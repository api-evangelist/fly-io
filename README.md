# Fly Io

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Documentation and guides from the team at Fly.io.

**Areas:** Platform · Infrastructure · Edge Computing · Networking · Hosting · Deployment · Serverless

## Fly Io on APIs.io

Everything profiled for Fly Io is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fly-io/](https://apis.io/providers/fly-io/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Fly.io Machines API](https://apis.io/apis/fly-io/machines-api/) — The Fly.io Machines API is a low-level REST interface for provisioning and managing Fly Machines, which are fast-booting virtual machines that run on…
- [Fly.io GraphQL API](https://apis.io/apis/fly-io/graphql-api/) — The Fly.io GraphQL API provides a programmatic interface for managing Fly.io platform resources including applications, IP address allocations,…
- [Fly.io Extensions API](https://apis.io/apis/fly-io/extensions-api/) — The Fly.io Extensions API is a provider-facing HTTP interface that enables third-party services to integrate with the Fly.io platform as extension…
- [fly-io Apps API](https://apis.io/apis/fly-io/fly-io-apps-api/) — Operations for creating, listing, and deleting Fly Apps. Every Fly Machine belongs to a Fly App, which groups related Machines together.
- [fly-io SSO API](https://apis.io/apis/fly-io/fly-io-sso-api/) — Single sign-on operations allowing Fly.io users to access provider dashboards using their Fly.io credentials via OAuth.
- [fly-io Tokens API](https://apis.io/apis/fly-io/fly-io-tokens-api/) — Operations for requesting OpenID Connect (OIDC) tokens from third-party services, enabling Fly Machines to authenticate to external systems using workload…
- [fly-io Volumes API](https://apis.io/apis/fly-io/fly-io-volumes-api/) — Operations for managing persistent storage volumes that can be attached to Fly Machines. Volumes provide durable block storage that persists across Machine…
- [fly-io Webhooks API](https://apis.io/apis/fly-io/fly-io-webhooks-api/) — Webhook endpoints for bidirectional event delivery between Fly.io and extension providers. Both sides sign their webhook payloads using HMAC-SHA256 for…
- [Fly Io O Auth API](https://apis.io/apis/fly-io/fly-io-oauth-api/) — Fly.io platform OAuth endpoints used during the single sign-on flow to authorize users and exchange tokens.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Fly.io Extensions Webhook Events](https://apis.io/asyncapis/fly-io/fly-io-extensions-webhooks-asyncapi/)

#### Event channels (2)

Individual events and webhooks the provider emits.

- [/api/hooks/extensions/{provider_name}](https://apis.io/channels/fly-io/api-hooks-extensions-provider-name/)
- [/extensions/events](https://apis.io/channels/fly-io/extensions-events/)

#### GraphQL (1)

GraphQL schemas.

- [fly-io GraphQL API](https://apis.io/graphqls/fly-io/fly-io-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Fly Io Agentic Access](https://apis.io/agentic-access/fly-io/fly-io-agentic-access/)

#### JSON Schema (25)

The data models the API reads and writes.

- [App](https://apis.io/schemas/fly-io/fly-io-app/)
- [CloudEventPayload](https://apis.io/schemas/fly-io/fly-io-cloudeventpayload/)
- [CreateAppRequest](https://apis.io/schemas/fly-io/fly-io-createapprequest/)
- [CreateMachineRequest](https://apis.io/schemas/fly-io/fly-io-createmachinerequest/)
- [CreateVolumeRequest](https://apis.io/schemas/fly-io/fly-io-createvolumerequest/)
- [ErrorResponse](https://apis.io/schemas/fly-io/fly-io-errorresponse/)
- [ExtensionResource](https://apis.io/schemas/fly-io/fly-io-extensionresource/)
- [ExtensionWebhookPayload](https://apis.io/schemas/fly-io/fly-io-extensionwebhookpayload/)
- [Fly.io Machine](https://apis.io/schemas/fly-io/fly-io-machine/)
- [MachineCheck](https://apis.io/schemas/fly-io/fly-io-machinecheck/)
- [MachineConfig](https://apis.io/schemas/fly-io/fly-io-machineconfig/)
- [MachineGuest](https://apis.io/schemas/fly-io/fly-io-machineguest/)
- [MachineInit](https://apis.io/schemas/fly-io/fly-io-machineinit/)
- [MachineMount](https://apis.io/schemas/fly-io/fly-io-machinemount/)
- [MachinePort](https://apis.io/schemas/fly-io/fly-io-machineport/)
- [MachineRestart](https://apis.io/schemas/fly-io/fly-io-machinerestart/)
- [MachineService](https://apis.io/schemas/fly-io/fly-io-machineservice/)
- [MachineServiceConcurrency](https://apis.io/schemas/fly-io/fly-io-machineserviceconcurrency/)
- [OAuthTokenResponse](https://apis.io/schemas/fly-io/fly-io-oauthtokenresponse/)
- [Organization](https://apis.io/schemas/fly-io/fly-io-organization/)
- [ProvisionRequest](https://apis.io/schemas/fly-io/fly-io-provisionrequest/)
- [ProvisionResponse](https://apis.io/schemas/fly-io/fly-io-provisionresponse/)
- [TokenInfo](https://apis.io/schemas/fly-io/fly-io-tokeninfo/)
- [Fly.io Volume](https://apis.io/schemas/fly-io/fly-io-volume/)
- [VolumeSnapshot](https://apis.io/schemas/fly-io/fly-io-volumesnapshot/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Fly Io Structure](https://apis.io/json-structure/fly-io/fly-io-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Fly Io Context](https://apis.io/jsonld/fly-io/fly-io-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Fly-Io Domain Vocabulary](https://apis.io/vocabularies/fly-io/fly-io-vocabulary/)

#### Collections (8)

Postman and Open Collection request collections.

- [Fly.io Extensions Apps API](https://apis.io/collections/fly-io/open-fly-io-apps-api/)
- [Fly.io Apps Extensions API](https://apis.io/collections/fly-io/open-fly-io-extensions-api/)
- [Fly.io Extensions Apps Machines API](https://apis.io/collections/fly-io/open-fly-io-machines-api/)
- [Fly.io Extensions Apps OAuth API](https://apis.io/collections/fly-io/open-fly-io-oauth-api/)
- [Fly.io Extensions Apps SSO API](https://apis.io/collections/fly-io/open-fly-io-sso-api/)
- [Fly.io Extensions Apps Tokens API](https://apis.io/collections/fly-io/open-fly-io-tokens-api/)
- [Fly.io Extensions Apps Volumes API](https://apis.io/collections/fly-io/open-fly-io-volumes-api/)
- [Fly.io Extensions Apps Webhooks API](https://apis.io/collections/fly-io/open-fly-io-webhooks-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Fly Io — asyncapi rules](https://apis.io/rules/fly-io/fly-io-asyncapi-spectral-rules/)
- [Fly Io — jsonschema rules](https://apis.io/rules/fly-io/fly-io-jsonschema-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Fly Io Authentication](https://apis.io/security/fly-io/fly-io-authentication/)
- [Fly Io Domain Security](https://apis.io/security/fly-io/fly-io-domain-security/)
- [Fly Io Trust Center](https://apis.io/security/fly-io/fly-io-trust-center/)
- [Fly Io Vulnerability Disclosure](https://apis.io/security/fly-io/fly-io-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Fly Io Plans Pricing](https://apis.io/plans/fly-io/fly-io-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Fly Io Rate Limits](https://apis.io/rate-limits/fly-io/fly-io-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Fly Io Finops](https://apis.io/finops/fly-io/fly-io-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://fly.io)
- [Blog](https://fly.io/blog/feed.xml)
- [GitHub](https://github.com/superfly)

## API Evangelist rating

**Kin Score 34.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 66.0 |
| Contract governance | 13.6 |
| Operational transparency | 10.5 |
| Developer ergonomics | 23.8 |
| Access clarity | 15.8 |

**Agent readiness 21.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 27.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/fly-io/](https://apis.io/providers/fly-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Fly Io: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fly-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
