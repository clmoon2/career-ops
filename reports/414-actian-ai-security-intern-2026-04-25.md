# Actian Corporation — AI Security Intern

**Score:** 4.0/5
**URL:** https://jobs.lever.co/actian/21624589-9c91-48ca-bce7-ba4d0bb9a868
**PDF:** ❌
**Date:** 2026-04-25
**Status:** Evaluada

---

## Company

Actian Corporation is an enterprise data management and integration company (Actian Vector, Actian DataConnect, Avalanche cloud data warehouse). Legacy tech pedigree — founded from Ingres/Relational Technology lineage, now focused on hybrid cloud data management. Not an AI-native company, but actively building AI security capability internally. HQ in Palo Alto CA.

## Role

12-week internship, **starts June 8, 2026**. **Primarily remote** — includes an onsite orientation at Austin, TX (travel covered by Actian). Responsibilities:

- Research AI security threats: prompt injection, data leakage, model misuse — aligned with OWASP Top 10 for LLMs
- Hands-on AWS Bedrock: test multiple foundation models, evaluate outputs, document behavior across use cases
- Design and implement AI security controls: guardrails, input/output validation, monitoring strategies
- Capstone: **end-to-end red team vs. blue team testing**, final presentation + AI Acceptable Use Policy draft

Requirements: CS/Cybersecurity/Information Systems degree (in progress); AWS foundational knowledge; general security concepts. Nice-to-haves: LLM/prompt engineering exposure, adversarial testing interest.

---

## Evaluation

### A — Match con CV (4.3/5)

- **Prompt injection / adversarial LLM testing ✅** — Carlos built a dedicated LLM Adversarial Testing project: "Conducted adversarial prompt injection testing against uncensored LLM models, testing multiple system prompt bypass techniques including fake model identity, developer mode simulation, and leaked transcript framing." This is the exact red team methodology the capstone describes.
- **OWASP Top 10 for LLMs ✅** — Defense-in-depth production security in Finch (CORS, CSP, LaTeX injection prevention, HMAC-SHA256 CSRF, PII-safe Sentry) demonstrates applied security thinking that maps directly to OWASP LLM controls.
- **AWS ✅** — Finch runs blue/green CI/CD on AWS EC2 with ALB routing, ECR image management, GitHub Actions workflows.
- **Cybersecurity minor ✅** — Explicit archetype signal. Coursework: Computer Security, OS security.
- **LLM evaluation ✅** — ATS scoring engine (785 keywords, 417 aliases, quality floor) = Carlos's own eval framework for LLM output; Finch uses deterministic validation gates on generated content.
- **Guardrails / input-output validation ✅** — Finch validates LLM output with retry + temperature reduction on failure; LaTeX injection prevention in production.
- **Foundation models / multi-model pipeline ✅** — Claude Sonnet, DeepSeek V3.2, Gemini Flash Lite, GPT-4o-mini orchestrated in a 7-stage pipeline. Direct AWS Bedrock analogy.

### B — North Star alignment (4.3/5)

- **Archetype:** Cybersecurity / Security Intern — primary archetype per `config/profile.yml`
- AI + Security dual archetype = the exact space Carlos is targeting
- The capstone (red team vs. blue team LLM testing) is a standout deliverable — concrete, resumable, and directly relevant to AI red-teaming roles at AI labs
- Remote role removes relocation barrier; Austin orientation is College Station TX → Austin (2.5hr drive — trivially easy)

### C — Comp (2.5/5 — estimated)

- Compensation not publicly listed.
- Actian is a legacy enterprise data company, not a funded AI startup.
- Estimate: **$22–35/hr** based on company stage and legacy enterprise norms.
- Below the $70K minimum ($34/hr) target — verify before accepting.
- **This is the key risk.** Confirm comp before committing.

### D — Cultural signals (3.3/5)

- Not an AI-native company; data integration / warehouse is the core business
- Building AI security capability internally (AI Acceptable Use Policy, guardrails work)
- Remote-first for this role = good for Carlos's flexibility
- Austin orientation = Texas familiarity, minimal disruption
- Lower brand recognition in AI/security space vs. Anthropic, Cloudflare, Snyk, etc.

### E — Red flags

- **Comp undisclosed / likely below floor**: Must confirm before accepting. Hard reject if below $34/hr.
- **Company brand**: Actian doesn't carry prestige in the AI/security space. Resume value is the specific work (LLM red teaming, OWASP LLM security), not the company name.
- **Legacy company culture**: Potential mismatch with Carlos's startup/builder energy — 6-person teams, fast iteration.

---

## Global: 4.0/5

**Recommendation: Apply — verify comp first.**

Carlos's LLM Adversarial Testing project is a verbatim match for this role's core deliverable (red team vs. blue team LLM testing, prompt injection, model misuse). The Cybersecurity minor + Finch's production security stack (HMAC-SHA256, CORS, CSP, LaTeX injection prevention) make this an authentic fit, not a stretch.

The remote location + Austin orientation makes this logistics-trivial for Carlos (College Station is 2.5 hours from Austin). The only real risk is comp — Actian is a legacy company that may underpay relative to AI-native startups.

**Verify comp first. If ≥ $34/hr, apply.** The specific LLM red-teaming experience is valuable regardless of company brand.

**Lead proof point:** "Built a dedicated LLM Adversarial Testing project covering prompt injection, fake model identity, developer mode simulation, and leaked transcript framing — the exact adversarial methodology your capstone describes. Also shipped production AI security controls: HMAC-SHA256 CSRF, LaTeX injection prevention, and multi-layer input validation in a live pipeline processing 100+ jobs/day."
