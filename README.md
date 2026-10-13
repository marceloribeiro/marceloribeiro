<img src="banner.svg" width="100%" alt="Marcelo Sousa Ribeiro — AI Engineer / Forward Deployed Engineer · 15+ years full-stack · San Francisco" />

I take ambiguous business problems and ship them as production systems inside
someone else's stack: LLM agents into CRMs, inboxes and third-party MCP servers;
mobile keys into Wyndham and IHG lock infrastructure; payments and sharding for
platforms past 2M subscribers.

[Website](https://www.themarceloribeiro.com) · [LinkedIn](https://www.linkedin.com/in/themarceloribeiro/) · [YouTube: vibeworkin](https://www.youtube.com/@vibeworkin) · [Email](mailto:themarceloribeiro@gmail.com)

## Now

- **[Evalstone](https://github.com/marceloribeiro/evalstone)** — the plug-and-play evals
  layer for LLM products. `pip install evalstone`, write `evalstone.yaml`, get a
  pass/fail gate in CI. Deterministic checks, calibrated LLM judges, RAG and agent
  trajectory checks, an MCP server so Claude Code can run your suites, and a
  self-hostable center for golden sets, human labeling and production monitors.
  The docs teach evals first, then the API. Built in the open at
  [evalstone.com](https://evalstone.com).
- **[Turnstile](https://github.com/marceloribeiro/turnstile)** — session-layer circuit
  breaker for LLM and agent traffic. A transparent streaming proxy (Go data plane,
  FastAPI control plane, Next.js dashboard) that meters every session and kills the
  one that goes rogue, without taking down the app. Direct adapters for OpenAI,
  Anthropic and Gemini, plus OpenRouter. MIT.
- **FlooxAI** — my agentic platform: agents deployed into real business tools, with
  the budget, prompt-economy and provider-routing plumbing that keeps them reliable.

Turnstile observes traffic; Evalstone judges quality. Together they are the
reliability layer I wanted on every LLM product I shipped.

## Deployed into customer stacks

- Apple / Google Wallet mobile keys into Wyndham and IHG's existing lock
  infrastructure (Vostio, Dormakaba).
- LLM agents wired to customers' CRMs, inboxes and MCP servers at FlooxAI.
- Multi-service FastAPI + Next.js products scaffolded from a written spec, deployed
  behind nginx and systemd, with Playwright end-to-end tests from day one.

## Scale work

- Sharded a monolithic database across 20+ shards at Deliveroo.
- Owned payments for a business past 2M subscribers at BarkBox.
- Cut unified search from 20+ seconds to ~1 second over hundreds of millions of records.
- Ran a 15-person client-services firm; still hands-on as architecture and delivery lead.

## How I work

A ticket is done when I watched the effect happen, not when the tests went green.
I mock at the network seam, never the module under test. Porting a system means
behavioral equivalence, not matching JSON schemas. Every agent turn gets measured
for what it actually sends the model.

## Stack

Python · TypeScript · Go · Ruby — FastAPI · Next.js · React Native · Rails —
PostgreSQL · pgvector · Redis · Elasticsearch · Celery — OpenAI · Anthropic · Gemini ·
OpenRouter · LangGraph · MCP — AWS · nginx · systemd · GitHub Actions · Playwright

<p align="center"><sub>Open to FDE and AI engineering roles in San Francisco and remote. Authorized to work in the US.</sub></p>
