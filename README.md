# Andrey Novikov

I build AI systems and business software that people use in their daily work: agents and MCP
tools, retrieval with citations, ERP/CRM and the integrations around them.

I work spec-first with coding agents (Claude Code, Codex, Cursor): I write the spec and the
acceptance checks, the agents write most of the code, and I review, test and ship it.

**Stack:** Python (FastAPI) · TypeScript (Next.js) · PostgreSQL / Supabase · MCP · REST APIs ·
Docker · Git

## Projects

- **agent-toolkit** (public, below): the tooling I use to run several coding agents — task
  hand-off to Codex / Cursor / Gemini / Claude under one contract, and full-text search over past
  agent sessions.
- **Internal ERP/CRM for an import-export company (Master Bearing), 2022–2026.** Quotation
  calculations, permissions, approval workflows; integrations with Bitrix24, 1C and DataLens
  (Next.js, FastAPI, PostgreSQL/Supabase). Added an AI estimate of preliminary logistics cost:
  the median time to a logistics price went from about three days to a few minutes. Feedback loop:
  user reports in Linear → Codex proposes a fix → human review → release.
- **Knowledge assistant over Confluence (PIX Robotics), 2026.** Confluence ingestion, keyword +
  vector retrieval on PostgreSQL, MCP tools, answers with citations; evaluated on held-out
  questions with model comparisons and documented answer defects.
- **Sales domain of a company ERP (Manna Coffee), 2026–present.** CRM, sales workflows and a
  multichannel inbox linking conversations to contact and deal records — built because
  off-the-shelf CRMs could not be configured for the sales process.
- **TeleNews** (personal): Telegram channel monitoring with scheduled AI digests (Python, ARQ,
  Redis, Telethon, Mistral).

## Background

Before moving into engineering I ran businesses and sales teams: founded ELK Group (services and
e-commerce, four locations, 40+ staff), then led sales at B2B companies with ARR over $100M. That is why I start from
how a team actually works before choosing AI, ordinary software or a process change.

## Public code

**[agent-toolkit](https://github.com/AgasiArgent/agent-toolkit)** — delegate skill and
session-search tool, with offline tests.

Employer code is private; I can walk through more on request where the employer permits it.
