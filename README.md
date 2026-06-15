# RunPod (runpod)

RunPod is a managed GPU cloud and serverless inference platform offering on-demand and persistent GPU Pods, autoscaling Serverless endpoints, network volumes, container templates, and a REST + GraphQL control plane for provisioning H100, H200, B200, A100, L40S, and consumer RTX GPUs. RunPod targets AI/ML developers who need flexible, per-second-billed GPU compute for training, fine-tuning, and inference workloads.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/runpod/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/runpod/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- AI
- Cloud
- Compute
- GPU
- Inference
- Machine Learning
- Serverless

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### RunPod REST API

The RunPod REST API programmatically manages Pods, Serverless endpoints, network volumes, templates, container registry auth, and billing. The API is the primary control plane for provisioning and operating GPU compute on RunPod.

- **Human URL:** [https://docs.runpod.io/api-reference/overview](https://docs.runpod.io/api-reference/overview)
- **Base URL:** `https://rest.runpod.io/v1`

#### Tags

- Billing
- Compute
- GPU
- Pods
- REST
- Serverless
- Storage
- Templates

#### Properties

- [Documentation](https://docs.runpod.io/api-reference/overview)
- [OpenAPI](https://rest.runpod.io/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runpod.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runpod.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RunPod GraphQL API

The RunPod GraphQL API provides programmatic access to Pods, templates, and Serverless endpoints via GraphQL queries and mutations. It is the original control-plane interface and is still supported alongside the REST API.

- **Human URL:** [https://docs.runpod.io/sdks/graphql/configurations](https://docs.runpod.io/sdks/graphql/configurations)
- **Base URL:** `https://api.runpod.io/graphql`

#### Tags

- Compute
- GPU
- GraphQL
- Pods
- Serverless
- Templates

#### Properties

- [Documentation](https://docs.runpod.io/sdks/graphql/configurations)
- [Postman Collection](collections/runpod.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runpod.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RunPod Serverless

RunPod Serverless provides pay-as-you-go inference endpoints with autoscaling workers, queue-based and load-balanced endpoint types, FlashBoot cold-start optimization, and per-second billing. Each endpoint exposes a URL that accepts request payloads for AI model inference and compute-intensive workloads.

- **Human URL:** [https://docs.runpod.io/serverless/overview](https://docs.runpod.io/serverless/overview)
- **Base URL:** `https://api.runpod.ai/v2`

#### Tags

- AI
- Autoscaling
- GPU
- Inference
- Serverless
- Workers

#### Properties

- [Documentation](https://docs.runpod.io/serverless/overview)
- [Postman Collection](collections/runpod.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runpod.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://runpod.io)
- [Developer](https://docs.runpod.io)
- [Documentation](https://docs.runpod.io)
- [Portal](https://console.runpod.io)
- [Sign Up](https://www.runpod.io/console/signup)
- [Login](https://www.runpod.io/console/signin)
- [Pricing](https://www.runpod.io/pricing)
- [Blog](https://blog.runpod.io)
- [Status Page](https://uptime.runpod.io)
- [Terms of Service](https://www.runpod.io/legal/terms-of-service)
- [Privacy Policy](https://www.runpod.io/legal/privacy-policy)
- [GitHub Organization](https://github.com/runpod)
- [Support](https://www.runpod.io/contact)
- [Changelog](https://docs.runpod.io/changelog)
- [SDK](https://github.com/runpod/runpod-python)
- [C L I](https://github.com/runpod/runpodctl)
- [Terraform](https://github.com/runpod/pulumi-runpod)
- [Features](undefined)
- [Integrations](undefined)
- [G P Us](undefined)
- [L L Ms Txt](https://docs.runpod.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
