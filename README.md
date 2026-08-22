# Browserbase (browserbase)

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

Browserbase is a browser-agent platform that provides managed, headless Chromium browsers and supporting web primitives for AI agents and automation workloads. Customers use a single API key to spin up sessions, fetch and search the web, persist context, route LLM calls, and observe agent behavior across replays and logs. The company maintains the popular open-source Stagehand SDK, a Director UI for agent design, a Browse CLI, and an MCP server. Target customers are AI startups, agent developers, RPA teams, and enterprises running production web automation, with SOC 2 Type II and HIPAA options. Billing is usage-based with a free tier and paid plans on the pricing page.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/browserbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/browserbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Headless Browser
- Browser Infrastructure
- Web Automation
- AI Agents
- Web Scraping
- Stagehand
- Playwright
- Puppeteer
- Web Search
- Web Fetch
- Model Gateway
- MCP
- Session Recording
- Agent Identity

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Browserbase API

The Browserbase API is a REST interface for managing cloud-hosted browser sessions, projects, contexts, extensions, downloads, and complementary Search, Fetch, and Functions services. Agents and automation scripts connect via the SDKs or Playwright/Puppeteer compatible endpoints to navigate the web, capture content, and persist authenticated state.

- **Human URL:** [https://docs.browserbase.com](https://docs.browserbase.com)
- **Base URL:** `https://api.browserbase.com`

#### Tags

- Sessions
- Projects
- Contexts
- Extensions
- Downloads
- Search
- Fetch
- Functions
- Stagehand
- MCP

#### Properties

- [Documentation](https://docs.browserbase.com)
- [API Reference](https://docs.browserbase.com/reference/introduction)
- [Getting Started](https://docs.browserbase.com/quickstart)
- [Sign Up](https://www.browserbase.com/sign-up)
- [SDK](https://github.com/browserbase/sdk-node)
- [SDK](https://github.com/browserbase/sdk-python)
- [SDK](https://github.com/browserbase/stagehand)
- [SDK](https://github.com/browserbase/stagehand-python)
- [C L I](https://github.com/browserbase/browse-cli)
- [GitHub Repository](https://github.com/browserbase/mcp-server-browserbase)
- [OpenAPI](openapi/browserbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/browserbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/browserbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/browserbase-session-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Plans](plans/browserbase-plans-pricing.yml)
- [Rate Limits](rate-limits/browserbase-rate-limits.yml)
- [Fin Ops](finops/browserbase-finops.yml)
- [Capabilities](capabilities/sessions.yaml)
- [Vocabulary](vocabulary/browserbase-vocabulary.yml)
- [Rules](rules/browserbase-rules.yml)
- [Changelog](https://www.browserbase.com/changelog)
- [Status Page](https://status.browserbase.com)
- [Pricing](https://www.browserbase.com/pricing)
- [Enterprise](https://www.browserbase.com/enterprise)

## Common Properties

- [Website](https://www.browserbase.com)
- [Documentation](https://docs.browserbase.com)
- [API Reference](https://docs.browserbase.com/reference/introduction)
- [Blog](https://www.browserbase.com/blog)
- [GitHub Organization](https://github.com/browserbase)
- [Pricing](https://www.browserbase.com/pricing)
- [Enterprise](https://www.browserbase.com/enterprise)
- [Changelog](https://www.browserbase.com/changelog)
- [Status Page](https://status.browserbase.com)
- [Sign Up](https://www.browserbase.com/sign-up)
- [Careers](https://www.browserbase.com/careers)
- [Terms of Service](https://www.browserbase.com/terms-of-service)
- [Privacy Policy](https://www.browserbase.com/privacy-policy)
- [L L Ms Txt](https://docs.browserbase.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
