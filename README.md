<h1 align="center">I run an Agent Company</h1>

<p align="center">
  <b>Nugrah Salam Harahap</b> · Batam, Indonesia<br>
  AI agents that do real business work — sales, lead generation, front desk, recruiting, inbox, operations.
</p>

---

Most AI projects stop at the demo. Mine don't — I run my company with agents.

I run **Core Solution** with a team of AI agents — my **Agent Company**: a manager plus divisions for product, marketing, sales, operations, finance, content, and research. They work the way a good team does: task contracts, evidence over claims, and human approval before anything public or paid. Nothing ships without verification.

<p align="center">
  <img width="720" src="https://raw.githubusercontent.com/envexx/ai-sales-agent/main/docs/screenshots/overview.png" alt="ai-sales-agent — sales pipeline dashboard">
</p>

## The fleet

| System | What it does | Built with |
|---|---|---|
| **[ai-sales-agent](https://github.com/envexx/ai-sales-agent)** | WhatsApp sales agent on a 14-node LangGraph pipeline: brand-safe RAG, lead scoring, scheduling via MCP, human-like replies, real-time dashboard. | LangGraph · DeepSeek · pgvector · Next.js |
| **[SignalDesk](https://github.com/envexx/signaldesk)** · [demo](https://signaldesk-steel.vercel.app) | Autonomous B2B lead enrichment: evidence-backed research, explainable ICP scoring, drafts that stop for human approval. | Next.js · Inngest · Postgres |
| **[WellNest](https://github.com/envexx/ai-clinic)** · [demo](https://ai-clinic-sand.vercel.app) | AI clinic front desk: admin Q&A, booking flows, staff handoff — with a full staff dashboard. | Next.js · Prisma · pgvector · Gemini |
| **[Switchboard](https://github.com/envexx/ai-business-inbox)** · [demo](https://business-inbox-ten.vercel.app) | AI business inbox: classify → policy → draft → act or hold. Risk tiers, approvals, full audit. | Next.js · Prisma · OpenAI |
| **[Firstpass](https://github.com/envexx/ai-lead-automation)** · [demo](https://lead-automation-alpha.vercel.app) | Lead qualify → decide → act → verify → audit. Scoring lives in code; every run replayable. | Next.js · Prisma · OpenAI |
| **Talenta** · [demo](https://ai-recruitmen.vercel.app) *(private repo)* | AI recruitment dashboard: flexible form builder, company knowledge, AI-assisted candidate scoring. | Next.js · Prisma |

## How it operates

- **Human gates by default** — sends, outreach, and anything public wait for approval; ad operations start paused.
- **Evidence over claims** — verification passes, audit trails, measured results.
- **Graceful degradation** — every AI path has a deterministic fallback; nothing breaks when a provider fails.
- **Production habits** — TypeScript strict, tests + smoke + eval scripts, architecture documented in each README.

## Stack

`TypeScript` · `Node.js` · `Python` · `Next.js` · `LangGraph` · `OpenAI / Gemini / DeepSeek` · `PostgreSQL + pgvector` · `Prisma` · `MCP` · `Docker` · `Ubuntu VPS`

<sub>Also built: agent-payment rails ([spend402](https://github.com/envexx/spend402) · [commit](https://github.com/envexx/commit)) · verifiable settlement ([Credo](https://github.com/envexx/credo-settlement-rwa)) · production n8n AI workflows ([n8n-automation-lab](https://github.com/envexx/n8n-automation-lab))</sub>

---

<p align="center">
  📫 <b>coresolution3@gmail.com</b> · <a href="https://becoder.xyz">becoder.xyz</a> · <a href="https://www.linkedin.com/in/nugrah-salam-16a408257">LinkedIn</a>
</p>
