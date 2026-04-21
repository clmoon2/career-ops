# Evaluation Report #389 — Verkada Security Software Engineer, University Graduate 2026

**Date:** 2026-04-20
**Score:** 4.1/5
**URL:** https://job-boards.greenhouse.io/verkada/jobs/4872797007
**Status:** Evaluada
**PDF:** ❌

---

## Position Summary

| Field | Details |
|-------|---------|
| Company | Verkada |
| Role | Security Software Engineer — University Graduate 2026 |
| Location | San Mateo, CA (on-site) |
| Comp | $148K–218K total (base ~$110-140K + RSUs) |
| Type | Full-time new grad FTE |
| Target Grad | 2026 graduates — ⚠️ Carlos graduates Fall 2027 |
| Deadline | Rolling |
| Archetype | Cybersecurity / Security Intern → Security SWE FTE |

---

## Offer Verification

**Verification:** active — confirmed listed on job-boards.greenhouse.io/verkada as of 2026-04-20.

---

## Score Breakdown

| Dimension | Score | Notes |
|-----------|-------|-------|
| CV Match | 4.5/5 | HMAC/TLS/OAuth/CORS/CSP production implementation = direct match; distributed systems; Python/TS |
| North Star | 4.0/5 | Security SWE FTE at physical security company — aligns with security archetype but slightly off primary track (internship focus) |
| Comp | 5.0/5 | $148-218K total for new grad; top quartile; strong RSU component |
| Cultural | 4.0/5 | Scrappy growth company; SF Bay; in-person culture; security-first product |
| Red Flags | -1.0 | **Critical: Carlos graduates Fall 2027 — "University Graduate 2026" likely means graduating 2026; eligibility uncertain** |
| **Global** | **4.1/5** | Excellent comp + CV match; graduation date eligibility must be confirmed before applying |

---

## Archetype: Security Software Engineer (New Grad FTE)

Verkada builds physical security hardware (cameras, access control, alarms) with a cloud-connected software platform. The security software engineering team works across the full stack to build and harden systems that handle 100K+ devices globally.

**Key responsibilities (inferred from role profile):**
- Build and maintain security features across the Verkada platform
- Scalable distributed systems handling high traffic from 100K+ deployed devices
- High-concurrency key-value storage systems (Redis, DynamoDB)
- Collaborate cross-functionally on security architecture
- Contribute to Verkada's defense-in-depth security posture

---

## Carlos's Fit — Evidence From CV

### Primary technical matches

**Security implementation at production scale** (`cv.md`):
> "HMAC-SHA256 CSRF protection and timing-safe signature verification (hmac.compare_digest)"
> "TLS 1.2/1.3 with ECDSA certificates and Mozilla-recommended cipher suites, enforcing HTTP-to-HTTPS redirects and disabling session tickets for forward secrecy"
> "CORS origin restrictions, request ID tracing with sanitization, LaTeX injection prevention, CSP lockdown"

All implemented in a live production system serving real users — not homework.

**Distributed systems and backend scale** (`cv.md`):
> "PostgreSQL admission control system with PL/pgSQL stored functions using row-level locking for race-condition-safe pipeline quota enforcement"
> "Cloudflare Workers edge API gateway with Hono proxying 20+ endpoints, OAuth redirect handling preventing edge cache poisoning, S3 signed URL server-side streaming"

Verkada's need for high-concurrency distributed systems maps directly to Carlos's production AWS/Cloudflare/PostgreSQL work.

**Full-stack production systems** (`cv.md`):
> "35,800-line Python codebase serving 46 API routes across a multi-model AI pipeline"
> "Blue/green CI/CD on AWS EC2 with ALB routing, ECR image management, automated smoke testing"

### Qualifications check

| Requirement | Status |
|-------------|--------|
| BS in CS/CE or related | ✅ CS major TAMU, cybersecurity minor |
| Security software engineering experience | ✅ Production HMAC/TLS/OAuth/CORS/CSP implementation |
| Distributed systems | ✅ AWS EC2, Cloudflare Workers, PostgreSQL, Docker |
| Programming (Python, TypeScript, systems) | ✅ Python (primary), TypeScript, Rust, C |
| **Graduation date: 2026** | ⚠️ Carlos graduates Fall 2027 — may not qualify for "University Graduate 2026" |

---

## Red Flags / Risks

1. **Graduation date eligibility (CRITICAL):** "University Graduate 2026" at Verkada typically targets students graduating May–December 2026. Carlos graduates Fall 2027. Must email recruiter or check FAQ before applying.
2. **On-site in San Mateo, CA:** Requires relocation from College Station, TX. Carlos noted openness to relocation.
3. **Not an internship:** This is a full-time FTE role. Accepting this would end the job search and require immediate commitment.

---

## Recommended Action

1. **Before applying:** Confirm graduation date eligibility. Email Verkada recruiting or check application form for eligibility requirements.
2. If eligible: Apply immediately — $148-218K comp for a security role with this exact technical match is exceptional.
3. **CV framing:** Lead with security stack (HMAC/TLS/OAuth/CORS/CSP from Finch), distributed systems (AWS/Cloudflare/PostgreSQL), and the adversarial LLM testing project.

---

## Note on Report Timing

This role was identified in scan v141 (2026-04-20) by the autonomous scan agent. The evaluation was captured in the tracker on April 20 but the report file was not created at that time. This report reconstructs the evaluation from available data as of 2026-04-21.
