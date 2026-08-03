# Argo (argo)

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

Argo is a collection of open-source Kubernetes-native tools for workflows, events, CI/CD, and progressive delivery. The project includes Argo Workflows (container-native workflow engine), Argo CD (declarative GitOps continuous delivery), Argo Events (event-driven automation framework), and Argo Rollouts (progressive delivery with canary and blue-green strategies). Argo is a CNCF graduated project governed by the Linux Foundation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/argo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/argo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- CNCF
- CI/CD
- GitOps
- Kubernetes
- Open Source
- Progressive Delivery
- Workflow Engine

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Argo Workflows API

REST API for managing Argo Workflows, workflow templates, cron workflows, archived workflow records, events, and sensors on Kubernetes clusters. Authentication uses JWT bearer tokens from Kubernetes service accounts.

- **Human URL:** [https://argo-workflows.readthedocs.io/en/latest/rest-api/](https://argo-workflows.readthedocs.io/en/latest/rest-api/)
- **Base URL:** `https://localhost:2746/api/v1`

#### Tags

- Automation
- Kubernetes
- Workflow Engine

#### Properties

- [Documentation](https://argo-workflows.readthedocs.io/en/latest/)
- [API Reference](https://argo-workflows.readthedocs.io/en/latest/rest-api/)
- [OpenAPI](openapi/argo-workflows-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argo-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argo-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://argo-workflows.readthedocs.io/en/latest/quick-start/)

### Argo CD API

REST API for managing Argo CD GitOps applications, projects, repositories, clusters, and sync operations for Kubernetes declarative continuous delivery. Authentication uses JWT bearer tokens.

- **Human URL:** [https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)
- **Base URL:** `https://localhost/api/v1`

#### Tags

- Continuous Delivery
- GitOps
- Kubernetes

#### Properties

- [Documentation](https://argo-cd.readthedocs.io/en/stable/)
- [API Reference](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)
- [OpenAPI](openapi/argo-cd-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argo-cd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argo-cd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Argo Events API

Kubernetes-native API for the Argo Events event-driven automation framework. Exposes CRD-based resources including EventSource, EventBus, and Sensor for triggering Argo Workflows and Kubernetes actions in response to over 20 event types including webhooks, S3, cron, and messaging queues.

- **Human URL:** [https://argoproj.github.io/argo-events/APIs/](https://argoproj.github.io/argo-events/APIs/)

#### Tags

- Automation
- Event-Driven
- Events
- Kubernetes

#### Properties

- [Documentation](https://argoproj.github.io/argo-events/)
- [API Reference](https://argoproj.github.io/argo-events/APIs/)
- [GitHub Repository](https://github.com/argoproj/argo-events)
- [AsyncAPI](asyncapi/argo-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/argo-cd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argo-cd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/argo-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argo-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Argo Rollouts API

Kubernetes CRD-based API for Argo Rollouts progressive delivery controller. Provides Rollout and AnalysisTemplate resources for managing canary and blue-green deployment strategies with automated analysis, traffic splitting, and rollback capabilities.

- **Human URL:** [https://argo-rollouts.readthedocs.io/en/stable/](https://argo-rollouts.readthedocs.io/en/stable/)

#### Tags

- Blue-Green
- Canary
- Deployments
- Kubernetes
- Progressive Delivery

#### Properties

- [Documentation](https://argo-rollouts.readthedocs.io/en/stable/)
- [GitHub Repository](https://github.com/argoproj/argo-rollouts)
- [API Reference](https://argo-rollouts.readthedocs.io/en/stable/features/kubectl-plugin/)
- [Postman Collection](collections/argo-cd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argo-cd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/argo-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argo-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/argo-ai)
- [Website](https://argoproj.github.io/)
- [Documentation](https://argoproj.github.io/)
- [GitHub Organization](https://github.com/argoproj)
- [GitHub Repository](https://github.com/argoproj/argoproj)
- [Blog](https://blog.argoproj.io/)
- [Support](https://github.com/argoproj/argo-workflows/issues)
- [JSON-LD](json-ld/argo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/argo-spectral-rules.yml)
- [Vocabulary](vocabulary/argo-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
