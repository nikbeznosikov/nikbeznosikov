<h1 align="center">Nikita Beznosikov</h1>

<p align="center">
  <b>Senior Full-Stack Engineer</b> · E-commerce · Checkout · Internal Tools · AI-native<br/>
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

Senior Full-Stack Engineer, 9 years building web products end to end. Owned the engineering for a US-based e-commerce business reaching ~$1M/month and ~2,000 orders/day: React checkout SPA, Node.js backend, admin tooling, and 50+ live offers running 3–5 A/B variations in parallel. Currently shipping independent products on the App Store and Shopify App Store.

Strongest in React, Next.js, Node.js, TypeScript. Plenty of integration work along the way: payments (Stripe, Braintree, PayPal, Apple/Google Pay), tracking (Facebook CAPI, GTM, BigQuery), infra (Cloudflare, DigitalOcean, AWS).

I use AI tools daily as a core part of how I work: running parallel agent sessions across branches for independent workstreams, using Cursor, Claude Code, and GitHub Copilot to ship faster.

I like real ownership: deciding the approach, building both ends, integrating services, and supporting what I ship. Honest about trade-offs and estimates. Comfortable in legacy code.

Open to senior full-stack roles in Germany, the Netherlands, or the UK. Also open to remote EU roles from Spain. Available via B2B contract, EOR, or relocation with sponsorship.

---

### Independent products

- **[Kairos](https://github.com/nikbeznosikov/kairos)** — AI job search workspace ([getkairos.fyi](https://getkairos.fyi)). Built during my own search. Paste a job posting and get a fit score against your CV, skills, salary, and work-auth constraints. Generates cover letters, recruiter Q&A, and cold outreach, then runs a critic pass to strip out the chatbot tells. Tracks every application through the pipeline in one place. Stack: Next.js 14, Supabase, Prisma, Gemini Flash, Railway, TypeScript.
- **[PassportPro](https://passportpro.app)** — Shopify app for EU Digital Product Passport / GPSR workflows. QR-coded passports, merchant admin interface, CSV bulk editing, AI-assisted autofill, Shopify product-page integration. Stack: Remix, Node.js, Prisma, Shopify Admin API.
- **[CreditReel](https://creditreel.to)** — Pay-per-use video testimonial SaaS. Businesses share a link; clients record or write reviews. Stripe credit payments, embeddable widgets, Cloudflare Stream delivery. Stack: Next.js, Supabase (PostgreSQL), Stripe, Cloudflare.
- **[InstaDeck](https://apps.apple.com/us/app/instadeck/id6754289754)** — iOS app that generates flashcard decks from any topic using LLMs, graded easy to hard. Spaced repetition, offline-first SQLite storage, freemium model. Stack: React Native, TypeScript, SQLite.
- **[GMC Store Readiness Scanner](https://apps.shopify.com/gmc-store-readiness-scanner)** — Shopify app that audits stores for Google Merchant Center readiness and surfaces prioritized fixes. Stack: Remix, PostgreSQL, Prisma, Shopify API.

---

### Other demos

| Project | Focus | Live | Stack |
| --- | --- | --- | --- |
| **[ai-feature-demo](https://github.com/nikbeznosikov/ai-feature-demo)** | Bounded LLM workflow, structured output, sentiment analysis, Cloudflare Turnstile cost protection | [demo](https://ai-feature-demo.vercel.app/) | Next.js · TypeScript · Gemini · Zod · Turnstile |
| **[payment-system-demo](https://github.com/nikbeznosikov/payment-system-demo)** | Multi-provider routing, retry logic, order state transitions, SSE event logs | [demo](https://web-production-dcad7.up.railway.app/) | Node.js · TypeScript · Express · PostgreSQL · Zod · SSE |
| **[analytics-dashboard-demo](https://github.com/nikbeznosikov/analytics-dashboard-demo)** | 50k synthetic orders, KPIs, period-over-period deltas, server-side filtering, virtualized tables | [demo](https://analytics-dashboard-demo-khaki.vercel.app) | Next.js · React · TypeScript · TanStack · Recharts |

---

### Experience

**Independent Engineer · Self-employed**
*2025 – Present · Remote*

Designing, building, and shipping independent products end to end: both ends of the stack, all integrations, all the way to live customers on the App Store and Shopify App Store.

---

**Senior Full-Stack Engineer · Launchify Ventures**
*2022 – 2025 · Remote*

US-based e-commerce business: ~$1M/month, ~2,000 orders/day, 80–90% mobile traffic.

- Designed and built the platform that replaced a legacy monolith — 50+ live offer funnels (blog → product → checkout → thank-you), each deployed independently with 3–5 A/B variations running in parallel, so marketing could iterate without blocking on engineering.
- Built a shared React checkout SPA across all offers, backed by a Node.js + MongoDB API handling orders, billing, retry logic, and admin operations. JWT auth for internal users.
- Built a React admin panel so product, marketing, and ops could configure offers, checkout flows, A/B tests, and integrations themselves — offer-launch time dropped from ~2 weeks to ~2 days.
- Built-in analytics on both admin panels surfaced sales by offer, special-offer take rates, decline rates, and funnel breakdowns.
- Integrated Stripe, Braintree, PayPal, Apple Pay, Google Pay. Multi-provider routing, webhook handlers, retry logic for failed orders.
- Built server-side tracking pipelines for Facebook CAPI, Google Ads, GTM, and BigQuery — reliable event data without browser-side dependencies.
- **Manna.com** — separate vitamin store built from scratch: Next.js app with its own React admin panel and Firebase Auth customer portal. Customers could update orders, cancel, and downgrade subscriptions through self-serve flows.
- Rebuilt a legacy subscription video platform on Next.js and migrated video delivery from AWS S3 to Cloudflare Stream — monthly infra cost dropped ~99% (~$800 → ~$5).

---

**Full-Stack Engineer · Launchify Ventures**
*2020 – 2022 · Remote*

Joined as frontend on the legacy monolith. When the backend engineer left during COVID, learned Node.js, took over the API, and proposed the rewrite that became the modular platform above — shipped the first admin panel and offer mini-apps.

---

**Frontend Engineer · Sinlao Media**
*2019 – 2020 · San Diego, CA*

Built an internal analytics dashboard for media buyers — Facebook ad performance and sales reporting. React, Redux, Chart.js, D3.js.

---

**Frontend Engineer · IQ Option**
*2016 – 2019 · St Petersburg*

Built an internal monitoring dashboard at an online-trading fintech. React, Redux, real-time data over WebSockets, charts and data tables for ops teams.

---

### Stack

**Frontend:** React · Next.js · TypeScript · JavaScript  
**Backend:** Node.js · Express · REST APIs · Webhooks · JWT · Firebase Auth · Zod  
**Databases:** MongoDB · Supabase (PostgreSQL, side projects)  
**Payments:** Stripe · Braintree · PayPal · Apple Pay · Google Pay · Shopify  
**Analytics / tracking:** Facebook CAPI · Google Ads · GTM · Google Analytics API · BigQuery  
**Infrastructure:** AWS (EC2, S3, IAM) · DigitalOcean · Vercel · Railway · Cloudflare (Stream, Workers, DNS)  
**AI tools:** Cursor · Claude · GitHub Copilot  
**Testing / Mobile:** Playwright · Cypress · React Native (published iOS app)  

---

### Links

- Portfolio: [nikbeznosikov.github.io](https://nikbeznosikov.github.io)
- LinkedIn: [linkedin.com/in/nikita-beznosikov](https://www.linkedin.com/in/nikita-beznosikov/)
