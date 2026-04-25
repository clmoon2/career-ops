# Ramp — Software Engineer Internship, Backend

**Score:** 4.1/5
**URL:** https://jobs.ashbyhq.com/ramp/c50962b5-c641-4d44-bbe5-7f1d6e7ce51f
**PDF:** ❌
**Date:** 2026-04-25
**Status:** Evaluada

---

## Company

Ramp is an enterprise financial operations platform ($7.65B valuation, 2024). AI-first corporate cards, expense management, vendor management, procurement, travel booking, and automated bookkeeping. Backed by Founders Fund, Stripe, Goldman Sachs, Coatue. 700+ employees, top-tier engineering culture known for high velocity and quality.

**Note:** Ramp FDE Intern (#341) already evaluated at 4.5/5. This is the Backend SWE track — different role, same company. Both are valid targets.

## Role

12 or 16-week internship, **Summer 2026**. NYC or SF in-person. Competitive compensation: **$11,000/mo + housing stipend** + catered lunches + MacBook.

Backend track responsibilities:
- Build and maintain high-throughput financial services (payments, card processing, vendor mgmt)
- Work across Flask (Python), Elixir, AWS, RabbitMQ, PostgreSQL
- Contribute to Ramp's core transaction infrastructure and AI-powered automation features
- Opportunity to work on AI integrations within Ramp's financial ops platform

Requirements: pursuing BS/MS in CS or related field, graduating Dec 2026–2028; track record of shipping high-quality products or strong side projects; strong fundamentals.

---

## Evaluation

### A — Match con CV (4.4/5)

- **Flask/Python ✅** — Carlos is the sole backend architect of Finch's Flask backend: 23,800 LOC, 43 API routes, strict unidirectional dependency flow, 7-stage AI pipeline. Flask at Ramp scale is directly analogous.
- **PostgreSQL ✅** — Finch uses Supabase/PostgreSQL with PL/pgSQL stored functions, row-level locking for race-condition-safe pipeline quota enforcement, and composite indexes.
- **AWS ✅** — Blue/green CI/CD on AWS EC2 with ALB routing, ECR image management, GitHub Actions workflows with confirmation gates for production promotion.
- **High-throughput / multi-service architecture ✅** — Finch processes 100+ jobs/day with a stateless OAuth proxy, Cloudflare Workers edge API gateway (Hono, 20+ proxied endpoints), distributed tracing with trace IDs propagating across Chrome extension + backend + service worker.
- **Elixir ❌** — Not in CV. Gap, but learnable; Ramp hires interns to grow, and Carlos's backend architecture depth compensates.
- **RabbitMQ ❌** — Queue familiarity gap. Minor — PostgreSQL admission control system (row-level locking, stored functions) demonstrates async/concurrency thinking.
- **Graduation window ✅** — Dec 2026–2028 requirement matches Carlos's timeline.

### B — North Star alignment (4.0/5)

- **Archetype:** SWE Intern (Backend) — primary archetype
- Ramp is a top-tier engineering destination for interns; strong brand for future job search
- Backend track is less archetype-differentiating than FDE (#341) for Carlos's profile, but equally valid
- "AI-powered financial ops" gives Carlos an angle to pitch Finch's AI integration experience
- Two Ramp tracks (FDE + Backend) = apply to both in parallel; different teams, different work

### C — Comp (5.0/5)

- **$11,000/mo + housing stipend** = top-tier intern compensation
- Same comp as Ramp FDE (#341) which was rated 4.5/5
- Equivalent to ~$67.50/hr (confirmed via Levels.fyi)
- Exceeds the $80K–120K target range equivalent; well above the $70K minimum floor

### D — Cultural signals (4.3/5)

- Ramp = one of the best-run fintechs in the US, known for extreme product quality and fast iteration
- Founders Fund + Stripe + Goldman backing = durable company
- Strong intern cohort (150+ interns historically), structured mentorship
- In-person NYC or SF: both are top tech markets; networking value is high
- Engineering culture that expects interns to ship real code in production

### E — Red flags

- **Elixir/RabbitMQ gaps**: Minor — backend architecture fundamentals transfer; Ramp trains interns
- **NYC or SF relocation**: College Station TX → NYC/SF for 12–16 weeks. Logistics cost; Carlos has demonstrated flexibility with SF-heavy applications
- **Ramp FDE (#341) is the stronger archetype match**: FDE is Carlos's differentiator profile (client-facing, fast delivery, AI integration). Backend SWE is a strong but more generic role. Apply to both, prioritize FDE in outreach.

---

## Global: 4.1/5

**Recommendation: Apply alongside FDE #341.**

Carlos's Flask backend (23,800 LOC, 43 routes, blue/green CI/CD on AWS) is a direct analog to Ramp's backend stack. Flask + PostgreSQL + AWS is a near-perfect skill match. The Elixir gap is real but manageable — Ramp evaluates intern candidates on fundamentals and shipping ability, both of which Carlos demonstrates with Finch.

$11K/mo + housing puts this in the top compensation tier for Summer 2026 internships. The brand carries significant weight for future recruiting.

**Apply to both Ramp Backend (#415) and Ramp FDE (#341). They are different teams. FDE is the primary archetype match; Backend is a fallback with equivalent comp.**

**Lead proof point:** "Sole backend architect of a 35K-line Flask/Python codebase with 43 API routes, blue/green CI/CD on AWS EC2, PostgreSQL row-level locking for quota enforcement, and a 602-test suite — shipping in production at Ramp's scale is the natural next step."
