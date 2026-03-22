# Argo (argo)
Argo is a collection of open source tools for Kubernetes-native workflows, events, CI/CD, and progressive delivery. It includes Argo Workflows for orchestrating parallel jobs, Argo CD for GitOps continuous delivery, Argo Events for event-driven automation, and Argo Rollouts for progressive delivery strategies.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/argo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Kubernetes, Workflows, CI/CD, GitOps

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

## APIs

### Argo Workflows API
REST API for managing Argo Workflows, workflow templates, cron workflows, and archived workflow records on Kubernetes clusters.

**Human URL:** [https://argo-workflows.readthedocs.io/en/latest/rest-api/](https://argo-workflows.readthedocs.io/en/latest/rest-api/)


#### Tags:

 - Kubernetes, Workflows, Automation

#### Properties

- [Documentation](https://argo-workflows.readthedocs.io/en/latest/)
- [Reference](https://argo-workflows.readthedocs.io/en/latest/rest-api/)
- [OpenAPI](openapi/argo-workflows-openapi.yml)
- [JSONSchema](json-schema/argo-workflow-schema.json)

### Argo CD API
API for managing Argo CD GitOps applications, projects, repositories, clusters, and sync operations for Kubernetes declarative continuous delivery.

**Human URL:** [https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)


#### Tags:

 - GitOps, Continuous Delivery, Kubernetes

#### Properties

- [Documentation](https://argo-cd.readthedocs.io/en/stable/)
- [Reference](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)
- [OpenAPI](openapi/argo-cd-openapi.yml)
- [JSONSchema](json-schema/argo-application-schema.json)

### Argo Events API
Kubernetes-native API for the Argo Events event-driven automation framework. Exposes CRD-based resources including EventSource, EventBus, and Sensor that enable triggering Argo Workflows and other Kubernetes actions in response to over 20 event types such as webhooks, S3, cron schedules, and messaging queues.

**Human URL:** [https://argoproj.github.io/argo-events/APIs/](https://argoproj.github.io/argo-events/APIs/)


#### Tags:

 - Events, Event-Driven, Kubernetes, Automation

#### Properties

- [Documentation](https://argoproj.github.io/argo-events/)
- [Reference](https://argoproj.github.io/argo-events/APIs/)
- [GitHubRepository](https://github.com/argoproj/argo-events)
- [AsyncAPI](asyncapi/argo-events-asyncapi.yml)

### Argo Rollouts API
Kubernetes CRD-based API for the Argo Rollouts progressive delivery controller. Provides Rollout and AnalysisTemplate resources for managing canary and blue-green deployment strategies with automated analysis, traffic splitting, and rollback capabilities on Kubernetes.

**Human URL:** [https://argo-rollouts.readthedocs.io/en/stable/](https://argo-rollouts.readthedocs.io/en/stable/)


#### Tags:

 - Progressive Delivery, Canary, Kubernetes, Deployments

#### Properties

- [Documentation](https://argo-rollouts.readthedocs.io/en/stable/)
- [GitHubRepository](https://github.com/argoproj/argo-rollouts)
- [JSONSchema](json-schema/argo-rollout-schema.json)

## Common Properties

- [Website](https://argoproj.github.io/)
- [Documentation](https://argo-workflows.readthedocs.io/en/latest/)
- [GitHub Organization](https://github.com/argoproj)
- [GitHubRepository](https://github.com/argoproj/argo-workflows)
- [Blog](https://blog.argoproj.io/)
- [Community](https://argoproj.github.io/community/)
- [Slack](https://argoproj.github.io/community/join-slack/)
- [JSON-LD](json-ld/argo-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
