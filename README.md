# Taha Rafiq

**Full-Stack AI Engineer** · Dubai, UAE · [taharafiq.com](https://taharafiq.com) · [Upwork](https://www.upwork.com/freelancers/taharafiq101)

I build whole products, not demos. UI, API, database, auth, billing, the AI layer, and the servers it all runs on, designed and deployed by one person, end to end.

10+ years, 40+ full-stack systems shipped. Roughly half started as my own products before becoming client work.

---

### Systems in production

**Multi-tenant AI chatbot SaaS · 500 businesses**
RAG chatbot answering across Web, WhatsApp, Instagram, Messenger and email into one unified inbox, with live human takeover, lead scoring, Stripe usage billing and a master-admin console.
`Next.js 15` `tRPC` `Postgres + pgvector` `Redis/BullMQ` `Cohere rerank` `Stripe`

**Five-in-one platform for a GCC certification company · 30,000+ records migrated**
Certifications, exams, sales, finance and outbound in one system. Migrated 30,000+ legacy records off a Laravel/MySQL stack, closed the enumeration vulnerability that was letting bots scrape the database, and took successful external attacks to zero.
`Next.js` `FastAPI` `PostgreSQL` `Redis` `Docker` `Coolify`

**AI-native operating system for a 20-person agency · ~$1,500/month of SaaS retired**
Replaced Slack, Zoom, cloud storage, team monitoring, client portals and ClickUp. One typed core (Zod → OpenAPI → generated client) serving a Next.js web app, an Expo mobile app and an MCP server.
`Next.js` `TypeScript` `Zod` `OpenAPI` `Expo` `MCP`

**14-module ERP with double-entry accounting · ~$300k of inventory a month**
Every sale, purchase and POS transaction auto-posts balanced journal pairs against a seeded chart of accounts. AI reorder planning avoided roughly $20k of excess stock. Native Android app for field salesmen.
`Next.js` `PostgreSQL` `Prisma` `Android` `Docker`

Also shipped: a multi-tenant Meta Ads platform where an AI analyst diagnoses why each ad lost money and generates the replacement · a zero-touch recruitment pipeline where an AI agent joins the video call and runs the interview · a real-time bilingual voice tutor at ~2s first-audio latency · a native macOS dictation app running fully on-device in Swift.

---

### What I build

- **AI-native SaaS** — multi-tenant from day one, with auth, RBAC, Stripe billing, usage metering and an admin back office
- **RAG and knowledge systems** — chunking, embeddings, pgvector/Pinecone/Qdrant, reranking, citations, injection protection
- **AI agents that take real actions** — tool calling, MCP servers, multi-agent orchestration, structured outputs, guardrails
- **ERPs, CRMs and internal tools** — double-entry accounting, inventory, pipelines, approval workflows, audit logs
- **Voice AI** — inbound receptionists and outbound qualification on Vapi, Retell, Twilio, Recall.ai
- **Mobile and desktop** — React Native/Expo, native Android, Electron, native macOS in Swift
- **Rescues** — inheriting a half-built product, finding what will break, getting it to production

### Stack

**Frontend** Next.js 15/16 · React 19 · TypeScript · Tailwind · shadcn/ui · Expo
**Backend** Node.js · Python · FastAPI · tRPC · WebSockets · BullMQ/ARQ
**Data** PostgreSQL · Prisma · Drizzle · pgvector · Redis · Qdrant
**AI** Claude · OpenAI · Gemini · LangChain · RAG · MCP · Whisper · ElevenLabs
**Infra** Docker · Coolify · Hetzner · Cloudflare · Traefik · CI/CD

I run my own servers. That is why I architect for year two rather than the first demo.

---

### A note on this profile

Most of what I build lives in private client repositories, so the public repos here are the pieces I can share: libraries and starters extracted from production systems, plus my own products. The contribution graph is the more honest record of the volume.

Before engineering I was CTO and Operations Manager of a Dubai e-commerce platform, scaling it from 50 to 1,200 vendors across five GCC markets. I read the business problem before the tech spec.

**Working on something?** [hello@taharafiq.com](mailto:hello@taharafiq.com) · Tell me what you are building or what is broken, and I will tell you how I would architect it before you spend anything.
