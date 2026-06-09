# jardisOps

**JARDIS** — *Just A Reliable Domain Integration System* — is a platform for Domain-Driven Design in the PHP ecosystem. You model your domain; Jardis generates the production-ready hexagonal code. → [jardis.io](https://jardis.io)

---

**jardisOps** provides the operational infrastructure for running PHP applications built on the Jardis platform: purpose-built Docker images for PHP CLI and PHP-FPM workloads, and provisioning tooling for cloud environments.

> The platform that generates hexagonal DDD code for PHP is available at [jardis.io](https://jardis.io).

---

## Packages

| Package | Description |
|---|---|
| phpcli | Docker image for PHP CLI workloads — scheduled tasks, queue workers, and command-line tooling for Jardis-based applications |
| phpfpm | Docker image for PHP-FPM — optimised for serving Jardis-generated application code behind a reverse proxy |
| provisioning | Cloud provisioning tooling for PHP application infrastructure |

---

## Scope

jardisOps covers the runtime and deployment layer. Application architecture — hexagonal structure, domain modelling, use-case generation — is handled by the Jardis platform and the packages in jardisCore, jardisAdapter, and jardisSupport.

MIT License (where applicable) · See individual repositories for licensing details
