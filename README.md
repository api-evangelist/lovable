# Lovable (lovable)

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

Lovable is an AI app builder that generates full-stack web applications from natural-language prompts, with live preview, GitHub sync, and Supabase / Firebase integration. Lovable's developer-facing surface is in early release: the "Build with URL" API generates apps from a shareable URL, and the Lovable MCP Server lets AI clients (Claude Desktop, Cursor) manage Lovable projects via Model Context Protocol.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/lovable/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=lovable-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, No-Code, App Builder, Web Development, Generative, MCP

## APIs
- **Build with URL API** — Generate a Lovable app from a shareable URL or prompt. [Docs](https://docs.lovable.dev/integrations/lovable-api) · [Blog](https://lovable.dev/blog/introducing-lovable-api-build-with-url)
- **Lovable MCP Server** (Research Preview) — `https://mcp.lovable.dev`. AI-client-driven project management via Model Context Protocol.

## Plans, Rate Limits, FinOps
- [Plans](plans/lovable-plans-pricing.yml) — Subscription tiers (Free / Pro / Teams / Enterprise) with monthly credit allowances.
- [RateLimits](rate-limits/lovable-rate-limits.yml)
- [FinOps](finops/lovable-finops.yml)

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://lovable.dev/)
- [Documentation](https://docs.lovable.dev/)
- [Pricing](https://lovable.dev/pricing)

## Notes
- Lovable is primarily an AI app-builder product (web UI + chat). Programmatic entry points are limited to "Build with URL" and the MCP Server in research preview. Public REST inference endpoints are not advertised.
- No public OpenAPI spec discovered.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
