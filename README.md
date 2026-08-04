# Ubuntu (ubuntu)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Collection of APIs and services provided by Canonical for Ubuntu and related products. Includes the Snap Store API for package management, Launchpad API for project hosting and bug tracking, Ubuntu Security CVE API for vulnerability intelligence, and enterprise services including Ubuntu Pro, MAAS, Juju, and Landscape.

**APIs.json:** [https://ubuntu.com](https://ubuntu.com)

## Tags

- Cloud
- Containers
- Devops
- Enterprise
- Linux
- Security
- Ubuntu
- Package Management
- Open Source

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Launchpad API

REST API for Launchpad, Ubuntu's project hosting and collaboration platform. Provides access to people, projects, bugs, packages, branches, and distributions. Uses OAuth 1.0a authentication and WADL-described resources.

- **Human URL:** [https://launchpad.net/](https://launchpad.net/)
- **Base URL:** `https://api.launchpad.net/1.0`

#### Tags

- Bugs
- Collaboration
- Distributions
- Packages
- Projects
- Open Source

#### Properties

- [Documentation](https://launchpad.net/+apidoc/)
- [Documentation](https://documentation.ubuntu.com/launchpad/user/explanation/launchpad-api/launchpad-web-service/)
- [Authentication](https://help.launchpad.net/API/Uses)
- [Wadl](https://api.launchpad.net/devel)
- [OpenAPI](openapi/ubuntu-launchpad-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ubuntu-launchpad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-launchpad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ubuntu Pro API

API for managing Ubuntu Pro subscriptions and entitlements, including security patches, compliance tooling, and extended security maintenance.

- **Human URL:** [https://ubuntu.com/pro](https://ubuntu.com/pro)
- **Base URL:** `https://contracts.canonical.com/`

#### Tags

- Enterprise
- Security
- Subscriptions
- Support

#### Properties

- [Documentation](https://canonical-ubuntu-pro-client.readthedocs-hosted.com/)
- [Authentication](https://ubuntu.com/pro/dashboard)
- [Postman Collection](collections/ubuntu-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-launchpad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-launchpad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-snap-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-snap-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snap Store API

API for the Snap Store for publishing and managing snap packages. Enables snap search, package info retrieval, refresh operations, category listings, and usage metrics for IoT and desktop deployments.

- **Human URL:** [https://snapcraft.io/](https://snapcraft.io/)
- **Base URL:** `https://api.snapcraft.io`

#### Tags

- Applications
- Distribution
- Packages
- Snaps
- Package Management

#### Properties

- [Documentation](https://snapcraft.io/docs/snapcraft-store-api)
- [Documentation](https://api.snapcraft.io/docs/)
- [Dashboard](https://snapcraft.io/account)
- [Developer  Portal](https://snapcraft.io/docs)
- [OpenAPI](openapi/ubuntu-snap-store-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ubuntu-snap-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-snap-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/ubuntu-snap-search-example.json)
- [JSON Schema](json-schema/ubuntu-snap-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Ubuntu Archive API

Access to Ubuntu package repositories and archive information via the Launchpad API's Ubuntu distribution endpoint.

- **Human URL:** [https://archive.ubuntu.com/](https://archive.ubuntu.com/)
- **Base URL:** `https://api.launchpad.net/devel/ubuntu`

#### Tags

- Archives
- Packages
- Releases
- Repositories

#### Properties

- [Documentation](https://wiki.ubuntu.com/ArchiveAdministration)
- [Package  Search](https://packages.ubuntu.com/)
- [Postman Collection](collections/ubuntu-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-launchpad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-launchpad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-snap-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-snap-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Landscape API

Systems management API for Ubuntu servers enabling automated patch management, compliance reporting, and fleet monitoring for Ubuntu deployments.

- **Human URL:** [https://ubuntu.com/landscape](https://ubuntu.com/landscape)
- **Base URL:** `https://landscape.canonical.com/api/`

#### Tags

- Automation
- Management
- Monitoring
- Servers

#### Properties

- [Documentation](https://ubuntu.com/landscape/docs/api)
- [Authentication](https://ubuntu.com/landscape/docs/api-authentication)
- [Postman Collection](collections/ubuntu-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-launchpad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-launchpad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-snap-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-snap-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MAAS API

Metal as a Service API for physical server provisioning, enabling automated bare-metal infrastructure management and cloud-like workflows.

- **Human URL:** [https://maas.io/](https://maas.io/)
- **Base URL:** `https://maas.io/docs/api`

#### Tags

- Bare-Metal
- Cloud
- Infrastructure
- Provisioning

#### Properties

- [Documentation](https://maas.io/docs/api)
- [Git Hub](https://github.com/canonical/maas)
- [Postman Collection](collections/ubuntu-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-launchpad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-launchpad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-snap-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-snap-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Juju API

Application modeling and deployment API supporting automated deployment, scaling, and management of applications across clouds and bare metal.

- **Human URL:** [https://juju.is/](https://juju.is/)
- **Base URL:** `wss://[controller-address]:17070/api`

#### Tags

- Automation
- Deployment
- Devops
- Orchestration

#### Properties

- [Documentation](https://juju.is/docs/juju/api)
- [Git Hub](https://github.com/juju/juju)
- [Postman Collection](collections/ubuntu-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-launchpad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-launchpad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ubuntu-snap-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-snap-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ubuntu CVE API

API for Ubuntu security notices and CVE vulnerability information, enabling programmatic queries of the Ubuntu CVE database including affected packages and patch status across Ubuntu releases.

- **Human URL:** [https://ubuntu.com/security/cves](https://ubuntu.com/security/cves)
- **Base URL:** `https://ubuntu.com/security`

#### Tags

- Cve
- Patches
- Security
- Vulnerabilities

#### Properties

- [Documentation](https://ubuntu.com/security/api)
- [R S S](https://ubuntu.com/security/notices/rss.xml)
- [OpenAPI](openapi/ubuntu-cve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ubuntu-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ubuntu-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/ubuntu-cve-list-example.json)
- [JSON Schema](json-schema/ubuntu-cve-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/ubuntu-linux)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
