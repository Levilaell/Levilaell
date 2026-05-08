# Levi Lael

> *AI operations engineering. I build systems that run in production without falling apart.*

Most “AI” projects today are demos. They work on stage and break the moment real traffic hits. My thesis: **the difference between a demo and a system is the boring part** — idempotency, exponential retries, cost telemetry, multi-provider orchestration.

That’s the part the market doesn’t want to build — which is why companies hire me to build it.

---

### What I have in production

**[CaixaHub](https://github.com/levilael)** — Financial SaaS for Brazilian SMBs  
Integrated with 100+ banks through Open Finance. Idempotent webhook handlers, boleto OCR with human review, and a self-learning categorization engine that improves with every correction. Ran with paying customers before being paused.

`Django` `Next.js 14` `PostgreSQL` `Celery+Redis` `Stripe` `Pluggy` `OpenAI` `Google Cloud Vision`

**[FastDevBuilds](https://github.com/levilael)** — B2B outbound automation platform  
End-to-end pipeline: lead discovery via Google Places → AI qualification (PageSpeed + visual analysis using Claude Haiku) → personalized WhatsApp outreach → website demo generation in under 90 seconds with Claude Opus.

`Next.js 16` `React 19` `Supabase` `Anthropic Claude` `Evolution API` `Puppeteer`

**[levilael.com.br](https://levilael.com.br)** — My personal website  
AI-generated operations diagnosis, cron-based nurturing email sequences, complete editorial system, and custom LGPD-compliant tracking.

`Next.js 16` `TypeScript` `Tailwind v4` `Anthropic` `Supabase` `Resend` `Notion`

---

### Daily stack

```txt
Backend         Python (Django REST), Node.js, TypeScript
Frontend        Next.js (App Router), React, Tailwind
AI/LLMs         Anthropic Claude (Opus, Sonnet, Haiku), OpenAI
Data            PostgreSQL, Supabase
Infra           Docker, Vercel, Railway, Celery+Redis
Automation      n8n, Make, custom Python pipelines
