<h1 align="center">Nikita Beznosikov</h1>

<p align="center">
  <b>Senior Full-Stack Engineer</b> · E-commerce · Checkout · Internal Tools<br/>
  React · Next.js · Node.js · TypeScript · 9 years · Remote from Madrid
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nikita-beznosikov/">
    <img src="https://img.shields.io/badge/LinkedIn-nikita--beznosikov-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://nikbeznosikov.github.io">
    <img src="https://img.shields.io/badge/Portfolio-nikbeznosikov.github.io-24292f?style=flat-square" alt="Portfolio"/>
  </a>
  <img src="https://img.shields.io/badge/Madrid-Remote%20EU%20%7C%20B2B%20%2F%20EOR-2ea043?style=flat-square" alt="Madrid · Remote EU · B2B / EOR"/>
</p>

---

### About

Senior Full-Stack Engineer, 9 years building web products end to end. For the last 6 years I was the primary engineer on a US-based DTC e-commerce stack — 50+ live offers with A/B variations, a React checkout SPA, Node.js backend, and admin tooling — that reached ~$1M/month and ~2,000 orders/day.

Strongest in React, Next.js, Node.js, TypeScript. Plenty of integration work along the way — payments (Stripe, Braintree, PayPal, Apple/Google Pay), tracking (Facebook CAPI, GTM, BigQuery), infra basics (Cloudflare, DigitalOcean, AWS).

I use AI tools daily as a core part of how I work — running parallel agent sessions across branches for independent workstreams, using Cursor, Claude Code, and GitHub Copilot for code generation, review, and problem-solving to ship faster.

I like real ownership: deciding the approach, building both ends, integrating services, and supporting what I shipped. Honest about trade-offs and estimates. Comfortable in legacy code.

Open to senior full-stack roles in the Netherlands, Germany, or the UK. Also open to remote EU roles from Spain. No EU work authorization — available via B2B contract, EOR, or relocation with sponsorship.

---

### Products and apps

- **[GMC Store Readiness Scanner](https://apps.shopify.com/gmc-store-readiness-scanner)** — Shopify app that audits stores for Google Merchant Center readiness and surfaces prioritized fixes. Stack: Remix, PostgreSQL, Prisma, Shopify API.
- **[PassportPro](https://passportpro.app)** — Shopify app for EU Digital Product Passport / GPSR workflows with QR passports, bulk editing, and AI-assisted autofill. Stack: Remix, Node.js, Prisma, Shopify API.
- **[CreditReel](https://creditreel.to)** — Pay-per-use video testimonial SaaS with shareable review links, Stripe credit payments, embeddable widgets, and Cloudflare Stream delivery. Stack: Next.js, Supabase, Stripe, Cloudflare.

---

### Portfolio demos

AI-assisted demos I built to explore patterns relevant to my work. I can walk through what they do and why the pattern matters, but I won't pretend every implementation decision was mine.

| Project | Focus | Live | Stack |
| --- | --- | --- | --- |
| **[payment-system-demo](https://github.com/nikbeznosikov/payment-system-demo)** | Multi-provider routing, retry logic, order state transitions, SSE event logs | [demo](https://web-production-dcad7.up.railway.app/) | Node.js · TypeScript · Express · PostgreSQL · Zod · SSE |
| **[analytics-dashboard-demo](https://github.com/nikbeznosikov/analytics-dashboard-demo)** | 50k synthetic orders, KPIs, period-over-period deltas, server-side filtering, virtualized tables | [demo](https://analytics-dashboard-demo-khaki.vercel.app) | Next.js · React · TypeScript · TanStack · Recharts |
| **[ai-feature-demo](https://github.com/nikbeznosikov/ai-feature-demo)** | Bounded LLM workflow, structured output, sentiment analysis, Cloudflare Turnstile cost protection | [demo](https://ai-feature-demo.vercel.app/) | Next.js · TypeScript · Gemini · Zod · Turnstile |

---

### Main experience

**Senior Full-Stack Engineer · Launchify Ventures**
*2020 – Present · Remote / US-based*

Primary engineer on a US-based DTC e-commerce business — ~$1M/month, ~2,000 orders/day, 80–90% mobile traffic. Mentored one junior; worked alongside a backend engineer at different points.

Stack: React, Next.js, TypeScript, Node.js, MongoDB, Cloudflare, DigitalOcean.

**Project 1 — DTC platform rebuild**
Replaced a legacy monolith with a modular stack:

- 50+ live offers (blog, interstitial, and supporting pages each), 3–5 A/B variations running in parallel
- A shared React checkout SPA across all offers
- Node.js + MongoDB backend for orders, billing, fraud, and admin
- React admin panel so product, marketing, and ops could configure offers, checkout flows, A/B tests, and integrations themselves — offer-launch time dropped from ~2 weeks to ~2 days
- Stripe, Braintree, PayPal, Apple Pay, and Google Pay integrated through Sticky.io
- Rule-based fraud and carding protection (IP blocking, URL parameter checks) plus Visa CDRN for chargeback automation
- Retry job that reprocessed unfinished orders — recovered ~10–20% of failed transactions
- Server-side tracking pipelines for Facebook CAPI, Google Ads, GTM, and BigQuery
- Migrated video delivery from AWS S3 to Cloudflare Stream — that infra cost dropped ~99%

**Project 2 — Manna.com**
Separate DTC store built from scratch — Next.js with its own React/MUI admin panel and Node.js backend. Same payment integrations and tracking as Project 1, separate codebase.

Earlier: internal analytics dashboards at Sinlao Media (React, Redux, Chart.js, D3.js), internal monitoring UI at IQ Option (React, Redux, WebSockets), and cross-browser web apps at Greenlabs.

---

### Stack

**Frontend:** React · Next.js · TypeScript · JavaScript
**Backend:** Node.js · Express · REST APIs · Webhooks · Zod
**Databases:** MongoDB · PostgreSQL · Prisma · Supabase
**Payments / commerce:** Stripe · Braintree · PayPal · Apple Pay · Google Pay · Sticky.io · Visa CDRN · Shopify
**Analytics / tracking:** Facebook CAPI · Google Ads · GTM · Google Analytics API · BigQuery
**Infrastructure:** AWS · DigitalOcean · Vercel · Railway · Cloudflare (Stream, Workers, DNS)
**Testing:** Playwright · Cypress
**Mobile:** React Native

---

### Links

- Portfolio: [nikbeznosikov.github.io](https://nikbeznosikov.github.io)
- LinkedIn: [linkedin.com/in/nikita-beznosikov](https://www.linkedin.com/in/nikita-beznosikov/)
