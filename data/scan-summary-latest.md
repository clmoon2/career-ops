# Portal Scan — 2026-04-14 (scan-v63)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Run:** scan-v63 (autonomous agent)
**Date:** 2026-04-14

---

## Results

```
Portals / companies scanned:   42
Search queries executed:        25+
Total new URLs encountered:      8 (not previously in history)
Passed title filter (US-based):  1
Passed score threshold (≥3.0):   0
Added to pipeline.md:            0
Full reports written (≥4.0):     0
New history entries added:      15
History total:                1,901 entries
```

---

## Companies Scanned

### Greenhouse API direct checks
| Company | Result |
|---------|--------|
| Arize AI | No intern roles (32 FTE-only positions) |
| Temporal | No jobs listed (0 positions) |
| RunPod | No intern roles (all FTE) |

### New findings (not in history)
| Company | Title | Score | Disposition |
|---------|-------|-------|-------------|
| Deloitte | GPS Summer Scholar – Tech Packages | 2.5/5 | `skipped_score` — enterprise SAP/Oracle impl, 50% travel, not Carlos's stack |
| Pure Storage | SW Engineer – Summer 2026 Internship | — | `skipped_location` — Prague, Czech Republic |
| Cloudflare | Solutions Engineer Intern (Summer 2026) | — | `skipped_location` — Lisbon, Portugal (requires PT work auth) |
| Chainguard | Software Engineer Intern (Packaging) | — | `skipped_closed` — 404, listing removed |

### Companies confirmed no new roles (all in history)
CrowdStrike · Palo Alto Networks · SentinelOne · Datadog · Okta · Confluent · Databricks · MongoDB · Viam · Stripe · Palantir (all roles) · Schonfeld · MEMX · Together AI · Verisign · Dark Wolf Solutions · Gemini · Semgrep · Salesforce · Anduril · NVIDIA · Roblox · Zendesk · Axon (US) · Zscaler (all roles) · Brain Co · HPIQ · CLEAR · Handshake · WeRide · Accenture · Notion · Cohere · Giga · Ramp · Farsight · Sigma Computing · Cloudflare (SWE Austin) · SpaceX

---

## Score Rationale — Deloitte GPS Summer Scholar (2.5/5)

**Role:** Deloitte Consulting LLP — Government & Public Services — Summer Scholar — Tech Packages
**Location:** Arlington/Rosslyn, VA | **Comp:** $38/hr | **Target grad:** Spring/Summer 2027

Why low score:
- "Tech Packages" = enterprise software implementation (SAP, Oracle, Workday, ServiceNow). Carlos's stack is Python/React/AWS/LangChain — no enterprise package experience.
- 50% travel requirement unusual for an intern.
- Government consulting trajectory diverges from Carlos's AI/SWE/security target path.
- Security clearance requirement adds process burden.

**Recommendation:** Do not apply. Score 2.5/5 is well below the 4.0 threshold.

---

## Context — Late-Cycle Market

This is scan v63, the fourth scan run on 2026-04-14. Scans v60–v62 (earlier today) already swept:
- All portals.yml companies (Greenhouse APIs + Ashby direct + Lever direct)
- 60+ WebSearch queries across Greenhouse/Ashby/Lever/YC/SimplifyJobs
- Curated lists (SimplifyJobs, speedyapply GitHub)

The summer 2026 intern market is at **late-cycle**: most top-tier companies have filled their summer cohorts. Remaining openings are niche, location-constrained, or lower-fit.

---

## Active Pipeline (from prior scans — still open)

| Score | Company | Role | Priority |
|-------|---------|------|----------|
| ~3.7/5 | Zscaler | Software Engineer Intern, Software Development (Summer 2026) | Pending review |
| ~3.7/5 | Lenovo | AI Application Development Intern (Summer 2026) | Pending review |
| ~3.3/5 | Hootsuite | Co-op/Intern, Internal AI Operations (Summer 2026) | ⚠️ URGENT — interview window April 14–24 |

---

## Recommended Next Actions

1. **Hootsuite is URGENT** — interview window closes April 24. Review the pipeline entry and decide now.
2. **Evaluate Zscaler** — strong cybersecurity brand, Python/AWS/Docker/React match, San Jose hybrid, $45–65/hr. Run `/career-ops` on that URL.
3. **Evaluate Lenovo** — LangChain/RAG/Python match, posted April 6 (fresh). Run `/career-ops` on that URL.
4. Consider scanning for **fall 2026 co-ops** and **2027 summer early applications** (open Oct–Nov 2026).
5. Run `/career-ops scan` again in 3–5 days to catch late-posted roles.
