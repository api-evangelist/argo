# Argo (argo)
Argo is a collection of open-source Kubernetes-native tools for workflows, events, CI/CD, and progressive delivery. The project includes Argo Workflows (container-native workflow engine), Argo CD (declarative GitOps continuous delivery), Argo Events (event-driven automation framework), and Argo Rollouts (progressive delivery with canary and blue-green strategies). Argo is a CNCF graduated project governed by the Linux Foundation.

**URL:** [https://argoproj.github.io/](https://argoproj.github.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - CNCF, CI/CD, GitOps, Kubernetes, Open Source, Progressive Delivery, Workflow Engine

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Argo Workflows API
REST API for managing Argo Workflows, workflow templates, cron workflows, archived workflow records, events, and sensors on Kubernetes clusters.

**Human URL:** [https://argo-workflows.readthedocs.io/en/latest/rest-api/](https://argo-workflows.readthedocs.io/en/latest/rest-api/)

#### Tags:

 - Automation, Kubernetes, Workflow Engine

#### Properties

- [Documentation](https://argo-workflows.readthedocs.io/en/latest/)
- [APIReference](https://argo-workflows.readthedocs.io/en/latest/rest-api/)
- [OpenAPI](openapi/argo-workflows-openapi.yml)
- [GettingStarted](https://argo-workflows.readthedocs.io/en/latest/quick-start/)

### Argo CD API
REST API for managing Argo CD GitOps applications, projects, repositories, clusters, and sync operations.

**Human URL:** [https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)

#### Tags:

 - Continuous Delivery, GitOps, Kubernetes

#### Properties

- [Documentation](https://argo-cd.readthedocs.io/en/stable/)
- [APIReference](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)
- [OpenAPI](openapi/argo-cd-openapi.yml)

### Argo Events API
Kubernetes-native API for event-driven automation supporting 20+ event sources for triggering workflows.

**Human URL:** [https://argoproj.github.io/argo-events/APIs/](https://argoproj.github.io/argo-events/APIs/)

#### Tags:

 - Automation, Event-Driven, Events, Kubernetes

#### Properties

- [Documentation](https://argoproj.github.io/argo-events/)
- [APIReference](https://argoproj.github.io/argo-events/APIs/)
- [GitHubRepository](https://github.com/argoproj/argo-events)
- [AsyncAPI](asyncapi/argo-events-asyncapi.yml)

### Argo Rollouts API
Kubernetes CRD-based API for progressive delivery with canary and blue-green strategies.

**Human URL:** [https://argo-rollouts.readthedocs.io/en/stable/](https://argo-rollouts.readthedocs.io/en/stable/)

#### Tags:

 - Blue-Green, Canary, Deployments, Kubernetes, Progressive Delivery

#### Properties

- [Documentation](https://argo-rollouts.readthedocs.io/en/stable/)
- [GitHubRepository](https://github.com/argoproj/argo-rollouts)
- [APIReference](https://argo-rollouts.readthedocs.io/en/stable/features/kubectl-plugin/)

## Common Properties

- [Website](https://argoproj.github.io/)
- [GitHubOrganization](https://github.com/argoproj)
- [GitHubRepository](https://github.com/argoproj/argoproj)
- [Blog](https://blog.argoproj.io/)
- [JSON-LD](json-ld/argo-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Argo Workflows | Container-native workflow engine for orchestrating parallel jobs and ML pipelines on Kubernetes. |
| Argo CD | Declarative GitOps continuous delivery tool that syncs Kubernetes application state from Git. |
| Argo Events | Event-driven automation framework supporting 20+ event sources to trigger Kubernetes workflows. |
| Argo Rollouts | Progressive delivery controller with canary, blue-green, and experiment strategies for Kubernetes. |
| CNCF Graduated | All four Argo projects are CNCF graduated, ensuring production-quality governance and stability. |
| Kubernetes-Native | All tools are implemented as Kubernetes CRDs and controllers, integrating natively with the platform. |

## Use Cases

| Name | Description |
|------|-------------|
| GitOps Platform | Combine Argo CD and Argo Workflows for a complete Git-driven DevOps platform on Kubernetes. |
| Machine Learning Pipelines | Use Argo Workflows to orchestrate multi-step ML training, evaluation, and deployment pipelines. |
| Event-Driven Automation | Use Argo Events to trigger workflows based on webhooks, schedules, messaging, and cloud events. |
| Progressive Delivery | Use Argo Rollouts for safe canary and blue-green deployments with automated analysis and rollback. |
| CI/CD on Kubernetes | Build complete CI/CD pipelines natively on Kubernetes using Argo Workflows and Argo CD together. |

## Integrations

| Name | Description |
|------|-------------|
| Helm | Argo CD natively renders Helm charts; Argo Workflows can execute Helm operations as steps. |
| Kustomize | Argo CD supports Kustomize overlays for environment-specific application configuration. |
| Prometheus | All Argo tools expose Prometheus metrics for monitoring workflow and deployment health. |
| Slack | Argo CD and Argo Workflows support Slack notifications for deployment and workflow events. |
| GitHub | Deep integration with GitHub webhooks for triggering workflows and CD syncs. |
| Amazon S3 | Argo Workflows uses S3 as an artifact repository for passing data between workflow steps. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Argo Workflows OpenAPI](openapi/argo-workflows-openapi.yml)
- [Argo CD OpenAPI](openapi/argo-cd-openapi.yml)

### AsyncAPI

- [Argo Events AsyncAPI](asyncapi/argo-events-asyncapi.yml)

### JSON Schema

52 schema files in [json-schema/](json-schema/)

### JSON Structure

52 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Argo Context](json-ld/argo-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Argo Workflows API](capabilities/shared/argo-workflows-api.yaml) — 2 operations for workflow management
- [Argo CD API](capabilities/shared/argo-cd-api.yaml) — 2 operations for GitOps application management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Argo Platform](capabilities/argo-platform.yaml) | Argo Workflows, Argo CD | 4 | Platform Engineer, DevOps Engineer |

## Vocabulary

- [Argo Vocabulary](vocabulary/argo-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Argo Spectral Rules](rules/argo-spectral-rules.yml) — 9 rules across 4 categories enforcing Argo API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
