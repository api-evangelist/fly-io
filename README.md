# fly-io (fly-io)

Documentation and guides from the team at Fly.io.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Fly.io Machines API

The Fly.io Machines API is a low-level REST interface for provisioning and managing Fly Machines, which are fast-booting virtual machines that run on Fly.io's global edge infrastructure. It provides endpoints for creating, starting, stopping, and destroying Machines, as well as managing Fly Apps, Fly Volumes, and TLS certificates. The API is accessible publicly at https://api.machines.dev or internally within the Fly.io private WireGuard network at http://_api.internal:4280.

- **Human URL:** [https://fly.io/docs/machines/api/](https://fly.io/docs/machines/api/)
- **Base URL:** `https://api.machines.dev`

#### Tags

- Deployment
- Edge Computing
- Infrastructure
- Platform
- Virtual Machines

#### Properties

- [Documentation](https://fly.io/docs/machines/api/)
- [Documentation](https://fly.io/docs/machines/api/working-with-machines-api/)
- [OpenAPI](openapi/fly-io-machines-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fly-io-machines-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fly-io-machines-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fly.io GraphQL API

The Fly.io GraphQL API provides a programmatic interface for managing Fly.io platform resources including applications, IP address allocations, organizations, and networking configuration. The endpoint is available at https://api.fly.io/graphql and includes an interactive GraphiQL explorer with schema introspection and documentation tabs accessible directly in the browser. Authentication requires an Authorization Bearer token, which can be obtained by running `flyctl auth token`.

- **Human URL:** [https://api.fly.io/graphql](https://api.fly.io/graphql)
- **Base URL:** `https://api.fly.io/graphql`

#### Tags

- Deployment
- GraphQL
- Infrastructure
- Networking
- Platform

#### Properties

- [Documentation](https://api.fly.io/graphql)
- [Postman Collection](collections/fly-io-extensions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fly-io-extensions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fly-io-machines-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fly-io-machines-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fly.io Extensions API

The Fly.io Extensions API is a provider-facing HTTP interface that enables third-party services to integrate with the Fly.io platform as extension providers. When a Fly.io user provisions an extension via the flyctl CLI, Fly.io forwards the provisioning request to the provider's API with details about the requesting organization, and the provider responds with environment variable configuration that is attached to the target application.

- **Human URL:** [https://fly.io/docs/reference/extensions_api/](https://fly.io/docs/reference/extensions_api/)
- **Base URL:** `https://api.example.com`

#### Tags

- Extensions
- Integration
- Partner
- Platform
- Provisioning

#### Properties

- [Documentation](https://fly.io/docs/reference/extensions_api/)
- [Documentation](https://fly.io/docs/about/extensions/)
- [OpenAPI](openapi/fly-io-extensions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fly-io-extensions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fly-io-extensions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/fly-io-extensions-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/superfly)
- [LinkedIn](https://www.linkedin.com/company/fly-io)
- [JSON Schema](json-schema/fly-io-machine-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/fly-io-volume-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/fly-io-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
