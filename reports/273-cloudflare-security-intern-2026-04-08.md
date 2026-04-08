# Cloudflare — Security Engineer Intern (Summer 2026)

**Date:** 2026-04-08
**Score:** 4.4/5
**URL:** https://job-boards.greenhouse.io/cloudflare/jobs/7582150
**PDF:** ❌
**Status:** Evaluated

---

## Role Overview

**Company:** Cloudflare
**Title:** Security Engineer Intern (Summer 2026)
**Location:** Austin, TX (in-office 3–5 days/week; local candidates only — no relocation provided)
**Comp:** Not listed (Cloudflare intern rates typically $40-55/hr based on public data)
**Type:** Summer Internship, 12–16 weeks

Cloudflare is the leading edge network/security platform ($1B+ ARR, ~4000 employees). This role sits in the security org, working cross-functionally with Product, Infrastructure, and Engineering to integrate security into the development lifecycle.

---

## Scoring

| Dimension | Score | Notes |
|-----------|-------|-------|
| Match con CV | 4.8 | Deep security engineering experience; Cloudflare stack already in production use |
| North Star alignment | 4.5 | Cybersecurity Minor + Security Engineering Intern archetype is primary target |
| Comp | 3.5 | Unlisted, but Cloudflare intern rates are competitive |
| Cultural signals | 4.5 | Mission-driven, strong eng culture, blog/Cloudflare.tv exposure |
| Red flags | -0.5 | "Local to Austin" requirement — Carlos is in College Station (1.5hrs away); no relocation |
| **Global** | **4.4** | **Strong match — apply with note about TX proximity** |

---

## CV Match Analysis

**Direct skill hits:**
- **Cloudflare in production** → Carlos built a Cloudflare Workers edge API gateway at Finch (Hono, proxying 20+ endpoints, OAuth redirect handling, edge cache poisoning prevention, S3 signed URL streaming) — he knows the platform deeply
- **Security engineering depth** → HMAC-SHA256 CSRF protection, timing-safe signature verification (hmac.compare_digest), TLS 1.2/1.3 with ECDSA certs, Mozilla cipher suites, CORS origin restrictions, CSP lockdown, LaTeX injection prevention, honeypot detection
- **OWASP coverage** → XSS (CSP), CSRF (HMAC token), SQL injection (parameterized queries), injection prevention (LaTeX sanitization), sensitive data exposure (PII-safe Sentry), broken authentication (OAuth proxy hardening)
- **AWS + infrastructure** → Blue/green CI/CD on AWS EC2 with ALB routing, 5 GitHub Actions workflows
- **Python + TypeScript** → Matches Cloudflare's backend stack

**JD requirement mapping:**
> "Solid understanding of OWASP Top 10, common attack vectors (XSS, SQLi, CSRF), and mitigations" → ✅ Implemented all of these in production at Finch
> "Bonus: personal security/software projects, open-source contributions" → ✅ LLM Adversarial Testing project + 673 GH contributions
> "Bonus: experience with Cloudflare developer platform" → ✅ **Carlos uses Cloudflare Workers in production today**
> "Curiosity, empathy, and ability to get things done" → ✅ Co-founded startup, shipped production platform

---

## Why This Role

This is a near-perfect fit on skills. Carlos uses Cloudflare Workers in production — he's not just familiar with the platform, he's built real systems on it. The security engineering breadth from Finch (OAuth proxy, TLS hardening, CORS, CSP, HMAC-SHA256) directly maps to what this role requires.

The "local to Austin" requirement is the only friction. Carlos is at Texas A&M in College Station, TX — approximately 1.5 hours from Austin. For a summer internship, short-term Austin housing is viable and common for interns. Cloudflare's "no relocation" policy likely means they won't pay for cross-country moves, not that College Station–Austin is disqualifying.

**Recommendation:** Apply and briefly address TX location in cover letter or note that you're Texas-based and can be in Austin for the summer.

---

## Recommended Narrative

Lead with: "I built a Cloudflare Workers edge API gateway in production — OAuth redirect handling, edge cache poisoning prevention, and 20+ endpoint proxying. I'm a Texas A&M CS student with a Cybersecurity Minor and a security engineering background that maps directly to what this role requires."

Proof points:
1. Cloudflare Workers gateway at Finch (Hono, Cloudflare Workers, S3 signed URL streaming)
2. Security depth: HMAC-SHA256 CSRF, TLS 1.2/1.3 with ECDSA, CORS, CSP, PII redaction, OAuth proxy
3. Cybersecurity Minor at Texas A&M + adversarial LLM testing research

---

## Red Flags / Concerns

- "Local to Austin" preference → Carlos is 1.5hrs away (College Station → Austin). Address proactively in application
- No stated comp → Standard Cloudflare intern rates are competitive, likely $40-55/hr
- Cross-functional presentation at end of internship → Carlos will need to prepare a polished security project demo

---

## Recommendation

**Apply.** One of the strongest location-accessible matches in the current batch. Carlos is already running Cloudflare Workers in production and his security engineering portfolio directly maps to the role. The Austin locality requirement is a minor friction for a College Station student — easily addressed.
