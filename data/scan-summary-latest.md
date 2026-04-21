# Portal Scan Summary — 2026-04-21 (v145)

**Date:** 2026-04-21  
**Scan version:** v145  
**Agent:** Autonomous scan agent  

---

## Results

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Portals/companies scanned:       35+
Channels exhausted:              Greenhouse APIs (9 companies — all back online),
                                 Cloudflare new URLs,
                                 ICE (Intercontinental Exchange) — NEW company,
                                 NVIDIA, Amazon, Apple, Databricks, ServiceNow,
                                 CrowdStrike, Wiz, Stripe, Brex, Salesforce,
                                 Anduril, IBM, Okta, Palo Alto Networks,
                                 OpenAI, xAI, Perplexity, Mistral,
                                 SimplifyJobs (0-1d), SpeedyApply AI/SWE,
                                 YC Work at a Startup, Jobright
New qualifying listings ≥4.0/5:  0
New pipeline entries:            0 (v145)
                                 2 added from v144 (TikTok LLM-agents ~3.8, DoorDash ~3.0)
New scan-history entries:        19 (v145) + 13 (v144 already in history)
Total scan-history entries:      ~3,202 (after v145)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**Market status: FULLY SATURATED** — 145 consecutive exhaustive scans. Summer 2026 internship cycle effectively closed. Last qualifying ≥4.0/5 discovery was TikTok Product Security #392 (v142, April 21).

---

## v145 Key Findings

### New Company Discovered: ICE (Intercontinental Exchange)

4 URLs never previously in scan history:

| URL | Role | Status | Score |
|-----|------|--------|-------|
| careers.ice.com/jobs/11604 | Cybersecurity Automation Intern | **CLOSED (404)** | N/A |
| careers.ice.com/jobs/11635 | Software Engineer Intern | Open (503 unverified) | ~3.0/5 |
| careers.ice.com/jobs/11598 | Software Developer Intern | Open (unverified) | ~2.8/5 |
| careers.ice.com/jobs/11603 | SDET Intern | Open (unverified) | skipped_title |

**Why below threshold:** Atlanta GA on-site (5d/week), financial infrastructure domain (NYSE/bond markets), legacy AngularJS→React conversion work. Carlos's profile is strongest in AI/security/cloud, not financial infra legacy code. None reached 4.0/5 threshold.

### Greenhouse APIs Back Online

After multiple scans with 503 errors (v130–v143), all Greenhouse APIs are now responding:
- Anthropic: All 5 Fellows tracks confirmed dup — general (5023394008), AI Safety (5183044008), AI Security (5030244008), ML Systems (5183051008), RL (5183052008), STEM Fellow (5189848008)
- All others: No intern/new-grad roles found

### Crusoe Product Security Applied AI Intern — Status Update

The role continues to appear on external job boards (Climate Draft, G2VP, LinkedIn, ImpactSource) but:
- Direct Ashby URL returns incomplete page (just "Jobs" header)
- All verification endpoints (Simplify, ClimateDraft) returning 503
- Cannot confirm active status via automated scan

**Recommend: Visit jobs.ashbyhq.com/Crusoe directly in a browser.**

---

## Channels Checked (v145)

| Channel | Result |
|---------|--------|
| Greenhouse APIs (9 companies) | All back online; 0 new intern/new-grad roles |
| Cloudflare (new URLs 7603409, 7799344) | Both non-technical admin/ops roles; skipped |
| ICE Intercontinental Exchange | 4 NEW URLs; all below 4.0 threshold or closed |
| NVIDIA Summer 2026 interns | All dup v8-v144 |
| Amazon SDE/Security interns | All dup v7-v144 |
| Apple SWE/ML/Security interns | All dup v8-v144 |
| Databricks SWE intern + New Grad | All dup v7-v144 |
| ServiceNow SWE/ML interns | All dup v8-v144 (closed) |
| CrowdStrike SWE/Security interns | All dup v8-v144 |
| Wiz | No intern program (confirmed) |
| Stripe / Brex / Plaid | All dup v7-v144 |
| Salesforce SWE/Solutions/AI | All dup v7-v144 |
| Anduril SWE intern / New Grad | All dup v7-v144 |
| IBM Software Dev intern | All dup v8-v144 |
| Okta SWE / AI intern | All dup v7-v144 (SWE AI closed) |
| Palo Alto Networks | No US intern listings found |
| OpenAI Applied Emerging Talent | All dup v20-v144 |
| xAI Engineering Internship | Hardware/EE domain; skipped_title dup v123 |
| Perplexity / Mistral | UK-only / Paris EMEA |
| SimplifyJobs v145 (0-1d entries) | 15 entries — all dup/non-target |
| SpeedyApply AI/SWE v145 | All dup v7-v144 |
| YC Work at a Startup v145 | All dup v30-v144 |
| Jobright (ICE, Exiger, Dropbox) | ICE NEW (below threshold); Exiger/Dropbox dup |
| Ashby broad (15+ companies) | All dup v7-v144 |
| Lever broad (10+ companies) | All dup v7-v144 |

---

## Active Pipeline — High Priority (Apply Now)

| # | Company | Role | Score | Deadline | Action |
|---|---------|------|-------|----------|--------|
| 246 | Anthropic | Fellows Program — AI Security | **4.7/5** | **APRIL 26** | ⚡ APPLY IMMEDIATELY — 5 days left |
| 370 | Anthropic | Fellows Program — AI Safety | **4.2/5** | **APRIL 26** | ⚡ APPLY IMMEDIATELY — 5 days left |
| 372 | Anthropic | Fellows Program — ML Systems | **4.1/5** | **APRIL 26** | ⚡ APPLY IMMEDIATELY — 5 days left |
| 388 | ByteDance | AI Security Software Engineer Intern | **4.3/5** | Rolling | Apply this week |
| 389 | Verkada | Security SWE — University Graduate 2026 | **4.1/5** | Rolling | Verify graduation eligibility |
| 391 | Netflix | SWE Intern Summer 2026 | **4.2/5** | Rolling | Apply this week |
| 392 | TikTok | Product Security Intern 2026 | **4.0/5** | Rolling | Apply after Anthropic Fellows |
| — | Crusoe | Product Security Applied AI Intern | **~4.3/5** | Unknown | ⚠️ Manual verify required |

---

## Application Priority Order (Today, April 21)

1. **RIGHT NOW:** Anthropic Fellows deadline April 26 = **5 days left**
   - #246 AI Security (4.7/5) — highest priority in the entire pipeline
   - #370 AI Safety (4.2/5)
   - #372 ML Systems (4.1/5)
2. **Today/Tomorrow:** Manually verify Crusoe at https://jobs.ashbyhq.com/Crusoe
3. **This week:** Netflix #391 (4.2/5) + ByteDance #388 (4.3/5)
4. **After April 26:** TikTok Product Security #392 (4.0/5)
5. **Verify eligibility first:** Verkada #389 (4.1/5) — confirm graduation date

---

## Market Intelligence

- **Summer 2026 recruiting cycle is effectively closed** after 145 scans
- **TikTok 2-application limit:** Use ByteDance #388 + TikTok #392 as the two slots
- **Fall 2026 internships** begin posting May–June 2026
- **ICE** is a new company to monitor for future cycles (NYSE parent company, strong cybersecurity org)
- **Crusoe** remains the last high-value potential discovery — verify manually

---

## Recommended Actions

1. **PAUSE automated scanning until May 2026** — Summer 2026 market exhausted
2. **Apply to Anthropic Fellows immediately** — 5-day deadline
3. **Manually verify Crusoe** at jobs.ashbyhq.com/Crusoe in a browser
4. **Re-activate scanning in May 2026** for Fall 2026 co-ops and 2027 new grad roles
5. **career-ops update available:** v1.1.0 → v1.3.0 (run `node update-system.mjs apply` when ready)

---

*Scan v145 complete — 2026-04-21 — Summer 2026 market CONFIRMED FULLY SATURATED (145 consecutive scans)*
