# Portal Scan — 2026-04-24 (v175)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Scan version:** v175 (autonomous agent)
**Prior scan:** v174 (same day — 2 new listings found: Julius AI 4.2/5 + Point72 IS 4.1/5)
**Cumulative scans:** 175 total since v1 (2026-04-05)

---

## Stats

| Metric | Count |
|--------|-------|
| Companies / sources checked | 25+ |
| WebSearch queries executed | 15+ |
| New URLs found | 0 |
| v174 pipeline items evaluated | 4 |
| New evaluated >= 4.0/5 | 1 (from pipeline) |
| Scan history total | ~3,722 entries |

---

## Sources Checked

- Greenhouse APIs: All returning 503 (server unavailable); fallback to WebSearch confirmed all dup
- Ashby broad: All tracked companies — all confirmed dup v7-v174
- Lever broad: All tracked companies — all confirmed dup v7-v174
- SimplifyJobs Summer2026 README: all dup v174 (Nutanix/IEM/ABB/HelloFresh/Tencent)
- SpeedyApply SWE repo: all dup v172+ (BlackSky/Kognitos/Ripple/Zoox)
- SpeedyApply AI repo: all PhD-focused or below threshold (Meta Audio/Adobe/Roblox/NVIDIA)
- jobright-ai New Grad README: all dup v172+ (Cohu/Navan/NVIDIA SQA/Affirm)
- YC internships + Work at a Startup: all confirmed dup v30-v174
- Targeted company checks: Stripe (no SWE intern), Rubrik (closed Mar 13), Lacework (404), Tesla (all closed/below), Capital One (in pipeline v136), IBM (non-Greenhouse, consulting domain), Wiz (no intern), ByteDance (below threshold), DV Trading (below threshold)

---

## Evaluated v174 Pipeline Items

| Company | Role | Score | Result |
|---------|------|-------|--------|
| **1Password** | Developer Intern - Client Secrets Management | **4.0/5** | ✅ EVALUATED — report #407 |
| 1Password | Developer Intern - Insights | 3.5/5 | Below threshold — skip |
| ByteDance | SWE Intern (AI Platform) | 3.2/5 | Below threshold — ML infra/CV domain mismatch |
| Julius AI | SWE - Infrastructure & Security | 2.0/5 | Mid-senior FTE — not intern/new grad; skip |

---

## New Listing >= 4.0/5

### #407 — 1Password | Developer Intern - Client Secrets Management (Summer 2026)
- **Score:** 4.0/5
- **URL:** https://jobs.ashbyhq.com/1password/2271dd32-0d1a-4014-b6c8-21b22b630705
- **Report:** [407](reports/407-1password-developer-intern-client-secrets-mgmt-2026-04-24.md)
- **Comp:** ~$31–38/hr estimated | Remote US/CA | May–August 2026 (4 months)
- **Why:** HMAC-SHA256 CSRF protection + TLS 1.2/1.3 ECDSA + OAuth proxy + sensitive storage key purging at Finch = direct cryptographic analog to secrets management. 4th qualifying 1Password track.
- **Context:** Apply after Extension Excellence #366 (4.3/5). All four 1Password tracks are worth applying to; Extension Excellence is the primary pick.

---

## Market Signal

**SATURATED.** This is the 5th autonomous scan on April 24, 2026 (v171–v175). Summer 2026 intern market is at peak saturation:
- Major tech companies opened applications Aug–Dec 2025; deadlines Jan–Mar 2026
- Remaining open listings are late-closing programs, relisted roles, or small companies
- All major ATS portals (Greenhouse, Ashby, Lever) returning dup results consistently across 5 sequential scans

**Recommendation:** Next scan on **May 1–3, 2026** when:
- Fall 2026 intern cycles may open
- New 2027 new grad roles from top companies appear
- Some Summer 2026 programs post late openings after yield day

---

## URGENT DEADLINE (48 hours)

**APRIL 26 = TOMORROW**: Anthropic Fellows Program deadlines
- **AI Security Track #246 — 4.7/5** — [APPLY NOW via Constellation program](https://constellation.org) — adversarial LLM red teaming = perfect match; $3,850/wk + $15K compute; 4-month Jul 20 start
- **AI Safety Track #370 — 4.2/5** — APPLY NOW
- **ML Systems Track #372 — 4.1/5** — APPLY NOW

---

## Full Priority Queue (all confirmed open, sorted by score)

| Score | # | Company | Role | Notes |
|-------|---|---------|------|-------|
| 4.8 | #347 | Cloudflare | SWE Intern | Austin TX local |
| 4.7 | #294 | Cloudflare | Security Intern | Austin TX local — no relocation |
| 4.7 | #246 | Anthropic | Fellows AI Security | ⚡ DEADLINE APRIL 26 |
| 4.7 | #143 | Palantir | FDSE New Grad | $145-180K + RSUs |
| 4.7 | #298 | Haize Labs | SWE Intern | $100-125K NYC |
| 4.6 | #304 | Mechanize | SWE Intern | $100/hr SF |
| 4.5 | #353 | OpenAI | SWE Intern | SF/Seattle $60/hr |
| 4.5 | #334 | Together AI | Security Intern | SF $58/hr |
| 4.5 | #295 | Together AI | SWE Intern | SF $58/hr |
| 4.5 | #340 | Glean | SWE Intern | Palo Alto $57-69/hr |
| 4.5 | #341 | Ramp | FDE Intern | $11K/mo NYC/SF |
| 4.5 | #355 | Atlassian | Security Intern | Seattle $49-75/hr |
| 4.4 | #357 | Browser Use | SWE Intern | YC $6-16K/mo SF |
| 4.4 | #305 | Decagon | Agent SWE Intern | SF agentic AI |
| 4.3 | #366 | 1Password | Extension Excellence | Remote Chrome MV3 |
| 4.3 | #274 | Sierra | Agent Dev Intern | SF multi-agent |
| 4.3 | #344 | Dex | AI/ML Intern | YC SF $6-10K/mo |
| 4.2 | #405 | Julius AI | SWE Product New Grad | SF $130-150K |
| 4.0 | #407 | 1Password | Client Secrets Mgmt | Remote security 🆕 |

---

## Recommended Next Actions

1. **TONIGHT/TOMORROW:** Apply to Anthropic Fellows AI Security (#246) — DEADLINE APRIL 26
2. **This week:** Apply to Cloudflare Security Intern #294 (Austin TX, no relocation required)
3. **This week:** Apply to Haize Labs SWE Intern #298 ($100-125K, adversarial LLM = perfect)
4. **Run `/career-ops pipeline`** to evaluate remaining pipeline items (C3 AI/Nutanix/Cresta FDE/Capital One Cyber/Snyk Container)
5. **Next scan:** Schedule for May 1–3, 2026

→ Run `/career-ops pipeline` to process pending URLs from the inbox.
