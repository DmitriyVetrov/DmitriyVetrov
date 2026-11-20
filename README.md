<!-- Profile README for github.com/DmitriyVetrov (repo: DmitriyVetrov/DmitriyVetrov) -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,100:D97757&height=190&section=header&text=Dmytro%20Vietrov&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=.NET%20Backend%20%C2%B7%20Cloud%20%C2%B7%20AI%20Agents&descAlignY=58&descSize=18" width="100%"/>

<a href="https://github.com/DmitriyVetrov">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=D97757&center=true&vCenter=true&width=620&lines=C%23+%2F+.NET+backend+engineer+%E2%80%94+8%2B+years;Monolith+%E2%86%92+services%2C+events%2C+outbox%2C+gRPC;Kubernetes+%C2%B7+Terraform+%C2%B7+GitHub+Actions;Building+LLM+agents+with+Claude+%26+LangGraph" alt="Typing SVG"/>
</a>

<p>
  <a href="https://linkedin.com/in/dmvietrov"><img src="https://img.shields.io/badge/LinkedIn-dmvietrov-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Spain-C60B1E?style=flat-square"/>
  <img src="https://img.shields.io/badge/Open%20to-full--time%20%C2%B7%20contract%20%C2%B7%20remote-2EA44F?style=flat-square"/>
</p>

</div>

```text
$ whoami
  Software Engineer · 8+ years · C# / .NET · Azure · SQL · Kubernetes · AI agents

$ cat now.txt
  ▸ Splitting a legacy ASP.NET help-desk monolith into .NET 8 services (Cayzu)
  ▸ Building Resumiser — a spec-first resume builder with Claude Code
  ▸ Running a multi-agent job-search system on Claude Code every day

$ cat background.txt
  ▸ Cloud DevOps @ SAP — self-service K8s clusters, Helm, Terraform + Vault, Go tests
  ▸ .NET full-stack @ CRIF — credit reports, RabbitMQ async PDF generation
  ▸ MSc, Intelligent Decision-Making Systems — perceptrons before they were cool
```

## About

I build backend services and APIs on .NET, and I like taking over the hard parts: legacy
systems, stalled backlogs, and monoliths that need to become services without stopping
production. Since 2025 I also build LLM applications and agents — Claude API, Claude Code
multi-agent workflows, LangGraph pipelines with RAG, structured output and speech-to-text.

## 🚀 Selected projects

<table>
<tr>
<td width="50%" valign="top">

### 📝 [Resumiser](https://github.com/DmitriyVetrov/resume-builder)
Full-stack resume editor with live preview, templates and PDF / TXT export. Built spec-first:
Claude Code writes, Codex reviews; 16 phases, each with a plan, contract and test plan.
AI CV import via the Claude .NET SDK with structured output and a deterministic fallback.

![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

</td>
<td width="50%" valign="top">

### 🤖 [Job Hunt agents](https://github.com/DmitriyVetrov/claude-code-job-agents)
A team of Claude Code subagents that collects postings from ~16 job sites (incl. login-gated
ones via Playwright MCP), scores them against the CV and writes reports. Telegram bot runs it
headless from the phone; ~8,300 postings analysed. Least-privilege design, OpenTelemetry → Grafana.

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎧 [Call-Tracking](https://github.com/DmitriyVetrov/call-tracking)
Live transcription and translation of any call (Zoom, Teams, Meet, WhatsApp): system audio →
Deepgram STT → Claude Haiku translation, DeepL fallback. Offline mode with faster-whisper
builds a two-speaker dialogue after the call.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square)
![Claude](https://img.shields.io/badge/Claude_Haiku-D97757?style=flat-square&logo=anthropic&logoColor=white)

</td>
<td width="50%" valign="top">

### 🧠 [Agentic RAG](https://github.com/DmitriyVetrov/langgraph-agentic-rag) · [Survey bot](https://github.com/DmitriyVetrov/langgraph-telegram-survey-bot)
Corrective RAG in LangGraph: retrieval grading, hallucination and relevance checks, web-search
fallback, plus a recursive graph that splits compound questions. A Telegram survey bot on a
LangGraph StateGraph with intent classification and checkpointed state.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6446?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### ⚓ [Sailing Route Finder](https://github.com/DmitriyVetrov/sailing-route-finder)
Cheapest direct, cheapest overall and fastest sea route between two ports from a messy schedule
feed (Dijkstra over a time-expanded graph), with a waiting list that notifies when a route appears.
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![RSpec](https://img.shields.io/badge/RSpec-100%25_coverage-2EA44F?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
</table>

## 🛠 Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=cs,dotnet,python,go,ts,react,postgres,mysql,redis,rabbitmq,azure,docker,kubernetes,terraform,githubactions,linux&perline=8" />

</div>

| Area | Tools |
|---|---|
| **Backend** | C#, .NET / ASP.NET Core, EF Core, SignalR, gRPC, RabbitMQ / Wolverine, microservices, outbox |
| **Data** | SQL Server, PostgreSQL, MongoDB, Redis |
| **AI / LLM** | Claude API (.NET & Python SDK), Claude Code, MCP, LangGraph, LangChain, RAG, Chroma, Azure OpenAI |
| **Cloud & DevOps** | Azure, Kubernetes, Helm, Terraform, Vault, GitHub Actions, SaltStack |
| **Testing** | xUnit, Testcontainers, Playwright, pytest, RSpec |

## 🎓 Certifications

[![Claude Code 101](https://img.shields.io/badge/Anthropic_Academy-Claude_Code_101-D97757?style=flat-square&logo=anthropic&logoColor=white)](https://academy.claude.com/verify/f3db5c2e0ffa86646759aa067b4b80e6)
[![Claude Platform 101](https://img.shields.io/badge/Anthropic_Academy-Claude_Platform_101-D97757?style=flat-square&logo=anthropic&logoColor=white)](https://academy.claude.com/verify/fceb6056e0093498526be26fb0aa8bce)
[![Intro to MCP](https://img.shields.io/badge/Anthropic_Academy-Intro_to_MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)](https://academy.claude.com/verify/cb1efb355923fe9cc61642e46e4ca1bb)

<div align="center">

🗣 English B2 · Spanish A2 · Slovak · Ukrainian & Russian native

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:D97757,100:512BD4&height=100&section=footer" width="100%"/>

</div>
