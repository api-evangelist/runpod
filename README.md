# RunPod (runpod)

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
