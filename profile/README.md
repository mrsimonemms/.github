# Zigflow

[![Zigflow](https://raw.githubusercontent.com/zigflow/zigflow/main/designs/zigflow.png "Zigflow")](https://zigflow.dev?utm_source=github_org&utm_medium=readme&utm_campaign=header)

**Declarative YAML workflows on Temporal. No SDK boilerplate.**

Zigflow is an opinionated, open-source orchestration layer on top of [Temporal](https://temporal.io?utm_source=github_org&utm_medium=readme&utm_campaign=header). Define workflows as YAML, aligned with the [CNCF Serverless Workflow](https://serverlessworkflow.io?utm_source=github_org&utm_medium=readme&utm_campaign=header) specification, then run them with native Temporal reliability.

If you want reliable orchestration with less code and more guardrails, you're in the right place.

## Start here

- **Core project:** [zigflow/zigflow](https://github.com/zigflow/zigflow)
- **Docs:** [zigflow.dev](https://zigflow.dev?utm_source=github_org&utm_medium=readme&utm_campaign=header)
- **Community:** [slack.zigflow.dev](https://slack.zigflow.dev)

## What you get

- Declarative workflows that compile to fully featured Temporal workflows
- Validation before execution
- Native retries and durability via Temporal
- Multi-language activities (use any Temporal SDK)
- Kubernetes-friendly deployment (Helm chart in the core repo)
- Low-code and visual-ready foundations for workflow builders

## Quick taste

Install from the latest release and run the hello world example:

- [Latest release](https://github.com/zigflow/zigflow/releases/latest)
- [Hello world workflow](https://raw.githubusercontent.com/zigflow/zigflow/main/examples/hello-world/workflow.yaml)

```bash
zigflow run -f ./workflow.yaml
```

> If Zigflow looks useful, give the core project a ⭐ to help others discover it.
