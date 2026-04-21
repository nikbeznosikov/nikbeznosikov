<h1 align="center">Nikita Beznosikov</h1>
<p align="center">
  <b>Senior Full-Stack Engineer</b> · DTC E-commerce · Payments · Checkout<br/>
  Scaled a $1M/mo DTC platform solo · 9+ years · Remote from Madrid
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/nikita-beznosikov/"><img src="https://img.shields.io/badge/LinkedIn-nikita--beznosikov-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://nikbeznosikov.github.io"><img src="https://img.shields.io/badge/Portfolio-nikbeznosikov.github.io-24292f?style=flat-square" alt="Portfolio"/></a>
  <img src="https://img.shields.io/badge/Madrid-B2B%20%2F%20EOR%20ready-2ea043?style=flat-square" alt="Location"/>
</p>

---

### About

Sole engineer for 6 years on a US-based DTC e-commerce platform peaking at **~$1M/month** and **1,000+ orders/day**. Deep hands-on specialty in checkout systems, multi-provider payments, fraud prevention, experimentation infrastructure, and analytics pipelines.

- Re-architected PHP/Laravel monolith into Next.js + Node.js + MongoDB — new-offer launch time from ~2 weeks to ~2 days
- Checkout and offer-management system powering ~10–30 A/B tests per month via VWO
- Multi-provider payment routing (Stripe, Braintree, PayPal, Apple/Google Pay) with retry + failover, recovering ~10–20% of initially failed transactions
- Fraud prevention + automated Visa CDRN chargeback workflow
- Server-side tracking (Facebook CAPI, Google Ads, GTM) + BigQuery analytics pipeline
- Cut video infrastructure cost ~99% by migrating S3 → Cloudflare Stream

Comfortable owning a system end-to-end: architecture, infrastructure, code, on-call.

### Selected work — public demos

Each repo isolates one production concern, ships with tests, security headers, and a live deployment.

| Project | What it shows | Live | Stack |
| --- | --- | --- | --- |
| **[payment-system-demo](https://github.com/nikbeznosikov/payment-system-demo)** | Multi-provider checkout, retry w/ backoff + jitter, provider fallback, idempotency cache, Stripe webhook verification, live SSE log | [demo](https://web-production-dcad7.up.railway.app/) | Node · TS · Express · Postgres · Stripe |
| **[backend-architecture-template](https://github.com/nikbeznosikov/backend-architecture-template)** | Layered API, JWT w/ refresh-token rotation + reuse detection, transactional orders under `Serializable`, Zod-generated OpenAPI | [demo](https://backend-architecture-template-production.up.railway.app) · [Swagger](https://backend-architecture-template-production.up.railway.app/docs) | Node · TS · Express · Prisma · Postgres |
| **[analytics-dashboard-demo](https://github.com/nikbeznosikov/analytics-dashboard-demo)** | 50k synthetic orders, ~105k-point downsampled time series, virtualized server-side filtered table, KPIs w/ PoP deltas | [demo](https://analytics-dashboard-demo-khaki.vercel.app) | Next.js 16 · React 19 · TanStack · Recharts |
| **[ai-feature-demo](https://github.com/nikbeznosikov/ai-feature-demo)** | Bounded LLM call returning Zod-validated structured sentiment, Cloudflare Turnstile to cap cost surface | [demo](https://ai-feature-demo.vercel.app/) | Next.js 16 · Gemini · Zod · Turnstile |

### Also building

- **[PassportPro](https://passportpro.app)** — Shopify app for EU Digital Product Passport / GPSR compliance. QR passports, bulk editing, AI autofill.
- **[GMC Store Readiness Scanner](https://apps.shopify.com/gmc-store-readiness-scanner)** — Shopify audit tool for Google Merchant Center compliance.
- **[CreditReel](https://creditreel.to)** — Pay-per-use video testimonial SaaS.

### Experience

- **Senior Full-Stack Engineer · Launchify Ventures** — *2020 – Present, Remote (US)*<br/>
  Sole engineer on a DTC platform, ~1,000+ orders/day at peak, ~$1M/month revenue, ~80–90% mobile traffic. Owned architecture, infra, payments, fraud, analytics.
- **Frontend Engineer · Sinlao Media** — *2019 – 2020*<br/>
  React + Redux analytics dashboard for media-buying decisions.
- **Frontend Engineer · IQ Option** — *2016 – 2019*<br/>
  Real-time monitoring in React + WebSockets for high-frequency fintech data.

### Stack

**Frontend** React · Next.js · TypeScript · Tailwind · React Native &nbsp;•&nbsp; **Backend** Node.js · Express · GraphQL &nbsp;•&nbsp; **Databases** MongoDB · PostgreSQL · Prisma &nbsp;•&nbsp; **Infra** Cloudflare (Workers, Stream) · AWS · DigitalOcean · Vercel · Railway &nbsp;•&nbsp; **Payments** Stripe · Braintree · PayPal · Apple/Google Pay · Visa CDRN &nbsp;•&nbsp; **Analytics** BigQuery · Facebook CAPI · GTM &nbsp;•&nbsp; **Testing** Vitest · Playwright · Cypress

---

<sub>Looking for senior full-stack roles at e-commerce SaaS, Shopify ecosystem, DTC brands, or payments-adjacent companies. Remote, B2B or EOR. Reach me on <a href="https://www.linkedin.com/in/nikita-beznosikov/">LinkedIn</a>.</sub>
