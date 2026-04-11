# Scan Summary — 2026-04-11 (v33)

**Agent:** Autonomous career-ops scanner
**Date:** 2026-04-11
**Scan Version:** v33
**Coverage:** 40+ companies and portals
**Previous Scan:** v32 (2026-04-11, earlier session — Transcarent, Planet Labs, YC companies)

> _This summary supersedes v32. See data/scan-summaries/ for previous summaries._

---

## Portals Scanned

| Portal | Method | Companies Checked |
|--------|--------|-------------------|
| Greenhouse API | WebFetch | Cloudflare, Glean, Together AI, Zscaler, Figma, Intercom, Temporal, RunPod, Okta |
| Ashby | WebSearch | Cohere, Notion, Farsight AI |
| Lever | WebSearch | Palantir, Weights & Biases, Voleon Group |
| Direct WebSearch | WebSearch | Google, Microsoft, Amazon, Meta, Stripe, Databricks, Figma, Snowflake, Shopify, ByteDance, Netflix, Palo Alto Networks, Deloitte, Accenture, McKinsey, Zscaler, Okta, IBM, Citadel, Two Sigma |
| YC/Other | WebSearch | Farsight AI, iCapital |

---

## New Listings Found

**Total new listings:** 37
**Added to scan history:** 37 entries (scan-v32 tag in history)
**Skipped (closed/expired):** 9 (Okta interns 404, Databricks 404, Shopify private, Cloudflare London roles)
**Skipped (no intern roles):** 5 (Temporal, RunPod, Intercom, W&B, n8n)
**Full reports written:** 3

---

## Top Matches (Score >= 4.0)

### 1. Cloudflare — Software Engineer Intern (Summer 2026) | Score: 4.8/5
**URL:** https://job-boards.greenhouse.io/cloudflare/jobs/7206269
**Report:** [293](reports/293-cloudflare-swe-intern-2026-04-11.md)
**Location:** Austin, TX (in-office 3-5 days/week)
**Comp:** ~$40-55/hr (estimated)
**Why #1:** Carlos built a **production Cloudflare Workers edge API gateway** with Hono for Finch — applying to work at the company whose exact stack he already shipped to production. Optional fast-track AI assignment (LLM + Workflows + memory) can be answered immediately with existing ApplyEasy code.
**Action:** Apply today + submit fast-track assignment

### 2. Cloudflare — Security Engineer Intern (Summer 2026) | Score: 4.7/5
**URL:** https://job-boards.greenhouse.io/cloudflare/jobs/7582150
**Report:** [294](reports/294-cloudflare-security-intern-2026-04-11.md)
**Location:** Austin, TX (LOCAL required — no relocation assistance)
**Comp:** ~$40-55/hr (estimated)
**Why #2:** Perfect archetype match — cybersecurity minor + HMAC-SHA256 CSRF + timing-safe auth + TLS 1.2/1.3 + OAuth proxy + adversarial LLM testing. Joins Cyber Defense & Engineering team. "Local Austin" manageable from College Station.
**Action:** Apply today, confirm Austin summer housing

### 3. Together AI — Software Engineer Intern (Summer 2026) | Score: 4.5/5
**URL:** https://job-boards.greenhouse.io/togetherai/jobs/5012768007
**Report:** [295](reports/295-together-ai-swe-intern-2026-04-11.md)
**Location:** San Francisco, CA (on-site HQ)
**Comp:** $58/hr (confirmed — top quartile)
**Why #3:** Top-3 AI infra company for model serving. Carlos's 5-provider inference routing ($0.003/app) maps to Platform Engineering track. $58/hr = ~$121K annualized — exceeds comp target.
**Action:** Apply soon, express preference for Platform Engineering or Infrastructure track

---

## All New Listings Added to Pipeline (v33 section)

| Priority | Company | Role | Score |
|----------|---------|------|-------|
| APPLY NOW | Cloudflare | SWE Intern – Austin TX | 4.8 |
| APPLY NOW | Cloudflare | Security Intern – Austin TX | 4.7 |
| APPLY SOON | Together AI | SWE Intern | 4.5 |
| This week | Palantir | FDSE Commercial Intern | 3.9 |
| This week | Stripe | SWE Intern (Summer) | 3.8 |
| This week | Stripe | New Grad SWE | 3.8 |
| This week | Zscaler | AI/ML Intern, Agentic Cloud | 3.8 |
| This week | Glean | SWE, AI & Security | 3.8 |
| This week | Palo Alto Networks | SWE Intern | 3.8 |
| This week | The Voleon Group | SWE Intern | 3.8 |
| Later | Cohere | SWE Intern (Spring/Summer) | 3.7 |
| Later | Notion | SWE AI Intern | 3.7 |
| Later | Amazon | SWE Intern (US) | 3.7 |
| Later | Microsoft | SWE Intern | 3.7 |
| Later | Together AI | New Grad SWE | 3.8 |
| Later | Glean | SWE University Grad | 3.7 |
| Later | Cloudflare | Data Engineer Intern – Austin TX | 3.8 |
| Low | ByteDance | Security SWE Intern (Network Sec) | 3.5 |
| Low | ByteDance | SWE Intern (AI Platform) | 3.5 |
| Low | Snowflake | Solution Engineer Intern (TX Remote) | 3.5 |
| Low | Netflix | SWE Intern, Content Eng | 3.6 |
| Low | Glean | Cloud Security Engineer (Remote) | 3.6 |
| Low | Farsight AI | SWE Intern | 3.5 |
| Low | Sigma Computing | AI/ML Grad Eng Intern | 3.4 |

**Confirmed closed/expired:** Databricks, Shopify, Okta AI/SRE Interns, Cloudflare London roles, Figma intern

---

## Recommended Next Actions

### Immediate (today)
1. **Apply to Cloudflare SWE Intern (Austin TX)** — build the optional AI fast-track assignment using ApplyEasy/Finch. Create a `cf_ai_` GitHub repo with README + prompt docs. This is the single highest-value action in the entire pipeline.
2. **Apply to Cloudflare Security Intern (Austin TX)** — cover letter: lead with OWASP mitigations in Finch (CSRF, TLS, OAuth proxy, CSP). Confirm Austin availability.
3. **Apply to Together AI SWE Intern** — indicate Platform Engineering or Infrastructure track. Emphasize multi-model inference routing and API platform work.

### This Week
4. Evaluate Transcarent Identity Intern (pipeline v32 entry, score 4.0).
5. Apply to Palantir FDSE Commercial Intern (FDSE = "deployed AI to 50+ ATS platforms" maps perfectly).
6. Apply to Stripe SWE Intern.

### Next Round (lower priority)
7. Voleon Group — quant trading background is a unique differentiator.
8. Amazon SWE Intern — still open in April, rolling hiring.
9. Palo Alto Networks — cybersecurity angle strong.

---

## Portals to Add to portals.yml

- **Cloudflare** (Greenhouse: `cloudflare`) — should be in portals.yml for future scans. Has Austin TX intern roles in SWE, Security, Data Engineering, Research, Red Team.
- **Netflix** (jobs.netflix.com) — has intern program, currently open.
- **Okta** (okta.com/company/careers) — intern program was open earlier; will repost.

---

*Generated by autonomous scanner — 2026-04-11 v33*
