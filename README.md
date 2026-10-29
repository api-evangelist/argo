# Argo

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

Argo is a collection of open-source Kubernetes-native tools for workflows, events, CI/CD, and progressive delivery. The project includes Argo Workflows (container-native workflow engine), Argo CD (declarative GitOps continuous delivery), Argo Events (event-driven automation framework), and Argo Rollouts (progressive delivery with canary and blue-green strategies). Argo is a CNCF graduated project governed by the Linux Foundation.

**Areas:** CNCF · CI/CD · GitOps · Kubernetes · Open Source · Progressive Delivery · Workflow Engine · Cloud-Native · Graduated

## Argo on APIs.io

Everything profiled for Argo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/argo/](https://apis.io/providers/argo/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Argo Events API](https://apis.io/apis/argo/argo-events-api/) — Kubernetes-native API for the Argo Events event-driven automation framework. Exposes CRD-based resources including EventSource, EventBus, and Sensor for…
- [Argo Rollouts API](https://apis.io/apis/argo/argo-rollouts-api/) — Kubernetes CRD-based API for Argo Rollouts progressive delivery controller. Provides Rollout and AnalysisTemplate resources for managing canary and…
- [Argo Applications API](https://apis.io/apis/argo/argo-applications-api/) — Operations for creating, querying, syncing, and deleting Argo CD GitOps applications.
- [Argo Clusters API](https://apis.io/apis/argo/argo-clusters-api/) — Operations for registering and managing target Kubernetes clusters for application deployment.
- [Argo Cron Workflows API](https://apis.io/apis/argo/argo-cron-workflows-api/) — Operations for managing scheduled cron workflows
- [Argo Info API](https://apis.io/apis/argo/argo-info-api/) — Server information and version endpoints
- [Argo Projects API](https://apis.io/apis/argo/argo-projects-api/) — Operations for managing Argo CD projects that provide governance and access control for applications.
- [Argo Repositories API](https://apis.io/apis/argo/argo-repositories-api/) — Operations for registering and managing Git and Helm chart repositories used as application sources.
- [Argo Session API](https://apis.io/apis/argo/argo-session-api/) — Authentication operations for obtaining and invalidating bearer tokens.
- [Argo Settings API](https://apis.io/apis/argo/argo-settings-api/) — Operations for reading Argo CD server configuration and settings.
- [Argo Version API](https://apis.io/apis/argo/argo-version-api/) — Server version information endpoint.
- [Argo Workflow Archives API](https://apis.io/apis/argo/argo-workflow-archives-api/) — Operations for accessing archived workflow records
- [Argo Workflow Templates API](https://apis.io/apis/argo/argo-workflow-templates-api/) — Operations for managing reusable workflow templates
- [Argo Workflows API](https://apis.io/apis/argo/argo-workflows-api/) — Operations for managing workflow executions

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Argo Events](https://apis.io/asyncapis/argo/argo-events-asyncapi/)

#### Event channels (2)

Individual events and webhooks the provider emits.

- [/eventsource/{namespace}/{eventSourceName}/{eventName}](https://apis.io/channels/argo/eventsource-namespace-eventsourcename-eventname/)
- [/webhook/{eventName}](https://apis.io/channels/argo/webhook-eventname/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Argo Agentic Access](https://apis.io/agentic-access/argo/argo-agentic-access/)

#### JSON Schema (52)

The data models the API reads and writes.

- [Argo CD Application Spec](https://apis.io/schemas/argo/argo-application/)
- [AppProject](https://apis.io/schemas/argo/argo-cd-app-project/)
- [Application](https://apis.io/schemas/argo/argo-cd-application/)
- [ApplicationDestination](https://apis.io/schemas/argo/argo-cd-application-destination/)
- [ApplicationList](https://apis.io/schemas/argo/argo-cd-application-list/)
- [ApplicationSource](https://apis.io/schemas/argo/argo-cd-application-source/)
- [ApplicationSpec](https://apis.io/schemas/argo/argo-cd-application-spec/)
- [ApplicationStatus](https://apis.io/schemas/argo/argo-cd-application-status/)
- [Cluster](https://apis.io/schemas/argo/argo-cd-cluster/)
- [ClusterList](https://apis.io/schemas/argo/argo-cd-cluster-list/)
- [ProjectList](https://apis.io/schemas/argo/argo-cd-project-list/)
- [Repository](https://apis.io/schemas/argo/argo-cd-repository/)
- [RepositoryList](https://apis.io/schemas/argo/argo-cd-repository-list/)
- [Settings](https://apis.io/schemas/argo/argo-cd-settings/)
- [SyncPolicy](https://apis.io/schemas/argo/argo-cd-sync-policy/)
- [SyncRequest](https://apis.io/schemas/argo/argo-cd-sync-request/)
- [VersionMessage](https://apis.io/schemas/argo/argo-cd-version-message/)
- [Argo Rollout Spec](https://apis.io/schemas/argo/argo-rollout/)
- [Argo Workflow Spec](https://apis.io/schemas/argo/argo-workflow/)
- [Arguments](https://apis.io/schemas/argo/argo-workflows-arguments/)
- [Artifact](https://apis.io/schemas/argo/argo-workflows-artifact/)
- [CronWorkflow](https://apis.io/schemas/argo/argo-workflows-cron-workflow/)
- [CronWorkflowCreateRequest](https://apis.io/schemas/argo/argo-workflows-cron-workflow-create-request/)
- [CronWorkflowList](https://apis.io/schemas/argo/argo-workflows-cron-workflow-list/)
- [CronWorkflowSpec](https://apis.io/schemas/argo/argo-workflows-cron-workflow-spec/)
- …and 27 more published on APIs.io

#### JSON Structure (52)

Data models expressed in JSON Structure.

- [Argo Application Structure](https://apis.io/json-structure/argo/argo-application-structure/)
- [Argo Cd App Project Structure](https://apis.io/json-structure/argo/argo-cd-app-project-structure/)
- [Argo Cd Application Destination Structure](https://apis.io/json-structure/argo/argo-cd-application-destination-structure/)
- [Argo Cd Application List Structure](https://apis.io/json-structure/argo/argo-cd-application-list-structure/)
- [Argo Cd Application Source Structure](https://apis.io/json-structure/argo/argo-cd-application-source-structure/)
- [Argo Cd Application Spec Structure](https://apis.io/json-structure/argo/argo-cd-application-spec-structure/)
- [Argo Cd Application Status Structure](https://apis.io/json-structure/argo/argo-cd-application-status-structure/)
- [Argo Cd Application Structure](https://apis.io/json-structure/argo/argo-cd-application-structure/)
- [Argo Cd Cluster List Structure](https://apis.io/json-structure/argo/argo-cd-cluster-list-structure/)
- [Argo Cd Cluster Structure](https://apis.io/json-structure/argo/argo-cd-cluster-structure/)
- [Argo Cd Project List Structure](https://apis.io/json-structure/argo/argo-cd-project-list-structure/)
- [Argo Cd Repository List Structure](https://apis.io/json-structure/argo/argo-cd-repository-list-structure/)
- [Argo Cd Repository Structure](https://apis.io/json-structure/argo/argo-cd-repository-structure/)
- [Argo Cd Settings Structure](https://apis.io/json-structure/argo/argo-cd-settings-structure/)
- [Argo Cd Sync Policy Structure](https://apis.io/json-structure/argo/argo-cd-sync-policy-structure/)
- [Argo Cd Sync Request Structure](https://apis.io/json-structure/argo/argo-cd-sync-request-structure/)
- [Argo Cd Version Message Structure](https://apis.io/json-structure/argo/argo-cd-version-message-structure/)
- [Argo Rollout Structure](https://apis.io/json-structure/argo/argo-rollout-structure/)
- [Argo Workflow Structure](https://apis.io/json-structure/argo/argo-workflow-structure/)
- [Argo Workflows Arguments Structure](https://apis.io/json-structure/argo/argo-workflows-arguments-structure/)
- [Argo Workflows Artifact Structure](https://apis.io/json-structure/argo/argo-workflows-artifact-structure/)
- [Argo Workflows Cron Workflow Create Request Structure](https://apis.io/json-structure/argo/argo-workflows-cron-workflow-create-request-structure/)
- [Argo Workflows Cron Workflow List Structure](https://apis.io/json-structure/argo/argo-workflows-cron-workflow-list-structure/)
- [Argo Workflows Cron Workflow Spec Structure](https://apis.io/json-structure/argo/argo-workflows-cron-workflow-spec-structure/)
- [Argo Workflows Cron Workflow Status Structure](https://apis.io/json-structure/argo/argo-workflows-cron-workflow-status-structure/)
- …and 27 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Argo Context](https://apis.io/jsonld/argo/argo-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Argo Vocabulary](https://apis.io/vocabularies/argo/argo-vocabulary/)

#### Examples (52)

Example requests and responses.

- [Argo Application Example](https://apis.io/examples/argo/argo-application-example/)
- [Argo Cd App Project Example](https://apis.io/examples/argo/argo-cd-app-project-example/)
- [Argo Cd Application Destination Example](https://apis.io/examples/argo/argo-cd-application-destination-example/)
- [Argo Cd Application Example](https://apis.io/examples/argo/argo-cd-application-example/)
- [Argo Cd Application List Example](https://apis.io/examples/argo/argo-cd-application-list-example/)
- [Argo Cd Application Source Example](https://apis.io/examples/argo/argo-cd-application-source-example/)
- [Argo Cd Application Spec Example](https://apis.io/examples/argo/argo-cd-application-spec-example/)
- [Argo Cd Application Status Example](https://apis.io/examples/argo/argo-cd-application-status-example/)
- [Argo Cd Cluster Example](https://apis.io/examples/argo/argo-cd-cluster-example/)
- [Argo Cd Cluster List Example](https://apis.io/examples/argo/argo-cd-cluster-list-example/)
- [Argo Cd Project List Example](https://apis.io/examples/argo/argo-cd-project-list-example/)
- [Argo Cd Repository Example](https://apis.io/examples/argo/argo-cd-repository-example/)
- [Argo Cd Repository List Example](https://apis.io/examples/argo/argo-cd-repository-list-example/)
- [Argo Cd Settings Example](https://apis.io/examples/argo/argo-cd-settings-example/)
- [Argo Cd Sync Policy Example](https://apis.io/examples/argo/argo-cd-sync-policy-example/)
- [Argo Cd Sync Request Example](https://apis.io/examples/argo/argo-cd-sync-request-example/)
- [Argo Cd Version Message Example](https://apis.io/examples/argo/argo-cd-version-message-example/)
- [Argo Rollout Example](https://apis.io/examples/argo/argo-rollout-example/)
- [Argo Workflow Example](https://apis.io/examples/argo/argo-workflow-example/)
- [Argo Workflows Arguments Example](https://apis.io/examples/argo/argo-workflows-arguments-example/)
- [Argo Workflows Artifact Example](https://apis.io/examples/argo/argo-workflows-artifact-example/)
- [Argo Workflows Cron Workflow Create Request Example](https://apis.io/examples/argo/argo-workflows-cron-workflow-create-request-example/)
- [Argo Workflows Cron Workflow Example](https://apis.io/examples/argo/argo-workflows-cron-workflow-example/)
- [Argo Workflows Cron Workflow List Example](https://apis.io/examples/argo/argo-workflows-cron-workflow-list-example/)
- [Argo Workflows Cron Workflow Spec Example](https://apis.io/examples/argo/argo-workflows-cron-workflow-spec-example/)
- …and 27 more published on APIs.io

#### Collections (14)

Postman and Open Collection request collections.

- [Argo CD Applications API](https://apis.io/collections/argo/open-argo-applications-api/)
- [Argo CD API](https://apis.io/collections/argo/open-argo-cd/)
- [Argo CD Applications Clusters API](https://apis.io/collections/argo/open-argo-clusters-api/)
- [Argo CD Applications Cron Workflows API](https://apis.io/collections/argo/open-argo-cron-workflows-api/)
- [Argo CD Applications Info API](https://apis.io/collections/argo/open-argo-info-api/)
- [Argo CD Applications Projects API](https://apis.io/collections/argo/open-argo-projects-api/)
- [Argo CD Applications Repositories API](https://apis.io/collections/argo/open-argo-repositories-api/)
- [Argo CD Applications Session API](https://apis.io/collections/argo/open-argo-session-api/)
- [Argo CD Applications Settings API](https://apis.io/collections/argo/open-argo-settings-api/)
- [Argo CD Applications Version API](https://apis.io/collections/argo/open-argo-version-api/)
- [Argo CD Applications Workflow Archives API](https://apis.io/collections/argo/open-argo-workflow-archives-api/)
- [Argo CD Applications Workflow Templates API](https://apis.io/collections/argo/open-argo-workflow-templates-api/)
- [Argo Workflows API](https://apis.io/collections/argo/open-argo-workflows/)
- [Argo CD Applications Workflows API](https://apis.io/collections/argo/open-argo-workflows-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Argo — asyncapi rules](https://apis.io/rules/argo/argo-asyncapi-spectral-rules/)
- [Argo — jsonschema rules](https://apis.io/rules/argo/argo-jsonschema-spectral-rules/)
- [Argo API Rules](https://apis.io/rules/argo/argo-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Argo Authentication](https://apis.io/security/argo/argo-authentication/)
- [Argo Domain Security](https://apis.io/security/argo/argo-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Argo Plans Pricing](https://apis.io/plans/argo/argo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Argo Rate Limits](https://apis.io/rate-limits/argo/argo-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Argo Finops](https://apis.io/finops/argo/argo-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://argoproj.github.io/)
- [Documentation](https://argoproj.github.io/)
- [Support](https://github.com/argoproj/argo-workflows/issues)
- [Blog](https://blog.argoproj.io/)
- [GitHub](https://github.com/argoproj)

## API Evangelist rating

**Kin Score 46.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 63.4 |
| Contract governance | 27.3 |
| Operational transparency | 36.8 |
| Developer ergonomics | 47.6 |
| Access clarity | 7.9 |

**Agent readiness 24.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/argo/](https://apis.io/providers/argo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Argo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/argo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
