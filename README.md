# Argo (argo)

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
