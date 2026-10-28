## Hi, I'm Ram Gupta 👋

Full-stack software engineer with **4 years** building a multi-tenant B2B SaaS (ATS + CRM) used by recruitment agencies worldwide. I own features end to end, from the design doc to production support. I work in **PHP (Laravel)**, **Python (FastAPI)**, **Vue.js / TypeScript** and **MySQL** on **AWS**, and since **July 2026** I've been on the AI team building **LLM-powered features**.

📍 Indore, India · open to relocate or remote · 🟢 **available immediately**
🌐 **Portfolio:** [ramgupta07.github.io](https://ramgupta07.github.io)

### What I've built
- **AI resume-editing backend** (Python/FastAPI): signed edit sessions, an LLM-as-judge check before each edit, model fallback to AWS Bedrock with explicit timeouts, Redis usage caps, and billing only after an edit succeeds. Covered by 284 pytest tests.
- **Navigation at 100K+ records:** the server looks up a record's position in a filtered, sorted queue, and the UI loads only the 100-row chunk around it, instead of the whole queue.
- **Record-link custom fields** for Candidates and Jobs: an access-controlled batch lookup API (type allow-list, view permission, tenant and ownership filters), one batched lookup per list page, and sync between a legacy Vue 2 app and a Vue 3 app running as micro-frontends.
- **Conditional (dependent) fields on public application forms:** public endpoints scoped by the job or talent-pool link, plus a ~1,500-line React form engine that shows, hides and filters child fields and clears stale answers and uploads.
- **Multi-tenant security and XSS-safe rich text:** tenant-scoped queries, permission checks, and sanitisation on both save and render.
- **Event-driven notifications:** producers to AWS SQS, queue workers, and per-tenant storage in MongoDB.

### Stack
`PHP` `Laravel` `Python` `FastAPI` `Vue.js` `TypeScript` `JavaScript` `MySQL` `MongoDB` `Redis`
`AWS (SQS, S3, Bedrock)` `REST APIs` `LLM integration` `Pinia` `AG Grid` `Next.js (working knowledge)`

### Reach me
[Portfolio](https://ramgupta07.github.io) · [LinkedIn](https://www.linkedin.com/in/ramgupta07/) · [Email](mailto:guptaram465691@gmail.com)

<sub>Most of my work lives in private company repositories; the portfolio has case studies of what I built and how.</sub>
