# Evaluation Report #392 — TikTok Security Software Engineer Project Intern (Product Security) - 2026 Start

**Date:** 2026-04-21
**Score:** 4.0/5
**URL:** https://lifeattiktok.com/search/7600536394771564853
**Status:** Evaluada
**PDF:** ❌

---

## Position Summary

| Field | Details |
|-------|---------|
| Company | TikTok (ByteDance) |
| Role | Security Software Engineer Project Intern (Product Security) - 2026 Start (BS/MS) |
| Location | San Jose, CA (on-site) |
| Comp | $45–60/hr |
| Duration | 3 months minimum |
| Start Dates | May 11, 18, 26; June 8, 22, 2026 |
| Deadline | Rolling |
| Archetype | Cybersecurity / Security Intern |

---

## Offer Verification

**Verification:** active — confirmed listed on lifeattiktok.com, Glassdoor, The Muse, Simply Hired, StudentCircus, NodeFlair as of 2026-04-21.

---

## Score Breakdown

| Dimension | Score | Notes |
|-----------|-------|-------|
| CV Match | 4.5/5 | LLM/MCP security + pentesting; adversarial LLM testing project; SDLC security tools; Python/Go/JS match |
| North Star | 4.5/5 | Primary archetype: Cybersecurity / Security Intern — direct hit; LLM security is Carlos's differentiator |
| Comp | 3.5/5 | $45-60/hr; below Carlos's $55+/hr preference but within acceptable range; midpoint $52.50 |
| Cultural | 3.0/5 | TikTok/ByteDance brand risk (Chinese parent company); otherwise strong AI-first security culture |
| Red Flags | -1.0 | Chinese parent company (brand risk); 2-application limit across TikTok/ByteDance; OA required |
| **Global** | **4.0/5** | Strong security+AI match; apply after Anthropic Fellows deadline (April 26) and ByteDance #388 |

---

## Archetype: Cybersecurity / Security Intern — AI/LLM Security

**Team mission:** Build infrastructure, platforms, and technologies to protect TikTok's users, products, and infrastructure. Focus on AI-native security tooling, LLM integration security, and SDLC security review.

**Key responsibilities:**
- Participate in security assessments including pentesting Web and mobile applications
- Tooling development with security focus: code review and API testing tools
- Tools developed will specifically benefit LLM integration (MCP, API security)
- Build Evals, harnesses, and optimizations for AI security tooling
- Improve LLM usage in the SDLC process
- Enhance infrastructure security via AI-assisted workflows

---

## Carlos's Fit — Evidence From CV

### Primary matches

**Adversarial LLM Testing** (`cv.md`):
> "Conducted adversarial prompt injection testing against uncensored LLM models, testing multiple system prompt bypass techniques including fake model identity, developer mode simulation, and leaked transcript framing"

This is the single most direct qualification match. The role explicitly mentions "Evals, harnesses, and optimisations on existing AI tooling & systems for Security Review" — which is exactly adversarial LLM evaluation. Carlos has hands-on experience here.

**Security tooling development** (`cv.md`):
> "Defense-in-depth security: CORS origin restrictions, request ID tracing with sanitization, LaTeX injection prevention, PII-safe Sentry error tracking, honeypot/financial field detection, CSP lockdown, and sensitive storage key purging on logout"
> "Engineered a stateless OAuth proxy (Google + GitHub) with HMAC-SHA256 CSRF protection and timing-safe signature verification"

Production security tooling, not just theory.

**LLM pipeline engineering** (`cv.md`):
> "Built a multi-model AI pipeline orchestrating 5 LLM providers (Claude Sonnet for profile enrichment, DeepSeek V3.2 for content generation, Gemini Flash Lite for filtering, GPT-4o-mini for cover letters)"
> "Two-pass LLM enrichment pipeline... with deterministic validation gates and automatic retry with temperature reduction on failure"

Understanding of LLM failure modes, validation, and production behavior is essential for building LLM security tooling.

**Distributed tracing** (`cv.md`):
> "Implemented distributed tracing with trace IDs propagating across Chrome extension content script, service worker, and backend, with field-level verification"

Understanding of request tracing across complex systems = relevant for API security testing and monitoring.

### Qualifications check

| Requirement | Status |
|-------------|--------|
| Undergraduate/Postgraduate in CS/CE/InfoSystems/STEM | ✅ CS major TAMU, cybersecurity minor |
| Security engineering experience (threat modeling, pentesting, tooling, privacy) | ✅ Adversarial LLM testing; HMAC/TLS/CORS/CSP in prod; security automation |
| Programming: JS/Node.js, Go, Python, Java, C++, Rust | ✅ Python (primary), TypeScript/JS, Rust |
| 3-month internship commitment | ✅ Summer standard |

---

## TikTok Application Limit Note

TikTok/ByteDance allows a maximum of 2 applications per candidate across all entities. If Carlos applies to ByteDance Security Assurance (#388), this would be his second application. Plan carefully:
- **Option A:** ByteDance Security Assurance (#388, 4.3/5) + TikTok Product Security (#392, 4.0/5) — both security roles, strong consistency
- **Option B:** TikTok Product Security (#392, 4.0/5) only — preserves second slot for a higher-scored ByteDance role if found

**Recommendation:** Apply to both #388 and #392. They are complementary security tracks and the 2-application limit covers both.

---

## Comp Analysis

$45-60/hr × 12 weeks × 40 hrs = $21,600 – $28,800 for the summer.
Annualized: $94K – $125K equivalent.

This is below Carlos's $80-120K target salary range but appropriate for an intern comp structure. The experience at ByteDance/TikTok (major tech company, real security work, AI-first culture) is high value for the resume.

---

## Red Flags / Risks

1. **Chinese parent company (ByteDance):** Future US government security clearance could be affected. Not a short-term blocker but worth considering long-term career trajectory.
2. **Online Assessment (OA):** Technical screening required. Prepare LeetCode medium + security concepts + LLM system design.
3. **2-application limit:** Shared with ByteDance #388 — plan applications accordingly.

---

## Recommended Application Strategy

1. **Apply after Anthropic Fellows (deadline April 26)** — don't let this distract from the higher-priority application
2. **Lead with:** Adversarial LLM Testing project + Finch LLM pipeline security
3. **Cover letter hook:** "I've already built and tested adversarial LLM pipelines in production — I want to apply that to securing TikTok's AI systems."
4. **Resume:** Adversarial LLM Testing → Finch security stack → cybersecurity minor → multi-model AI pipeline
5. **Prepare for OA:** LeetCode medium, security-aware system design, LLM evaluation concepts

---

## Strategic Note

This role and ByteDance Security Assurance (#388) are the strongest security+AI match pair Carlos has found in 144 scans. The adversarial LLM testing project is a genuine differentiator — very few interns can say they've systematically tested LLM bypass techniques. Apply to both.
