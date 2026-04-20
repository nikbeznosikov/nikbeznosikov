<h1 align="center">Nikita Beznosikov</h1>

<p align="center">
  <b>Senior Full-Stack Engineer</b> · 9+ years · E-commerce, payments, fraud, analytics<br/>
  Built &amp; scaled a DTC platform to <b>~$1M/month</b> revenue as the sole engineer
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nikita-beznosikov/"><img src="https://img.shields.io/badge/LinkedIn-nikita--beznosikov-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Madrid-Open%20to%20Remote-2ea043?style=flat-square" alt="Location"/>
</p>

---

### About

Spent the last six years as the **only engineer** on a US DTC e-commerce platform — checkout, multi-provider payments (Stripe, Braintree, PayPal, Apple/Google Pay), fraud / carding prevention, Visa CDRN integration, server-side tracking, and a BigQuery analytics pipeline. Re-architected the original PHP/Laravel monolith into a Next.js + Node.js stack and cut video infra cost ~99% by migrating S3 → Cloudflare Stream.

Comfortable owning a system end-to-end: architecture, infrastructure, code, on-call.

### Selected work — public demos

Each repo isolates one production concern, ships with tests, security headers, and a live deployment.

| Project | What it shows | Live | Stack |
| --- | --- | --- | --- |
| **[payment-system-demo](https://github.com/nikbeznosikov/payment-system-demo)** | Multi-provider checkout, retry w/ backoff + jitter, provider fallback, idempotency cache, Stripe webhook verification, live SSE log | [demo](https://web-production-dcad7.up.railway.app/) | Node · TS · Express · Postgres · Stripe |
| **[backend-architecture-template](https://github.com/nikbeznosikov/backend-architecture-template)** | Layered API, JWT w/ refresh-token rotation + reuse detection, transactional orders under `Serializable`, Zod-generated OpenAPI | [demo](https://backend-architecture-template-production.up.railway.app) · [Swagger](https://backend-architecture-template-production.up.railway.app/docs) | Node · TS · Express · Prisma · Postgres |
| **[analytics-dashboard-demo](https://github.com/nikbeznosikov/analytics-dashboard-demo)** | 50k synthetic orders, ~105k-point downsampled time series, virtualized server-side filtered table, KPIs w/ PoP deltas | [demo](https://analytics-dashboard-demo-khaki.vercel.app) | Next.js 16 · React 19 · TanStack · Recharts |
| **[ai-feature-demo](https://github.com/nikbeznosikov/ai-feature-demo)** | Bounded LLM call returning Zod-validated structured sentiment, Cloudflare Turnstile to cap cost surface | [demo](https://ai-feature-demo.vercel.app/) | Next.js 16 · Gemini · Zod · Turnstile |

### Experience

- **Senior Full-Stack Engineer · Launchify Ventures** — *2020 – Present, Remote (US)*<br/>
  Sole engineer on a DTC platform, peak ~$1M/mo. Owned architecture, infra, payments, fraud, analytics.
- **Frontend Engineer · Sinlao Media** — *2019 – 2020*<br/>
  React + Redux analytics dashboard for media-buying decisions.
- **Frontend Engineer · IQ Option** — *2016 – 2019*<br/>
  Real-time monitoring system in React + WebSockets, optimised for high-frequency fintech data.

### Stack

**Frontend** React · Next.js · TypeScript · Tailwind · React Native &nbsp;•&nbsp; **Backend** Node.js · Express · GraphQL &nbsp;•&nbsp; **Databases** PostgreSQL · MongoDB · Prisma &nbsp;•&nbsp; **Infra** Cloudflare (Workers, Stream, DNS) · AWS · DigitalOcean · Railway · Vercel &nbsp;•&nbsp; **Payments** Stripe · Braintree · PayPal · Apple/Google Pay · Visa CDRN &nbsp;•&nbsp; **Analytics** BigQuery · Facebook CAPI · GTM &nbsp;•&nbsp; **Testing** Vitest · Playwright · Cypress

---

<sub>Looking for: senior full-stack roles, remote, focused on payments, checkout, e-commerce infra, or platform engineering. Best way to reach me is <a href="https://www.linkedin.com/in/nikita-beznosikov/">LinkedIn</a>.</sub>
