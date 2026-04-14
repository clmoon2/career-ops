# Portal Scan — 2026-04-14 (scan-v63)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Run:** scan-v63 (combined — two parallel autonomous agents)
**Date:** 2026-04-14

---

## Results

```
Portals / companies scanned:   45+
Search queries executed:        40+
Total new URLs encountered:     ~12 (not previously in history)
Passed title filter (US-based):  1
Passed score threshold (≥3.0):   0
Added to pipeline.md:            0
Full reports written (≥4.0):     0
New history entries added:      24
History total:                ~1,910 entries
```

---

## Companies Scanned

### Greenhouse API direct checks
| Company | Result |
|---------|--------|
| Arize AI | No intern roles (32 FTE-only positions) |
| Temporal | No jobs listed (0 positions) |
| RunPod | No intern roles (all FTE) |
| Stripe | No intern/new-grad SWE roles (only Data Analyst Intern requiring Master's) |
| Brex | No interns — all mid-senior FTE |
| West Monroe | Board empty (0 jobs); Aug 2025 LinkedIn posts likely closed by April 2026 |
| Cloudflare (refresh) | Only new role = Fall 2026 BA Marketing Intern — non-SWE, skipped |

### Lever Board (full scan)
| Company | Result |
|---------|--------|
| Palantir | 3 new Deployment Strategist Internship variants found (all ≤2.5/5 — see below) |

### New findings (not in history)
| Company | Title | Score | Disposition |
|---------|-------|-------|-------------|
| Deloitte | GPS Summer Scholar – Tech Packages | 2.5/5 | `skipped_score` — enterprise SAP/Oracle impl, 50% travel, not Carlos's stack |
| Palantir | Deployment Strategist Intern - Commercial | 2.5/5 | `skipped_score` — consulting role, 2026-graduation constraint |
| Palantir | Deployment Strategist Intern - US Gov | 2.0/5 | `skipped_score` — clearance required, DC/Honolulu HI |
| Palantir | Deployment Strategist Build-to-Apply - US Gov | 2.0/5 | `skipped_score` — clearance + graduation constraint |
| Efficient Computer | Compiler Intern | 2.5/5 | `skipped_score` — LLVM/hardware domain gap |
| Pure Storage | SW Engineer – Summer 2026 Internship | — | `skipped_location` — Prague, Czech Republic |
| Cloudflare | Solutions Engineer Intern (Summer 2026) | — | `skipped_location` — Lisbon, Portugal |
| Chainguard | Software Engineer Intern (Packaging) | — | `skipped_closed` — 404 removed |

### Companies confirmed no new roles (all in history)
CrowdStrike · Palo Alto Networks · SentinelOne · Datadog · Okta · Confluent · Databricks · MongoDB · Viam · Semgrep · Salesforce · Anduril · NVIDIA · Roblox · Zendesk · Axon (US) · Zscaler (all roles) · Brain Co · HPIQ · CLEAR · Handshake · WeRide · Accenture · Notion · Cohere · Giga · Ramp · Farsight · Sigma Computing · Cloudflare (SWE Austin) · SpaceX · DV Trading · Klaviyo · Verkada · Robinhood · PDT Partners · Together AI Security · Gemini · MEMX · Schonfeld · Dark Wolf · Verisign · Bandwidth DevSecOps · Artera · Belvedere Trading · Tevora · Replit · Superhuman · DoorDash · Roadie

---

## Score Notes — Sub-threshold Findings

### Palantir Deployment Strategist, Internship — Commercial (2.5/5)
- **URL:** https://jobs.lever.co/palantir/9f0dcd19-22ec-4860-8f85-dff02a30dbb7
- **Comp:** $6,700/month (~$80K annualized)
- **Location:** NYC / DC / SF
- **Why skipped:** Client-facing business consulting role (not core SWE/security); requires 2026 graduation as *final internship* before graduating — eligibility risk; Python/SQL only "a plus"
- **Note:** If Carlos is graduating Dec 2026, worth reconsidering — Palantir brand is strong.

### Deloitte GPS Summer Scholar Tech Packages (2.5/5)
- **URL:** https://apply.deloitte.com/en_US/careers/JobDetail/Deloitte-Consulting-LLP-Government-Public-Services-Summer-Scholar-Tech-Packages/312563
- **Comp:** $38/hr | **Location:** Arlington/Rosslyn, VA
- **Why skipped:** "Tech Packages" = SAP/Oracle/Workday implementation — not Carlos's stack (Python/React/AWS/LangChain). 50% travel requirement. Government consulting trajectory.

### Efficient Computer Compiler Intern (2.5/5)
- **URL:** https://job-boards.greenhouse.io/efficientcomputer
- **Location:** San Jose, CA
- **Why skipped:** LLVM/compiler specialization at hardware startup. Carlos has C/C++ + carlosOS kernel experience but no compiler toolchain background. Domain gap vs. primary SWE/AI/security targets.

---

## Context — Late-Cycle Market

This is scan v63, the fifth autonomous scan run on 2026-04-14. Scans v59–v62 (earlier today) swept:
- All portals.yml companies (Greenhouse APIs + Ashby direct + Lever direct)
- 60+ WebSearch queries across Greenhouse/Ashby/Lever/YC/SimplifyJobs
- Curated lists (SimplifyJobs, speedyapply GitHub)

The summer 2026 intern market is at **late-cycle**: most top-tier companies have filled their summer cohorts. Remaining openings are niche, location-constrained, or lower-fit.

---

## Outstanding Pipeline Items (from all scans — still pending)

| Score | Company | Role | Notes |
|-------|---------|------|-------|
| 4.0/5 | Tenstorrent | Applied AI Workflow Automation Intern | Report #363; Austin TX/Santa Clara; n8n in JD |
| 4.0/5 | ElevenLabs | Forward Deployed Engineer - Recent Grad | Report #364; Remote+SF/NY; voice AI $3.3B |
| 3.8/5 | Cua (YC) | Research Intern Summer 2026 | SF/Remote; $8K-9.25K/mo; AI computer-use agents |
| 3.7/5 | Speak (YC) | Full-stack Engineer Internship | SF in-person; $6-10K/mo; React/Node/Python |
| 3.7/5 | Zscaler | Software Engineer Intern (Summer 2026) | San Jose CA hybrid; $45-65/hr; cloud security |
| 3.7/5 | Lenovo | AI Application Development Intern | Morrisville NC; LangChain+Python+LLM |
| 3.5/5 | Aledade | Summer Internship - AI Researcher | Remote 10wks; browser-use agents; healthcare |
| 3.3/5 | Hootsuite | Co-op Intern, Internal AI Operations | ⚠️ URGENT: interview window April 14-24 |
| 3.2/5 | Commvault | AI & Support Automation Intern | Remote USA; May 26-Aug 7 |
| 3.1/5 | Bandwidth | Software Development Intern (SW Infra) | Raleigh NC in-person |

---

## Recommended Next Actions

1. **URGENT — Hootsuite interview window closes April 24.** Verify US work eligibility before applying (Canadian company).
2. **Apply to Tenstorrent (#363) and ElevenLabs FDE (#364)** — both scored 4.0/5, reports ready.
3. **Evaluate Cua, Speak, Zscaler, Lenovo** — all scored 3.7–3.8/5, worth full evaluation.
4. **Run `/career-ops pipeline`** to process remaining pending items.
5. Consider scanning for **fall 2026 co-ops** and **2027 summer early applications** (open Oct–Nov 2026).
6. Run `/career-ops scan` again in 3–5 days to catch late-posted roles.

---
*Generated by career-ops autonomous scan agent — 2026-04-14 (scan-v63, merged)*
