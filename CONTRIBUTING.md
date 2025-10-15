# Contributing to Eclipse XFSC

Thanks for your interest in this project.

## Project description

Eclipse XFSC (Cross Federation Services Components) develops the software
components necessary to set up a federated system that interconnects several
participants in a data and service infrastructure with each other, aiming to
develop new data-driven services and innovative products. Such ecosystems
consist of joined interconnected data and infrastructure ecosystems, aggregated
in so-called Federations that are individually orchestrated and operated with
the help of Federation Services, part of Gaia-X. It consists of several
components (mainly microservices) enabling federations in data ecosystems and
providing interoperability across federations. The Eclipse XFSC Toolbox provides
a set of services for the functional implementation of Self Sovereign
Identities, W3C credential management, Trust Services, database functions for
knowledge graphs, usage policy negotiation and a core Low Code Engine. The main
purpose is the operational uptake of federations as decentralized ecosystems.
Eclipse XFSC is to be seen as the implementation of a suite of solutions â€“
providing for the minimum technical requirements to empower Federations to
become operational and to allow organizations to participate in a world of Self
Sovereign Identity and data ecosystems. The Eclipse XFSC toolbox defines a range
of components necessary to fulfil the Gaia-Xâ€™s objective of building trust and
interoperability, and ensuring participants retain sovereignty over their data.
Concretely, the first set of services delivered are: ICAM & Trust over IP
(Identity, Credential and Access Management) These services empower federated
ecosystems, like federations, to authenticate and authorise users and systems in
a decentralised, self-sovereign manner, ensuring trust without depending on a
central authority. These services utilise credential validation and technology
functionalities to maintain a consistent level of trust among all participants
in the federation. Authentication/Authorisation Service (AAS) Organisation
Credential Manager (OCM) Personal Credential Manager (PCM) Trust Services API
(TSA) Notarisation Service (NOT) Trust Management Infrastructure (TRAIN) Â 
Decenralised Catalogue and Contracting ServiceÂ  (CCS) The Decentralised
Catalogue and Contracting Service Â act as an inventory, allowing participants
to discover, understand, and use available data in an ecosystem. The Federated
Catalogue serves as a repository for a Federation, enabling participants to find
each other's information and services through Self-Descriptions. The toolbox
provides code for groups to create their own Catalogue and includes services for
contract negotiations and tracking data transactions, giving participants
control over their data usage within the group. Federated Catalogue (CAT)
Self-Description Wizard (SD-Wizard) Data Contract Services (DCS) Data Exchange
Logging Service (DELS) Â  Orchestration & Monitoring Orchestration and
Monitoring services are vital for managing complex ecosystems, ensuring seamless
and compliant operations. The distinction lies in their focus and functionality:
ORCE (Orchestration Engine) is tailored for orchestrating tasks, particularly
emphasizing complex application networking, while ORC (Orchestration) is
specifically designed for managing the life cycle of infrastructure services,
including deployment, updates, and deletion based on actions from consumers or
providers. Additionally, the Continuous Automated Monitoring (CAM) service
ensures transparency through automated compliance monitoring, providing insights
into service adherence to Federation rules. Orchestration Engine (ORCE) Service
Mesh Orchestrator, (ORC) Continuous Automated Monitoring (CAM) Â  Portal (POR)
The Portal within XFSC toolbox serves as an integration layer, highlighting
Federation Services and providing user-friendly access to onboarding,
accreditation, service discovery, orchestration, and delivery. It includes key
features such as searching, exploring, and displaying content from the Federated
Catalogue. Users can register and onboard new Participants, accessing onboarding
details, with the Federation approving registrations and issuing verified
credentials. Furthermore, Participants can orchestrate and provision services
through the portal. Â  Â 

* https://projects.eclipse.org/projects/technology.xfsc

## Terms of Use

This repository is subject to the Terms of Use of the Eclipse Foundation

* https://www.eclipse.org/legal/termsofuse.php

## Developer resources

Information regarding source code management, builds, coding standards, and
more.

* https://projects.eclipse.org/projects/technology.xfsc/developer

The project maintains the following source code repositories:

* https://github.com/eclipse-xfsc/org.eclipse.xfsc
* https://github.com/eclipse-xfsc/.github
* https://github.com/eclipse-xfsc/facis-fap
* https://github.com/eclipse-xfsc/dev-ops
* https://github.com/eclipse-xfsc/.eclipsefdn
* https://github.com/eclipse-xfsc/smartdeployment
* https://github.com/eclipse-xfsc/facis-poc
* https://github.com/eclipse-xfsc/data-exchange-logging
* https://github.com/eclipse-xfsc/train-integration-tests
* https://github.com/eclipse-xfsc/ssi-vdr-ipfs
* https://github.com/eclipse-xfsc/orchestrators
* https://github.com/eclipse-xfsc/cam
* https://github.com/eclipse-xfsc/custom-policy-agent
* https://github.com/eclipse-xfsc/cloud-event-provider
* https://github.com/eclipse-xfsc/train-dns-trust-zone-manager
* https://github.com/eclipse-xfsc/oid4-vci-authorization-bridge
* https://github.com/eclipse-xfsc/sd-creation-wizard-api
* https://github.com/eclipse-xfsc/gx-vc-verifier-npm
* https://github.com/eclipse-xfsc/trusted-info-hub
* https://github.com/eclipse-xfsc/sd-jwt-service
* https://github.com/eclipse-xfsc/portal-sp-service
* https://github.com/eclipse-xfsc/aries-integration-tests
* https://github.com/eclipse-xfsc/task-sheduler
* https://github.com/eclipse-xfsc/mobile-wallet
* https://github.com/eclipse-xfsc/portal-self-description-management
* https://github.com/eclipse-xfsc/portal-resource-provision-demo
* https://github.com/eclipse-xfsc/portal-lcm-service
* https://github.com/eclipse-xfsc/portal-integration
* https://github.com/eclipse-xfsc/portal-frontend
* https://github.com/eclipse-xfsc/portal-federated-catalogue-management
* https://github.com/eclipse-xfsc/portal-e2e-test-automation
* https://github.com/eclipse-xfsc/portal-discovery-service
* https://github.com/eclipse-xfsc/portal-demo
* https://github.com/eclipse-xfsc/portal-claim-mapping-service
* https://github.com/eclipse-xfsc/portal-claim-mapping-library
* https://github.com/eclipse-xfsc/cloud-wallet-web-ui
* https://github.com/eclipse-xfsc/cloud-wallet-plugin-core
* https://github.com/eclipse-xfsc/cloud-wallet-plugin-frontend-template
* https://github.com/eclipse-xfsc/cloud-wallet-plugin-backend-template
* https://github.com/eclipse-xfsc/cloud-wallet-integration-tests
* https://github.com/eclipse-xfsc/bdd-executor
* https://github.com/eclipse-xfsc/aas
* https://github.com/eclipse-xfsc/ssi-vdr-core
* https://github.com/eclipse-xfsc/sd-creation-wizard-frontend
* https://github.com/eclipse-xfsc/oid4-vci-vp-library
* https://github.com/eclipse-xfsc/oid4-vci-vp-integration-tests
* https://github.com/eclipse-xfsc/oid4-vci-issuer-service
* https://github.com/eclipse-xfsc/oid4-vci-issuer-dummycontentsigner
* https://github.com/eclipse-xfsc/did-core
* https://github.com/eclipse-xfsc/data-contract-transaction
* https://github.com/eclipse-xfsc/crypto-provider-luna-cloud-hsm-plugin
* https://github.com/eclipse-xfsc/crypto-provider-hashicorp-vault-plugin
* https://github.com/eclipse-xfsc/crypto-provider-local-plugin
* https://github.com/eclipse-xfsc/crypto-provider-core
* https://github.com/eclipse-xfsc/credential-storage-service
* https://github.com/eclipse-xfsc/portal-self-description-service
* https://github.com/eclipse-xfsc/aries-ssi-agent
* https://github.com/eclipse-xfsc/transmute-universal-resolver-driver
* https://github.com/eclipse-xfsc/cloud-wallet-plugin-kubernetes-operator
* https://github.com/eclipse-xfsc/did
* https://github.com/eclipse-xfsc/facis-fap1-implementation
* https://github.com/eclipse-xfsc/federated-catalogue
* https://github.com/eclipse-xfsc/facis
* https://github.com/eclipse-xfsc/trusted-cloud
* https://github.com/eclipse-xfsc/orchestration-engine
* https://github.com/eclipse-xfsc/oid4-vci-vp-well-known-service
* https://github.com/eclipse-xfsc/notarization-service
* https://github.com/eclipse-xfsc/microservice-core-go
* https://github.com/eclipse-xfsc/train-trust-framework-manager
* https://github.com/eclipse-xfsc/portal-did-management-service
* https://github.com/eclipse-xfsc/redis-cache-service
* https://github.com/eclipse-xfsc/ipfs-document-manager
* https://github.com/eclipse-xfsc/event-log-service
* https://github.com/eclipse-xfsc/crypto-provider-service
* https://github.com/eclipse-xfsc/oid4-vci-credential-retrieval-service
* https://github.com/eclipse-xfsc/nats-message-library
* https://github.com/eclipse-xfsc/oid4-vci-credential-verification-service
* https://github.com/eclipse-xfsc/didcomm-v2-connector
* https://github.com/eclipse-xfsc/email-service
* https://github.com/eclipse-xfsc/portal-article-service
* https://github.com/eclipse-xfsc/portal-user-account-service
* https://github.com/eclipse-xfsc/statuslist-service
* https://github.com/eclipse-xfsc/portal-admin-service
* https://github.com/eclipse-xfsc/portal-onboarding-service
* https://github.com/eclipse-xfsc/sd-validation-api
* https://github.com/eclipse-xfsc/portal-dashboard-service
* https://github.com/eclipse-xfsc/configuration-service
* https://github.com/eclipse-xfsc/ssi-jwt
* https://github.com/eclipse-xfsc/easy-stack-builder-catalogue
* https://github.com/eclipse-xfsc/easy-stack-builder-orce
* https://github.com/eclipse-xfsc/easy-stack-builder
* https://github.com/eclipse-xfsc/facis-fap2-implementation
* https://github.com/eclipse-xfsc/facis-aviation-poc
* https://github.com/eclipse-xfsc/aw40-demonstrator
* https://github.com/eclipse-xfsc/deployment
* https://github.com/eclipse-xfsc/docs
* https://github.com/eclipse-xfsc/landingpage
* https://github.com/eclipse-xfsc/cloud-wallet-account-service
* https://github.com/eclipse-xfsc/portal-proof-management-service
* https://github.com/eclipse-xfsc/cloud-wallet-plugin-discovery
* https://github.com/eclipse-xfsc/portal-principal-credential-creation-service
* https://github.com/eclipse-xfsc/portal-policy-management-service
* https://github.com/eclipse-xfsc/train-trusted-content-resolver
* https://github.com/eclipse-xfsc/workshops
* https://github.com/eclipse-xfsc/tsa-integration-tests
* https://github.com/eclipse-xfsc/crypto-provider-service-java
* https://github.com/eclipse-xfsc/integration
* https://github.com/eclipse-xfsc/mobile-wallet-integration-tests
* https://github.com/eclipse-xfsc/sd-schemas
* https://github.com/eclipse-xfsc/portal-pre-acceptance-testing
* https://github.com/eclipse-xfsc/portal-infra-mesh
* https://github.com/eclipse-xfsc/train-shared
* https://github.com/eclipse-xfsc/rego-policies
* https://github.com/eclipse-xfsc/didcomm-mediator-service

## Eclipse Development Process

This Eclipse Foundation open project is governed by the Eclipse Foundation
Development Process and operates under the terms of the Eclipse IP Policy.

* https://eclipse.org/projects/dev_process
* https://www.eclipse.org/org/documents/Eclipse_IP_Policy.pdf

## Eclipse Contributor Agreement

In order to be able to contribute to Eclipse Foundation projects you must
electronically sign the Eclipse Contributor Agreement (ECA).

* https://www.eclipse.org/legal/ECA.php

The ECA provides the Eclipse Foundation with a permanent record that you agree
that each of your contributions will comply with the commitments documented in
the Developer Certificate of Origin (DCO). Having an ECA on file associated with
the email address matching the "Author" field of your contribution's Git commits
fulfils the DCO's requirement that you sign-off on your contributions.

For more information, please see the Eclipse Committer Handbook:
https://www.eclipse.org/projects/handbook/#resources-commit

## Contact

Contact the project developers via the project's "dev" list.

* https://accounts.eclipse.org/mailing-list/xfsc-dev
