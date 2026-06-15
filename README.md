# Ubuntu (ubuntu)

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
