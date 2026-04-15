# Portal Scan Summary — 2026-04-15 (v79)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Candidate:** Carlos Luna-Peña  
**Scan version:** v79  
**Date:** 2026-04-15  
**Scan type:** Autonomous Agent — Comprehensive discovery sweep

---

## Stats

| Metric | Count |
|--------|-------|
| WebSearch queries executed | 25+ |
| Company portals checked | 30+ |
| Greenhouse API calls | Multiple (503 rate-limited throughout) |
| Total URLs evaluated | ~50 |
| Duplicate / already in history | ~45 |
| Skipped (title filter / domain / score) | ~10 |
| **New listings added to pipeline** | **3** |
| Listings scoring ≥ 4.0 | 0 |

---

## Context

The pipeline is **heavily saturated** — 2,159+ entries through scan v78 (completed earlier today on 2026-04-15). Most known portals (Ashby, Greenhouse, Lever, YC, SimplifyJobs, SpeedyApply) returned predominantly duplicates. Greenhouse APIs were rate-limiting (503) throughout this scan.

This is the **fourth scan run today** (v75, v76, v77, v78 all ran 2026-04-15 before this v79). Marginal returns are diminishing significantly — the Summer 2026 internship season is at near-peak saturation.

---

## New Listings Added to Pipeline (3)

None scored ≥ 4.0. All are low-priority volume additions.

| Company | Role | Score | Location | Notes |
|---------|------|-------|----------|-------|
| Alloy | Software Engineering Intern | ~3.2/5 | NYC hybrid 2-3d/wk | Identity risk fintech; Go/Docker/JS; comp undisclosed; Go is a stack gap |
| Tricentis | Software Engineering Intern | ~3.0/5 | Austin TX | Test automation software; $32-56/hr ✓; testing/QA domain not primary archetype |
| Mine (YC) | Software Engineering Intern | ~3.0/5 | SF likely | YC startup; 100K+ user reach/month; comp/stack undisclosed; verify before applying |

---

## Top Matches ≥ 4.0

**None found in this scan.** All high-scoring roles already in pipeline from prior scans.

**Current top priorities already in pipeline (from earlier scans today):**

| Rank | Company | Role | Score | Notes |
|------|---------|------|-------|-------|
| 1 | Cloudflare | SWE Intern (Austin TX) | 4.8/5 | Prod Cloudflare Workers exp = top differentiator |
| 2 | OpenAI | SWE Intern (Summer 2026) | 4.5/5 | SF/Seattle; multi-model pipeline exact match |
| 3 | Atlassian | Security Engineer Intern | 4.5/5 | Seattle; Cybersec Minor + OAuth/TLS/HMAC exact |
| 4 | Together AI | Security Engineer Intern | 4.5/5 | $58/hr; SF; adversarial LLM testing exact match |
| 5 | NVIDIA | Solutions Architect - New Grad | 4.5/5 | $108-196K; Santa Clara; 18-month SA rotation |
| 6 | Ramp | FDE Intern | 4.5/5 | $11K/mo + housing; NYC/SF; fintech FDE |
| 7 | Glean | SWE Intern | 4.5/5 | $57-69/hr; Palo Alto/SF; AI search |
| 8 | 1Password | Extension Excellence Intern | 4.3/5 | Remote US/CA; Chrome MV3 exact match |
| 9 | Point72 | AI Intern LS Equities | 4.3/5 | $130K annualized; NYC; Bloomberg/quant match |
| 10 | Dex | AI/ML Engineer Intern | 4.3/5 | $6-10K/mo; SF; browser agents + LLM |

---

## Portals Confirmed Saturated (no new roles)

- **Ashby:** Cohere, ElevenLabs, Notion, Sierra, Decagon, Ramp, 1Password, Replit, Harvey, Zip, Whatnot, Delinea, Sentry, Vantage, Brain Co., Handshake, Lambda, Superhuman, Monarch Money, Simple AI, Ontic
- **Greenhouse:** Scale AI, Klaviyo, Glean, Cloudflare, Together AI, Mercury, Figma, DoorDash, Robinhood, CLEAR, Enova, Sigma Computing, Pendo, HP IQ, Databricks, Verkada, Aquatic Capital, Astranis, Bandwidth
- **Lever:** Palantir, Mistral AI, Symmetry Systems, Artera, Shield AI, Nominal, Waabi
- **YC Board:** All entries confirmed through v57; Mine/SID/Novaflow checked today
- **SpeedyApply SWE Repo:** Amentum/Appian/CACI/Cadence/Mariana Minerals/PTC/Signify/Tricentis — only Tricentis added
- **Greenhouse APIs:** 503 rate-limited (PolyAI/Parloa/Intercom/Hume AI/Temporal/Arize AI/RunPod all 0 interns per v75)

---

## Skipped Listings (this scan)

| Company | Role | Reason |
|---------|------|--------|
| SID (YC) | Research Intern | Research role; not primary archetype (skipped_title) |
| Alloy | Junior Software Engineer | Full-time FTE, not intern (skipped_title) |
| Appian (7727768) | Software Engineering Intern | Same co as 7201613 already skipped; Java/low-code; $22-30/hr below minimum |
| CACI (Austin 316653) | Software Engineer Intern | Defense contractor; clearance likely; 2.5/5 below threshold |
| Mariana Minerals | Full-Stack Intern | Mining/minerals domain; Ann Arbor MI |
| PTC | Software Engineer Intern | Industrial IoT/CAD domain; 2.8/5 below threshold |
| Signify/Cooper Lighting | Software Engineering Intern | Lighting hardware domain; Atlanta GA |
| Amentum | Software Systems Engineer Intern | Defense/aerospace; Huntsville AL |
| Cadence | Software Intern | EDA/semiconductor tools; 3.0/5 below threshold |

---

## Recommended Next Actions

1. **APPLY NOW** — Focus entirely on applying to evaluated roles in applications.md. 40+ evaluated roles at 4.0+ sit unapplied.
2. **Priority apply list:** Cloudflare SWE (Austin), OpenAI SWE, Atlassian Security, Together AI Security, 1Password Extension Excellence, Ramp FDE, Glean SWE
3. **Stop scanning** — Marginal return per scan is near zero. Run `/career-ops pipeline` instead to process pending pipeline items.
4. **Next scan:** Recommend 2026-04-22 (7 days) — allow new postings to accumulate before scanning again.
5. Run `node verify-pipeline.mjs` to check pipeline health if needed.

---

*Generated by career-ops autonomous scan agent v79 — 2026-04-15*
