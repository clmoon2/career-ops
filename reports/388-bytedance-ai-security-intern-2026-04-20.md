# Evaluation Report #388 — ByteDance Security Software Engineer Project Intern (Security Assurance)

**Date:** 2026-04-20
**Score:** 4.3/5
**URL:** https://joinbytedance.com/search/7592416621414205701
**Status:** Evaluada
**PDF:** ❌

---

## Position Summary

| Field | Details |
|-------|---------|
| Company | ByteDance |
| Role | Security Software Engineer Project Intern (Security Assurance) - 2026 Start (BS/MS) |
| Location | San Jose, CA (on-site) |
| Comp | $45–60/hr |
| Duration | 3 months minimum |
| Start Dates | May 11, 18, 26; June 8, 22, 2026 (rolling) |
| Deadline | Rolling — apply ASAP |
| Archetype | Cybersecurity / Security Intern |

---

## Offer Verification

**Verification:** active — confirmed listed on joinbytedance.com, Glassdoor, and SimplifyJobs as of 2026-04-20. Rolling deadline.

---

## Score Breakdown

| Dimension | Score | Notes |
|-----------|-------|-------|
| CV Match | 4.5/5 | Adversarial LLM Testing project = exact match; HMAC-SHA256/TLS/OAuth/CORS from Finch; cybersecurity minor |
| North Star | 4.5/5 | Primary archetype: Cybersecurity/Security Intern — direct hit |
| Comp | 4.0/5 | $45-60/hr; midpoint $52.50 is within target range |
| Cultural | 3.0/5 | Chinese parent company (ByteDance) — brand risk for future US clearance or employers; otherwise strong AI-first culture |
| Red Flags | -0.5 | ByteDance brand risk (Chinese parent); 3-month minimum commitment; OA required |
| **Global** | **4.3/5** | Strong technical match; recommend applying |

---

## Archetype: Cybersecurity / Security Intern

**Team mission:** Build security infrastructure, platforms, and technologies to protect ByteDance users, products, and infrastructure. Focus on offensive security, AI-assisted attack and defense, and penetration testing.

**Key responsibilities:**
- Work with senior engineers on security posture assessment across ByteDance products
- AI-driven attack and defense research (adversarial LLM, AI security assessments)
- Apply AI techniques to enhance security operations
- Offensive security, threat emulation, penetration testing, red team activities
- Security assessments of AI systems

---

## Carlos's Fit — Evidence From CV

### Primary matches

**Adversarial LLM Testing** (`cv.md`):
> "Conducted adversarial prompt injection testing against uncensored LLM models, testing multiple system prompt bypass techniques including fake model identity, developer mode simulation, and leaked transcript framing"

This is a direct match to the team's focus on AI-driven attack research and LLM security assessments.

**Security engineering depth from Finch** (`cv.md`):
> "HMAC-SHA256 CSRF protection, timing-safe signature verification (hmac.compare_digest), bypassing Texas A&M's Cisco Umbrella enterprise firewall"
> "Defense-in-depth security: CORS origin restrictions, request ID tracing with sanitization, LaTeX injection prevention, PII-safe Sentry error tracking, honeypot/financial field detection, CSP lockdown"
> "TLS 1.2/1.3 with ECDSA certificates and Mozilla-recommended cipher suites, enforcing HTTP-to-HTTPS redirects, disabling session tickets for forward secrecy"

Production security implementation at the protocol/application layer = directly transferable to a security assurance role.

**Multi-model AI pipeline** (`cv.md`):
> "Built a multi-model AI pipeline orchestrating 5 LLM providers (Claude Sonnet, DeepSeek V3.2, Gemini Flash Lite, GPT-4o-mini) with cost optimization"

Fluency in LLM systems + adversarial testing = rare intern-level combination that this team explicitly wants.

### Qualifications check

| Requirement | Status |
|-------------|--------|
| BS/MS in CS/CE/InfoSystems/STEM | ✅ CS major, TAMU |
| Security engineering experience (threat modeling, pentesting, tooling) | ✅ Adversarial LLM testing, HMAC/TLS/CORS/CSP in prod |
| Programming (Python, Go, Java, JS, C++, Rust) | ✅ Python (primary), Rust, TypeScript |
| CTF/bug bounty/security research | ⚠️ No formal CTF; adversarial LLM testing is equivalent |
| Cloud/container security | ✅ AWS EC2, Docker, nginx in prod |
| 3-month minimum commitment | ✅ Summer internship standard |

---

## Red Flags / Risks

1. **ByteDance/Chinese parent company:** Career risk for future US government work or security clearance. Carlos should weigh this against his long-term goals. Not a blocker now but worth noting.
2. **Online Assessment (OA) required:** Technical screening before review. Standard for ByteDance — prepare LeetCode medium + security concepts.
3. **2-application limit across ByteDance/TikTok entities:** Carlos should count this against his TikTok Product Security application (#392). Only 2 total allowed.

---

## Recommended Narrative / Framing

**Lead with:** Adversarial LLM Testing project — prompt injection + bypass techniques against uncensored models. This is literally what the AI security team does.

**Secondary:** Finch security stack — HMAC-SHA256, TLS hardening, OAuth proxy, distributed tracing. Production implementation, not coursework.

**Cover letter hook:** "I've already tested adversarial prompt injection against LLM models in production — I want to do it at ByteDance's scale."

---

## Next Actions

1. ⚠️ **APPLY ASAP** — rolling deadline, competitive OA process
2. Confirm this doesn't exceed the 2-application limit (counting TikTok #392)
3. Prepare for OA: LeetCode medium-hard (arrays/graphs/DP) + security fundamentals
4. Customize CV: lead with Adversarial LLM Testing project, Finch security stack
