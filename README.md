# Google Cloud Deploy (google-cloud-deploy)

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

Google Cloud Deploy is a managed continuous delivery service that automates the deployment of applications to Google Cloud target environments such as GKE, Cloud Run, and Anthos. It provides an opinionated delivery pipeline that promotes releases through a series of target environments with approval gates, rollback capabilities, and deployment verification, enabling safe and repeatable software delivery workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-cloud-deploy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-cloud-deploy/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Continuous Delivery
- Deployment
- DevOps
- Kubernetes
- Pipeline
- Release Management

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Cloud Deploy API

The Cloud Deploy API provides programmatic access to manage delivery pipelines, targets, releases, and rollouts for continuous delivery workflows. Developers can use the API to create and manage delivery pipelines that define the progression of releases through target environments, create releases from build artifacts, promote releases between targets, approve rollouts, and manage rollback operations.

- **Human URL:** [https://cloud.google.com/deploy/docs](https://cloud.google.com/deploy/docs)
- **Base URL:** `https://clouddeploy.googleapis.com`

#### Tags

- Delivery Pipelines
- Releases
- Rollouts
- Targets

#### Properties

- [Documentation](https://cloud.google.com/deploy/docs/api/reference/rest)
- [OpenAPI](openapi/cloud-deploy-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloud-deploy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-deploy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://cloud.google.com/deploy/docs/api/reference/rest#authentication)
- [JSON Schema](json-schema/google-cloud-deploy-release-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [GitHub Organization](https://github.com/GoogleCloudPlatform)
- [Portal](https://cloud.google.com/deploy)
- [Getting Started](https://cloud.google.com/deploy/docs/quickstart)
- [Documentation](https://cloud.google.com/deploy/docs)
- [Authentication](https://cloud.google.com/deploy/docs/api/reference/rest#authentication)
- [Pricing](https://cloud.google.com/deploy/pricing)
- [Terms of Service](https://cloud.google.com/terms)
- [Privacy Policy](https://policies.google.com/privacy)
- [Console](https://console.cloud.google.com/deploy)
- [C L I](https://cloud.google.com/sdk/gcloud/reference/deploy)
- [Status Page](https://status.cloud.google.com)
- [Support](https://cloud.google.com/deploy/docs/support)
- [JSON-LD](json-ld/google-cloud-deploy-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
