# Fly.io (fly-io)
Fly.io is a cloud platform for deploying and running applications on a global edge infrastructure using fast-booting virtual machines. It provides developers with APIs for provisioning and managing machines, networking, and platform resources, including a low-level Machines REST API, a GraphQL API for platform operations, and an Extensions API for third-party service providers integrating with the Fly.io ecosystem.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Edge Computing, Infrastructure, Virtual Machines, Deployment, Platform, Cloud

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-28

## APIs

### Fly.io Machines API
The Fly.io Machines API is a low-level REST interface for provisioning and managing Fly Machines, which are fast-booting virtual machines that run on Fly.io's global edge infrastructure. It provides endpoints for creating, starting, stopping, and destroying Machines, as well as managing Fly Apps, Fly Volumes, and TLS certificates. The API is accessible publicly at https://api.machines.dev or internally within the Fly.io private WireGuard network at http://_api.internal:4280. All requests require bearer token authentication using a Fly.io API token, which can be obtained via the flyctl CLI.

**Human URL:** [https://fly.io/docs/machines/api/](https://fly.io/docs/machines/api/)


#### Tags:

 - Edge Computing, Infrastructure, Virtual Machines, Deployment, Platform

#### Properties

- [Documentation](https://fly.io/docs/machines/api/)
- [Documentation](https://fly.io/docs/machines/api/working-with-machines-api/)
- [OpenAPI](openapi/fly-io-machines-api-openapi.yml)

### Fly.io GraphQL API
The Fly.io GraphQL API provides a programmatic interface for managing Fly.io platform resources including applications, IP address allocations, organizations, and networking configuration. The endpoint includes an interactive GraphiQL explorer with schema introspection and documentation tabs accessible directly in the browser. Authentication requires an Authorization Bearer token, which can be obtained by running `flyctl auth token`. This API is primarily used for platform-level operations and is consumed internally by the flyctl CLI, though it is also available for direct integration by developers building tooling on top of the Fly.io platform.

**Human URL:** [https://api.fly.io/graphql](https://api.fly.io/graphql)


#### Tags:

 - GraphQL, Infrastructure, Platform, Deployment, Networking

#### Properties

- [Documentation](https://api.fly.io/graphql)

### Fly.io Extensions API
The Fly.io Extensions API is a provider-facing HTTP interface that enables third-party services to integrate with the Fly.io platform as extension providers. When a Fly.io user provisions an extension via the flyctl CLI, Fly.io forwards the provisioning request to the provider's API with details about the requesting organization, and the provider responds with environment variable configuration that is attached to the target application. Providers are also required to support single sign-on login flows and daily billing detail endpoints. Extensions currently available through this program include Sentry, Supabase, Tigris object storage, Upstash Redis and Vector, MySQL, and others.

**Human URL:** [https://fly.io/docs/reference/extensions_api/](https://fly.io/docs/reference/extensions_api/)


#### Tags:

 - Extensions, Platform, Integration, Provisioning, Partner

#### Properties

- [Documentation](https://fly.io/docs/reference/extensions_api/)
- [Documentation](https://fly.io/docs/about/extensions/)
- [OpenAPI](openapi/fly-io-extensions-api-openapi.yml)
- [AsyncAPI](asyncapi/fly-io-extensions-webhooks-asyncapi.yml)

## Common Properties

- [Portal](https://fly.io/docs/)
- [Documentation](https://fly.io/docs/)
- [Website](https://fly.io/)
- [PrivacyPolicy](https://fly.io/legal/privacy-policy/)
- [TermsOfService](https://fly.io/legal/terms-of-service/)
- [Support](https://community.fly.io/)
- [Blog](https://fly.io/blog/)
- [Login](https://fly.io/app/sign-in)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
