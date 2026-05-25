# Browserbase (browserbase)

Browserbase is a browser-agent platform that provides managed, headless Chromium browsers and supporting web primitives for AI agents and automation workloads. Customers use a single API key to spin up sessions, fetch and search the web, persist context, route LLM calls, and observe agent behavior across replays and logs.

**URL:** [Browserbase apis.yml](https://raw.githubusercontent.com/api-evangelist/browserbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

AI Agents, Agent Identity, Browser Infrastructure, Headless Browser, MCP, Model Gateway, Playwright, Puppeteer, Session Recording, Stagehand, Web Automation, Web Fetch, Web Scraping, Web Search

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Browserbase API

The Browserbase API is a REST interface for managing cloud-hosted browser sessions, projects, contexts, extensions, downloads, and complementary Search, Fetch, and Functions services. Agents and automation scripts connect via the SDKs or Playwright/Puppeteer compatible endpoints to navigate the web, capture content, and persist authenticated state.

- **Human URL:** https://docs.browserbase.com
- **Base URL:** https://api.browserbase.com

#### Tags

Contexts, Downloads, Extensions, Fetch, Functions, MCP, Projects, Search, Sessions, Stagehand

#### Properties

- [Documentation](https://docs.browserbase.com)
- [API Reference](https://docs.browserbase.com/reference/introduction)
- [Getting Started](https://docs.browserbase.com/quickstart)
- [Sign Up](https://www.browserbase.com/sign-up)
- [Node SDK](https://github.com/browserbase/sdk-node)
- [Python SDK](https://github.com/browserbase/sdk-python)
- [Stagehand SDK (Node)](https://github.com/browserbase/stagehand)
- [Stagehand SDK (Python)](https://github.com/browserbase/stagehand-python)
- [Browse CLI](https://github.com/browserbase/browse-cli)
- [MCP Server](https://github.com/browserbase/mcp-server-browserbase)
- [OpenAPI](openapi/browserbase-openapi.yml)
- [JSON Schema](json-schema/browserbase-session-schema.json)
- [Plans](plans/browserbase-plans-pricing.yml)
- [Rate Limits](rate-limits/browserbase-rate-limits.yml)
- [FinOps](finops/browserbase-finops.yml)
- [Naftiko Capabilities](capabilities/sessions.yaml)
- [Vocabulary](vocabulary/browserbase-vocabulary.yml)
- [Spectral Rules](rules/browserbase-rules.yml)
- [Change Log](https://www.browserbase.com/changelog)
- [Status Page](https://status.browserbase.com)
- [Pricing](https://www.browserbase.com/pricing)
- [Enterprise](https://www.browserbase.com/enterprise)

#### Features

- **Cloud Browser Sessions** — Spin up Chromium sessions on demand with persistent context, recording, and multi-region routing.
- **Stagehand SDK** — AI-first browser automation framework optimized for agents to plan, observe, and act on pages.
- **Web Search and Fetch** — Token-efficient search results and lightweight URL-to-structured-data fetch endpoints.
- **Agent Identity** — Human-like identity layer with bot-protection integration for sites that gate automated traffic.
- **Model Gateway** — Unified API surface to route requests across multiple LLM providers.
- **Observability and Replays** — rrweb session recording, logs, and prompt tracing for debugging agent runs.
- **Contexts and Extensions** — Reusable browser environments, cookies, profiles, and custom Chrome extensions.
- **Proxies and Static IPs** — Configurable residential/datacenter proxies and IP allowlisting for enterprise use.
- **1Password Integration** — Secure credential injection for sites that require human-style login.
- **MCP Server** — Model Context Protocol server so agents in Claude, Cursor, and other clients can drive Browserbase.

#### Use Cases

- **AI Agent Web Browsing** — Give agents a real browser to research, fill forms, click through flows, and capture results.
- **Web Scraping at Scale** — Run large fleets of stealthy, parallel browsers for data extraction.
- **End-to-End Testing** — Drive Playwright/Puppeteer suites against production sites in managed browsers.
- **RPA and Workflow Automation** — Automate human-style tasks across SaaS apps without maintaining your own browser fleet.
- **Visual QA and Monitoring** — Capture screenshots and replays to detect UI regressions and broken flows.

#### Integrations

Playwright, Puppeteer, Stagehand, [Anthropic](https://github.com/api-evangelist/anthropic), Claude Computer Use, OpenAI, LangChain, LlamaIndex, CrewAI, Vercel AI SDK, n8n, AgentKit, Temporal, Hermes Agent, Prime Intellect, 1Password, MCP

#### Authentication

- **API Key** — A single API key passed via the `X-BB-API-Key` header authenticates all REST and SDK calls.

## Artifacts

### OpenAPI

- [openapi/browserbase-openapi.yml](openapi/browserbase-openapi.yml) — Sessions, Contexts, Projects, Extensions

### Naftiko Capabilities

- [capabilities/sessions.yaml](capabilities/sessions.yaml) — Session lifecycle, logs, recordings, downloads, debug URLs
- [capabilities/contexts.yaml](capabilities/contexts.yaml) — Reusable encrypted browser profiles
- [capabilities/projects.yaml](capabilities/projects.yaml) — Project metadata and usage metering
- [capabilities/extensions.yaml](capabilities/extensions.yaml) — Chrome extension upload and management

### JSON Schema

- [json-schema/browserbase-session-schema.json](json-schema/browserbase-session-schema.json)
- [json-schema/browserbase-context-schema.json](json-schema/browserbase-context-schema.json)
- [json-schema/browserbase-project-schema.json](json-schema/browserbase-project-schema.json)

### JSON Structure

- [json-structure/browserbase-session-structure.json](json-structure/browserbase-session-structure.json)
- [json-structure/browserbase-context-structure.json](json-structure/browserbase-context-structure.json)
- [json-structure/browserbase-project-structure.json](json-structure/browserbase-project-structure.json)

### JSON-LD

- [json-ld/browserbase-context.jsonld](json-ld/browserbase-context.jsonld)

### Examples

- [examples/browserbase-create-session-example.json](examples/browserbase-create-session-example.json)
- [examples/browserbase-get-session-example.json](examples/browserbase-get-session-example.json)
- [examples/browserbase-get-session-debug-example.json](examples/browserbase-get-session-debug-example.json)
- [examples/browserbase-create-context-example.json](examples/browserbase-create-context-example.json)
- [examples/browserbase-list-projects-example.json](examples/browserbase-list-projects-example.json)

### Vocabulary

- [vocabulary/browserbase-vocabulary.yml](vocabulary/browserbase-vocabulary.yml)

### Spectral Rules

- [rules/browserbase-rules.yml](rules/browserbase-rules.yml)

### Commercial

- [plans/browserbase-plans-pricing.yml](plans/browserbase-plans-pricing.yml) — API Commons Plans 0.1
- [rate-limits/browserbase-rate-limits.yml](rate-limits/browserbase-rate-limits.yml) — API Commons Rate Limits 0.1
- [finops/browserbase-finops.yml](finops/browserbase-finops.yml) — FinOps / FOCUS alignment

## Common

- [Website](https://www.browserbase.com)
- [Documentation](https://docs.browserbase.com)
- [API Reference](https://docs.browserbase.com/reference/introduction)
- [Blog](https://www.browserbase.com/blog)
- [GitHub Organization](https://github.com/browserbase)
- [Pricing](https://www.browserbase.com/pricing)
- [Enterprise](https://www.browserbase.com/enterprise)
- [Change Log](https://www.browserbase.com/changelog)
- [Status Page](https://status.browserbase.com)
- [Sign Up](https://www.browserbase.com/sign-up)
- [Careers](https://www.browserbase.com/careers)
- [Terms of Service](https://www.browserbase.com/terms-of-service)
- [Privacy Policy](https://www.browserbase.com/privacy-policy)
- [llms.txt](https://docs.browserbase.com/llms.txt)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
