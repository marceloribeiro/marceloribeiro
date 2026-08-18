<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,100:0EA5E9&height=190&section=header&text=Marcelo%20Sousa%20Ribeiro&fontColor=ffffff&fontSize=40&fontAlignY=34&desc=AI%2FLLM%20Engineer%20%C2%B7%20Senior%20Full-Stack%20%C2%B7%2015%2B%20years&descSize=17&descAlignY=54" width="100%" alt="Marcelo Sousa Ribeiro — AI/LLM Engineer, Senior Full-Stack, 15+ years" />

<p align="center">
  <a href="https://www.themarceloribeiro.com"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=3200&pause=900&color=6366F1&center=true&vCenter=true&width=700&lines=I+build+agentic+systems+%E2%80%94+and+the+infra+that+keeps+them+reliable.;LLM+orchestration+%C2%B7+tool-calling+%C2%B7+RAG+%C2%B7+MCP;Scaled+platforms+to+millions+of+users." alt="I build agentic systems and the infrastructure that keeps them reliable" /></a>
</p>

<p align="center">
  <a href="https://www.themarceloribeiro.com"><img src="https://img.shields.io/badge/Portfolio-themarceloribeiro.com-6366F1?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.youtube.com/@vibeworkin"><img src="https://img.shields.io/badge/YouTube-vibeworkin-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="mailto:themarceloribeiro@gmail.com"><img src="https://img.shields.io/badge/Email-themarceloribeiro-0EA5E9?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I build **agentic systems** and the infrastructure around them — LLM orchestration and
tool-calling, retrieval over vector databases, and the production plumbing that keeps
autonomous agents reliable and within budget.

That AI work sits on a deep full-stack and systems foundation: Python, TypeScript, Ruby
and Go across FastAPI, Next.js and Rails on AWS. I've sharded a monolithic database across
20+ shards at Deliveroo, owned payments for a business past 2M subscribers at BarkBox, and
cut unified search from 20+ seconds to ~1 second over hundreds of millions of records.

**Frontier AI engineering, with the systems judgment to actually run it in production.**

---

## 🚦 Turnstile — the session layer for agent traffic

<a href="https://github.com/marceloribeiro/turnstile">
  <img src="https://img.shields.io/github/v/release/marceloribeiro/turnstile?style=flat-square&color=6366F1&label=release" alt="Release" />
</a>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square" alt="MIT" />

A transparent streaming proxy between your app and any LLM provider. It meters every agent
session in real time and **trips a circuit breaker the instant one session goes rogue** — a
runaway loop or a blown budget — without taking down the rest of your app.

> Swap one base URL. No SDK, no code changes. Microsecond-scale added latency, fail-open by
> default, and raw prompts and API keys are never persisted.

Go data plane · FastAPI control plane · Next.js dashboard · adapters for OpenAI, Anthropic,
Gemini and OpenRouter · **[turnstileguard.com](https://turnstileguard.com)** ·
**[repo →](https://github.com/marceloribeiro/turnstile)**

---

## 🧰 Stack

**AI / LLM**

<img src="https://img.shields.io/badge/Agentic_Systems-6366F1?style=for-the-badge" alt="Agentic Systems" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/MCP-D97757?style=for-the-badge" alt="Model Context Protocol" />
<img src="https://img.shields.io/badge/RAG_%2F_Vector_DBs-0EA5E9?style=for-the-badge" alt="RAG and vector databases" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
<img src="https://img.shields.io/badge/OpenRouter-6467F2?style=for-the-badge" alt="OpenRouter" />

**Languages & frameworks**

<img src="https://skillicons.dev/icons?i=python,typescript,javascript,go,ruby,fastapi,nextjs,react,rails,vue&perline=10" alt="Python, TypeScript, JavaScript, Go, Ruby, FastAPI, Next.js, React, Rails, Vue" />

**Data & infrastructure**

<img src="https://skillicons.dev/icons?i=postgres,elasticsearch,redis,aws,docker,kubernetes,git,githubactions&perline=8" alt="PostgreSQL, Elasticsearch, Redis, AWS, Docker, Kubernetes, Git, GitHub Actions" />

---

## 🧭 Experience

| Where | What |
|---|---|
| **FlooxAI** · Founding Engineer<br><sub>2025 → now</sub> | Agentic platform connecting LLMs to the tools people already use (HubSpot, Salesforce, Gmail) and to third-party MCP servers. Built the agentic core on LangChain + Composio, credit-based multi-step workflows, and multi-model routing via OpenRouter with vector retrieval. |
| **Canary Technologies** · Senior Engineer<br><sub>2024 → 2025</sub> | Hotel guest journey across frontend and backend, deployed to **tens of thousands of hotels**. Shipped Apple/Google Wallet mobile keys (PassKit, Vostio, Dormakaba) and the tipping + feedback service. |
| **TPXImpact** · Lead Full-Stack<br><sub>2022 → 2024</sub> | Led a team of 3 building tools for UK local government to manage council homes and tenants, to GOV.UK accessibility standards. |
| **Deliveroo** · Senior Full-Stack<br><sub>2020 → 2022</sub> | Drove the data-sharding effort: migrated a monolithic database to UUID keys and split it across **20+ shards** spanning UK, EU and Emirates markets. |
| **BarkBox** · Senior Engineer<br><sub>2017 → 2020</sub> | Owned payments end to end — recurring and gift subscriptions, multiple recurrence models — for a business that grew past **2M subscribers**. |
| **CrystalCommerce** · Lead Engineer<br><sub>2015 → 2017</sub> | Led a team of 6 on a marketplace with 1,200+ stores and **5M monthly actives**. Built an Elasticsearch cluster with geocode search over hundreds of millions of records, cutting unified search from **20+ seconds to ~1 second**. |

---

## 🎓

**Y Combinator** — Startup School, 2019
**University of São Paulo** — BSc Physics with Scientific Software Programming

<br>

<p align="center">
  <sub>Open to opportunities in San Francisco and remote.</sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0EA5E9,100:6366F1&height=110&section=footer" width="100%" alt="" />
