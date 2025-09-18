name: Update CONTRIBUTING with org repositories

on:
  schedule:
    # alle 2 Wochen montags um 02:30 UTC
    - cron: "30 2 * * 1/2"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  update-contributing:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Install GitHub CLI + jq
        run: sudo apt-get update && sudo apt-get install -y gh jq

      - name: Fetch repo list
        env:
          GH_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        run: |
          gh repo list eclipse-xfsc --limit 500 --json nameWithOwner,isArchived,isPrivate \
            | jq -r '.[] | select(.isArchived==false) | select(.isPrivate==false) | .nameWithOwner' \
            | sed 's#^#* https://github.com/#' > repo_list.txt

      - name: Replace Developer resources section in CONTRIBUTING.md
        run: |
          # Header bis Developer resources kopieren
          sed -n '1,/^## Developer resources/p' CONTRIBUTING.md > CONTRIBUTING.new

          # Neue Section einfügen
          {
            echo
            echo "Information regarding source code management, builds, coding standards, and"
            echo "more."
            echo
            echo "* https://projects.eclipse.org/projects/technology.xfsc/developer"
            echo
            echo "The project maintains the following source code repositories:"
            echo
            cat repo_list.txt
            echo
          } >> CONTRIBUTING.new

          # Rest (nächstes Kapitel oder Datei-Ende) anhängen
          # Falls du ein fixes Kapitel nach Developer resources hast, ersetze '## ' durch dessen Marker
          sed -n '/^## [A-Z]/,/^$/p' CONTRIBUTING.md | tail -n +2 >> CONTRIBUTING.new || true

          mv CONTRIBUTING.new CONTRIBUTING.md

      - name: Commit and push changes
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "github-actions[bot]@users.noreply.github.com"
          git add CONTRIBUTING.md
          git commit -m "chore: update CONTRIBUTING.md with latest repos from eclipse-xfsc org" || echo "No changes"
          git push
