# Nexus Repository Manager (nexus)

Nexus Repository Manager by Sonatype is an enterprise-grade artifact repository manager supporting multiple package formats including Maven, npm, Docker, PyPI, NuGet, RubyGems, Helm, Go, and more. It provides a central hub for managing software supply chain components, proxying remote repositories, hosting private artifacts, and grouping repositories. Nexus exposes a comprehensive REST API documented via an OpenAPI/Swagger specification served at `<nexus_url>/service/rest/swagger.json` on each instance.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/nexus/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Artifact Management
- DevOps
- Docker
- Maven
- Npm
- Package Management
- Repository Manager
- Software Supply Chain

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Nexus Repository Manager REST API

Comprehensive REST API for managing repositories, components, assets, search, security, blob stores, capabilities, tasks, tags, staging, and scripts in Sonatype Nexus Repository Manager 3. The full OpenAPI specification is available from each Nexus instance at `/service/rest/swagger.json` and is explorable via the built-in Swagger UI under System Settings > API.

**Human URL:** https://help.sonatype.com/repomanager3/integrations/rest-and-integration-api

**Base URL:** `https://your-nexus-instance.example.com/service/rest`

**Tags:** Assets, Blob Stores, Capabilities, Components, Repositories, REST, Search, Security, Staging, Tags, Tasks

**Properties:**

- [Documentation](https://help.sonatype.com/repomanager3/integrations/rest-and-integration-api)
- [Authentication](https://help.sonatype.com/repomanager3/integrations/rest-and-integration-api/authentication)
- [SwaggerUI](https://help.sonatype.com/repomanager3/integrations/rest-and-integration-api/api-reference-documentation)

> Note: This repository does not vendor a static OpenAPI spec because the spec is instance-specific and dynamically generated on each Nexus deployment. To obtain the spec, fetch `https://<your-nexus-host>/service/rest/swagger.json` from a running Nexus 3 instance.

## Common Properties

- [Website](https://www.sonatype.com/products/nexus-repository)
- [Documentation](https://help.sonatype.com/repomanager3)
- [Support](https://support.sonatype.com)
- [Getting Started](https://help.sonatype.com/repomanager3/getting-started)
- [GitHub](https://github.com/sonatype/nexus-public)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
