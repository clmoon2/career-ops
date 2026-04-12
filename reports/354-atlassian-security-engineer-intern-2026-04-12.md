# Atlassian — Security Engineer Intern, 2026 Summer U.S.

**Score:** 4.2/5
**URL:** https://join.atlassian.com/event-12707/jobs/20957
**PDF:** ❌
**Date:** 2026-04-12
**Verification:** unconfirmed (page accessible, active listing confirmed via WebFetch)

---

## Company Snapshot

Atlassian (NASDAQ: TEAM) is the maker of Jira, Confluence, Trello, and Bitbucket — the productivity and DevOps tooling backbone of 300,000+ organizations worldwide. Their security team protects enterprise SaaS used by governments, Fortune 100 companies, and millions of developers.

- **Revenue:** ~$4.4B ARR (FY2025 est.)
- **Headcount:** ~12,000 employees
- **HQ:** Sydney, Australia (U.S. offices: San Francisco, Austin, Seattle, NYC)
- **Products:** Jira (issue tracking), Confluence (wiki), Bitbucket (git hosting), Jira Service Management
- **Security team:** Protects Atlassian Cloud, Forge platform, and enterprise deployments

---

## Role Summary

**Security Engineer Intern, 2026 Summer U.S.** — building security monitoring, vulnerability research, and infrastructure hardening systems.

Key responsibilities:
- Build and run monitoring and analytics systems to detect compromises
- Conduct vulnerability research and build automation to address findings
- Evaluate product and feature hardening recommendations
- Contribute to infrastructure security architecture decisions

**Comp:** $59–$75/hr (Seattle Zone A) | $53–$68/hr (Zone B) | $49–$62/hr (Zone C)
**Location:** Seattle, Washington
**Duration:** 12 weeks (May/June – August/September 2026)
**Graduation requirement:** By June 2027

---

## Scoring Breakdown

### A. CV Match — 4.5/5

**Strengths:**
- **Security engineering depth**: HMAC-SHA256 CSRF protection, OAuth proxy engineering (bypassing enterprise firewall), TLS 1.2/1.3 with ECDSA certificates and Mozilla-recommended cipher suites, CORS origin restrictions, CSP lockdown, PII-safe Sentry error tracking — this is not checkbox security; it's production security engineering at Finch
- **Adversarial LLM testing**: Conducted prompt injection research against uncensored LLMs (system prompt bypass, developer mode simulation) — directly relevant to AI security work Atlassian would do protecting Atlassian Intelligence
- **Monitoring & observability**: Distributed tracing with trace IDs propagating across Chrome extension content script, service worker, and backend; Sentry + PostHog integration; field-level verification
- **Vulnerability mindset**: Built defense-in-depth: honeypot/financial field detection, LaTeX injection prevention, anti-detection automation, request ID sanitization, sensitive storage key purging
- **Programming languages**: Python (primary, 23K+ LOC), TypeScript, JavaScript ✓ (role asks for Java/Python/JavaScript)
- **Data structures and design**: CS coursework (Algorithms, OS, AI), 602-test suite, deterministic validation gates
- **Cybersecurity Minor at TAMU** — formal security education
- **Computer Security coursework** (listed in education)
- **Graduating by June 2027** ✓ (In Progress at TAMU, assuming 2027 grad)

**Gaps:**
- No Java (role mentions Java as option — Python and JavaScript cover the requirement)
- No enterprise-scale security operations experience (but internship will provide this)
- No prior security internship (first real security role — but the depth of self-taught security work compensates)

**Verdict:** This is the strongest CV-to-role match on the security engineering dimension in the entire pipeline.

### B. North Star Alignment — 5/5

Cybersecurity / Security Engineering Intern is Carlos's **primary archetype**. This role is the textbook definition of the target: enterprise security team, monitoring systems, vulnerability research, infrastructure hardening. Atlassian's scale (protecting 300,000+ orgs) means the work has real impact.

### C. Compensation — 4.5/5

$59–$75/hr in Seattle Zone A = $118K–$150K annualized. This is significantly above Carlos's $80K–$120K FTE target range. Even at the Zone C floor ($49/hr), this is $98K annualized — above the $70K minimum. Strong.

### D. Cultural Signals — 4.0/5

- Top-tier tech company with genuine security challenges at enterprise scale
- TEAM is remote-friendly (distributed globally) but this is an in-person Seattle role
- Atlassian TEAM ANYWHERE culture values autonomy and impact over presence
- Security team at a company that handles highly sensitive org data (commits, wikis, tickets) means the work matters
- 12-week structured internship with likely mentorship program
- Intern → full-time conversion path is real at Atlassian

### E. Red Flags — -0.8

- **Seattle relocation**: Carlos is in College Station, TX. Seattle summer relocation is feasible but requires planning (Atlassian may offer housing assistance — worth asking).
- **Not eligible for F1/J1**: Not an issue for Carlos (no sponsorship needed ✓)
- **Large company structure**: 12,000-person company = more process, slower decisions vs. startups
- **Posting date September 2025**: This was posted 7 months ago, which raises the question of whether positions are filled. Verify before applying.

### Global Score: 4.2/5

Strong alignment on every dimension. The security engineering portfolio (OAuth proxy, TLS, HMAC-SHA256, adversarial LLM testing) is legitimately impressive for an intern candidate. Top-tier company, exceptional comp.

---

## Application Strategy

**Should apply:** Yes — this is a top-5 security internship opportunity.

**Proof points to lead with:**
1. **OAuth proxy engineering**: "Engineered a stateless OAuth proxy with HMAC-SHA256 CSRF protection and timing-safe signature verification (hmac.compare_digest), bypassing Texas A&M's Cisco Umbrella enterprise firewall blocking Supabase auth endpoints." — shows real-world security problem solving.
2. **Defense-in-depth at Finch**: "Implemented defense-in-depth: CORS origin restrictions, request ID tracing with sanitization, LaTeX injection prevention, PII-safe Sentry error tracking, honeypot/financial field detection, CSP lockdown." — maps directly to product hardening role.
3. **Adversarial LLM testing**: "Conducted prompt injection research — testing system prompt bypass, developer mode simulation, leaked transcript framing against uncensored LLMs." — directly relevant to Atlassian Intelligence security.
4. **Distributed tracing**: "Built distributed tracing with trace IDs propagating across Chrome extension, service worker, and backend with field-level verification." — maps to monitoring/analytics systems.

**Cover letter angle:**
> "Security engineering at Atlassian is protecting the commit history and project wikis of organizations that depend on Jira as their single source of truth. I've spent the past year engineering production security at Finch — HMAC-CSRF protection, TLS hardening, adversarial LLM testing. I want to bring that builder energy to your team."

**Verify opening status**: Email recruiting or apply directly — this posting is 7 months old and may have rolling admissions or specific cohort timing.

---

## Next Actions

- [ ] Verify role is still open (apply and check for confirmation email)
- [ ] Apply at https://join.atlassian.com/event-12707/jobs/20957
- [ ] Tailor CV to lead with security section (OAuth proxy, TLS, adversarial testing)
- [ ] Write cover letter citing Atlassian Intelligence as AI security vector
- [ ] Research housing options in Seattle for summer (ask Atlassian HR about stipend)
