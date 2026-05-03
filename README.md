# Ubuntu

Collection of APIs and services provided by Canonical for Ubuntu and related products. Includes the Snap Store API for package management, Launchpad API for project hosting and bug tracking, Ubuntu Security CVE API for vulnerability intelligence, and enterprise services including Ubuntu Pro, MAAS, Juju, and Landscape.

**URL:** [https://ubuntu.com](https://ubuntu.com)

## Scope

- **Type:** Index

## Tags

Cloud, Containers, Devops, Enterprise, Linux, Security, Ubuntu, Package Management, Open Source

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-03

## APIs

### Launchpad API
REST API for Launchpad — Ubuntu's project hosting and collaboration platform. OAuth 1.0a auth, WADL-described resources.

**Human URL:** [https://launchpad.net/](https://launchpad.net/)

#### Tags
Bugs, Collaboration, Distributions, Packages, Projects

#### Properties
- [Documentation](https://launchpad.net/+apidoc/)
- [Authentication](https://help.launchpad.net/API/Uses)
- [Wadl](https://api.launchpad.net/devel)
- [OpenAPI](openapi/ubuntu-launchpad-openapi.yml)

---

### Ubuntu Pro API
API for managing Ubuntu Pro subscriptions, entitlements, and extended security maintenance.

**Human URL:** [https://ubuntu.com/pro](https://ubuntu.com/pro)

#### Tags
Enterprise, Security, Subscriptions, Support

#### Properties
- [Documentation](https://canonical-ubuntu-pro-client.readthedocs-hosted.com/)

---

### Snap Store API
API for discovering, searching, and managing snap packages in the Canonical Snap Store.

**Human URL:** [https://snapcraft.io/](https://snapcraft.io/)

#### Tags
Applications, Distribution, Packages, Snaps, Package Management

#### Properties
- [Documentation](https://snapcraft.io/docs/snapcraft-store-api)
- [OpenAPI](openapi/ubuntu-snap-store-openapi.yml)
- [Example](examples/ubuntu-snap-search-example.json)
- [JSONSchema](json-schema/ubuntu-snap-schema.json)

---

### Ubuntu Archive API
Access to Ubuntu package repositories and archive information.

**Human URL:** [https://archive.ubuntu.com/](https://archive.ubuntu.com/)

#### Tags
Archives, Packages, Releases, Repositories

---

### Landscape API
Systems management API for Ubuntu server fleet management and patch automation.

**Human URL:** [https://ubuntu.com/landscape](https://ubuntu.com/landscape)

#### Tags
Automation, Management, Monitoring, Servers

#### Properties
- [Documentation](https://ubuntu.com/landscape/docs/api)

---

### MAAS API
Metal as a Service API for bare-metal infrastructure provisioning.

**Human URL:** [https://maas.io/](https://maas.io/)

#### Tags
Bare-Metal, Cloud, Infrastructure, Provisioning

#### Properties
- [Documentation](https://maas.io/docs/api)

---

### Juju API
Application modeling and deployment API for multi-cloud orchestration.

**Human URL:** [https://juju.is/](https://juju.is/)

#### Tags
Automation, Deployment, Devops, Orchestration

#### Properties
- [Documentation](https://juju.is/docs/juju/api)

---

### Ubuntu CVE API
API for querying Ubuntu's CVE security database, security notices, and package patch status.

**Human URL:** [https://ubuntu.com/security/cves](https://ubuntu.com/security/cves)

#### Tags
CVE, Patches, Security, Vulnerabilities

#### Properties
- [OpenAPI](openapi/ubuntu-cve-openapi.yml)
- [Example](examples/ubuntu-cve-list-example.json)
- [JSONSchema](json-schema/ubuntu-cve-schema.json)

---

## Artifacts

### OpenAPI Specifications
| File | Description |
|------|-------------|
| [openapi/ubuntu-launchpad-openapi.yml](openapi/ubuntu-launchpad-openapi.yml) | Launchpad REST API |
| [openapi/ubuntu-snap-store-openapi.yml](openapi/ubuntu-snap-store-openapi.yml) | Snap Store Devices API |
| [openapi/ubuntu-cve-openapi.yml](openapi/ubuntu-cve-openapi.yml) | Ubuntu Security CVE API |

### Naftiko Capabilities
| File | Description |
|------|-------------|
| [capabilities/package-and-security-management.yaml](capabilities/package-and-security-management.yaml) | Snap Store + CVE combined workflow (5 tools) |

**Shared definitions:** `capabilities/shared/snap-store.yaml`, `capabilities/shared/security-cve.yaml`

### Rules
- [rules/ubuntu-rules.yml](rules/ubuntu-rules.yml)

### JSON Schema
- [json-schema/ubuntu-snap-schema.json](json-schema/ubuntu-snap-schema.json)
- [json-schema/ubuntu-cve-schema.json](json-schema/ubuntu-cve-schema.json)

### JSON Structure
- [json-structure/ubuntu-snap-structure.json](json-structure/ubuntu-snap-structure.json)

### JSON-LD
- [json-ld/ubuntu-context.jsonld](json-ld/ubuntu-context.jsonld)

### Examples
- [examples/ubuntu-snap-search-example.json](examples/ubuntu-snap-search-example.json)
- [examples/ubuntu-cve-list-example.json](examples/ubuntu-cve-list-example.json)

### Vocabulary
- [vocabulary/ubuntu-vocabulary.yml](vocabulary/ubuntu-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
