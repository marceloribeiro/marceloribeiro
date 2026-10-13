<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,100:0EA5E9&height=190&section=header&text=Marcelo%20Sousa%20Ribeiro&fontColor=ffffff&fontSize=40&fontAlignY=34&desc=AI%20Engineer%20%C2%B7%20Forward%20Deployed%20Engineer%20%C2%B7%2015%2B%20years%20full-stack&descSize=17&descAlignY=54" width="100%" alt="Marcelo Sousa Ribeiro — AI Engineer, Forward Deployed Engineer, 15+ years full-stack" />

<p align="center">
  <a href="https://www.themarceloribeiro.com"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=3200&pause=900&color=6366F1&center=true&vCenter=true&width=700&lines=I+build+agentic+systems+%E2%80%94+and+the+infra+that+keeps+them+reliable.;LLM+orchestration+%C2%B7+tool-calling+%C2%B7+RAG+%C2%B7+MCP+%C2%B7+evals;I+ship+LLM+agents+into+real+business+stacks.;Scaled+platforms+to+millions+of+users." alt="I build agentic systems and the infrastructure that keeps them reliable" /></a>
</p>

<p align="center">
  <a href="https://www.themarceloribeiro.com"><img src="https://img.shields.io/badge/Portfolio-themarceloribeiro.com-6366F1?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/themarceloribeiro/"><img src="https://img.shields.io/badge/LinkedIn-themarceloribeiro-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.youtube.com/@vibeworkin"><img src="https://img.shields.io/badge/YouTube-vibeworkin-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="mailto:themarceloribeiro@gmail.com"><img src="https://img.shields.io/badge/Email-themarceloribeiro-0EA5E9?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I build **agentic systems** and the infrastructure around them — LLM orchestration and
tool-calling, retrieval over vector databases, evals, and the production plumbing that
keeps autonomous agents reliable and within budget. As a forward deployed engineer I ship
that into other people's stacks: LLM agents into CRMs, inboxes and third-party MCP servers;
mobile keys into Wyndham and IHG lock infrastructure.

That AI work sits on a deep full-stack and systems foundation: Python, TypeScript, Ruby
and Go across FastAPI, Next.js and Rails on AWS. I've sharded a monolithic database across
20+ shards at Deliveroo, owned payments for a business past 2M subscribers at BarkBox, and
cut unified search from 20+ seconds to ~1 second over hundreds of millions of records.

**Frontier AI engineering, with the systems judgment to actually run it in production.**

---

## 🪨 Evalstone — the evals layer for any LLM product

<p>
  <a href="https://pypi.org/project/evalstone/"> <img src="https://img.shields.io/pypi/v/evalstone?style=flat-square&label=pypi&color=6366F1" alt="PyPI" /> </a>
  <a href="https://github.com/marceloribeiro/evalstone/actions/workflows/lib.yml"> <img src="https://img.shields.io/github/actions/workflow/status/marceloribeiro/evalstone/lib.yml?style=flat-square&label=lib%20ci&color=6366F1" alt="Library CI" /> </a>
  <a href="https://github.com/marceloribeiro/evalstone/actions/workflows/site.yml"> <img src="https://img.shields.io/github/actions/workflow/status/marceloribeiro/evalstone/site.yml?style=flat-square&label=site%20ci&color=6366F1" alt="Site CI" /> </a>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/MCP-D97757?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/GitHub%20Action-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Action" />
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square" alt="MIT" />
</p>

A plug-and-play evals layer you add to an existing LLM project without a rewrite.
`pip install evalstone`, write `evalstone.yaml`, and get a **pass/fail quality gate in CI**:
deterministic checks, calibrated LLM-as-judge, RAG and agent-trajectory checks, pairwise
comparison and safety checks, all as plain Python.

> **First it teaches you what evals are. Then it runs them for you, in CI and in production.**
> A learning center ("Evals 101"), a self-hostable center for versioned golden sets, human
> labeling and judge calibration, production monitors, and an MCP server so Claude Code or
> Cursor can run your suites. The library computes; the center stores.

Python library + CLI · pytest plugin · GitHub Action · FastAPI center · Next.js app · MCP server ·
**[evalstone.com](https://evalstone.com)** · **[repo →](https://github.com/marceloribeiro/evalstone)**

*Building in the open — the library, CLI, pytest plugin, MCP server and GitHub Action are on
[PyPI](https://pypi.org/project/evalstone/) (`pip install evalstone`, `marceloribeiro/evalstone/action@action-v0`);
the site and [Evals 101](https://evalstone.com/docs/learn) are live; the center API is next.*

---

## 🚦 Turnstile — the session layer for agent traffic

<p>
  <a href="https://github.com/marceloribeiro/turnstile"> <img src="https://img.shields.io/github/v/release/marceloribeiro/turnstile?style=flat-square&color=6366F1&label=release" alt="Release" /> </a>
  <a href="https://github.com/marceloribeiro/turnstile"> <img src="https://img.shields.io/github/stars/marceloribeiro/turnstile?style=flat-square&color=6366F1" alt="Stars" /> </a>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square" alt="MIT" />
</p>

A transparent streaming proxy between your app and any LLM provider. It meters every agent
session in real time and **trips a circuit breaker the instant one session goes rogue** — a
runaway loop or a blown budget — without taking down the rest of your app.

> Swap one base URL. No SDK, no code changes. Microsecond-scale added latency, fail-open by
> default, and raw prompts and API keys are never persisted.

Go data plane · FastAPI control plane · Next.js dashboard · **direct adapters for OpenAI,
Anthropic and Gemini**, plus OpenRouter · **[turnstileguard.com](https://turnstileguard.com)** ·
**[repo →](https://github.com/marceloribeiro/turnstile)**

*Turnstile observes traffic; Evalstone judges quality. Together they are the reliability
layer for LLM products.*

---

## 🧰 Stack

**AI / LLM**

<p>
  <img src="https://img.shields.io/badge/Agentic_Systems-6366F1?style=for-the-badge" alt="Agentic Systems" />
  <img src="https://img.shields.io/badge/Evals_%2F_LLM--as--judge-6366F1?style=for-the-badge" alt="Evals and LLM-as-judge" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" alt="LangGraph" />
  <img src="https://img.shields.io/badge/MCP-D97757?style=for-the-badge" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/RAG_%2F_Vector_DBs-0EA5E9?style=for-the-badge" alt="RAG and vector databases" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/OpenRouter-6467F2?style=for-the-badge" alt="OpenRouter" />
</p>

**Languages & frameworks**

<img src="https://skillicons.dev/icons?i=python,typescript,javascript,go,ruby,fastapi,nextjs,react,rails,vue&perline=10" alt="Python, TypeScript, JavaScript, Go, Ruby, FastAPI, Next.js, React, Rails, Vue" />

**Data & infrastructure**

<img src="https://skillicons.dev/icons?i=postgres,elasticsearch,redis,aws,docker,kubernetes,nginx,git,githubactions&perline=9" alt="PostgreSQL, Elasticsearch, Redis, AWS, Docker, Kubernetes, nginx, Git, GitHub Actions" />

---

## 🎓 Education

**Y Combinator** — Startup School, 2019<br />
**University of São Paulo** — BSc Physics with Scientific Software Programming

<br>

<p align="center">
  <sub>Open to FDE and AI engineering roles in San Francisco and remote · Authorized to work in the US.</sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0EA5E9,100:6366F1&height=110&section=footer" width="100%" alt="" />
