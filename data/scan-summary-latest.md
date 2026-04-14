# Portal Scan — 2026-04-14 (v63)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Scan:** v63 (5th autonomous scan today)
**Date:** 2026-04-14
**Agent mode:** Autonomous (WebSearch + Greenhouse API + Lever board checks; Playwright unavailable)

## Stats

| Metric | Count |
|--------|-------|
| Portals / boards scanned | 25+ |
| WebSearch queries executed | 15+ |
| Raw listings evaluated | ~40 |
| Filtered by title (no positive keyword) | 2 |
| Filtered by score (<3.0) | 5 |
| Duplicates (already in history) | ~33 |
| **New listings added to pipeline.md** | **0** |
| Listings scored ≥4.0 (full reports) | 0 |
| New entries added to scan-history.tsv | 9 |
| History total (lines) | 1,895 |

## Portals Checked This Scan

### Greenhouse API (new checks)
- **Stripe** — no intern/new-grad SWE roles; only Data Analyst Intern (Master's req)
- **Brex** — no interns; all mid-senior FTE
- **West Monroe** — Greenhouse board empty (0 jobs); LinkedIn listings from Aug 2025 likely closed by April 2026
- **Cloudflare** — board refresh; only new role = Business Analyst Marketing Intern (Fall 2026, non-SWE)

### Lever Board (full scan)
- **Palantir** — 3 new Deployment Strategist Internship variants found (see below)

### WebSearch (15+ queries across portals)
- Ashby: Notion, Replit, Farsight, Giga, Cohere, Delinea, Fizz, Harvey, Superhuman — all in history
- Greenhouse: DV Trading, Klaviyo, Okta, Verkada, Robinhood, HP IQ, Pure Storage, PDT Partners — all in history
- Lever: Artera, Voleon, Shield AI, WeRide, Symmetry Systems, Belvedere Trading, Tevora — all in history
- YC: Dex, Circleback, Browser Use, Swif.ai, Cloudglue, a0.dev, Mesh, Crustdata, Promptless — all in history
- SimplifyJobs README: 0d entries = Tenstorrent ✓, Zscaler SWE ✓, Commvault ✓ (all already in history/pipeline); BlueScope Dev Intern skipped (steel company, below threshold); Dick's Sporting Goods Android skipped (negative filter)
- Security roles: Bandwidth DevSecOps, Cloudflare Security, Together AI Security, Gemini, Gallup, MEMX, Schonfeld — all in history

## New Findings (all below pipeline threshold)

### Palantir Deployment Strategist, Internship — Commercial
- **URL:** https://jobs.lever.co/palantir/9f0dcd19-22ec-4860-8f85-dff02a30dbb7
- **Score:** 2.5/5
- **Comp:** $6,700/month (~$80K annualized)
- **Location:** NYC / DC / SF
- **Why below threshold:** Client-facing business consulting role (not core SWE/security); requires 2026 graduation as *final internship* before graduating — eligibility risk depending on Carlos's graduation timeline; Python/SQL listed only as a "plus"

### Palantir Deployment Strategist, Internship — US Government
- **URL:** https://jobs.lever.co/palantir/a49d4181-a289-435a-b581-7f5af0497c8e
- **Score:** 2.0/5
- **Why skipped:** Active US security clearance eligibility required; DC / Honolulu HI locations; same graduation constraint

### Palantir Deployment Strategist, Build to Apply — US Government
- **URL:** https://jobs.lever.co/palantir/842d6bc5-823c-4a77-8839-3f0f427bcd8c
- **Score:** 2.0/5
- **Why skipped:** Build-to-apply program variant of the above US Gov role; same clearance/location/graduation constraints

### Efficient Computer — Compiler Intern
- **URL:** https://job-boards.greenhouse.io/efficientcomputer (specific JD not fetched)
- **Score:** 2.5/5
- **Location:** San Jose, CA
- **Why below threshold:** LLVM/compiler specialization at a hardware startup building energy-efficient AI processors; Carlos has C/C++ + carlosOS experience but no compiler background; domain gap relative to primary SWE/AI/security targets

## Companies Confirmed No New Roles (since prior scans)

Stripe, Brex, West Monroe, Cloudflare (new interns), Notion, Replit, Cohere, Farsight, Giga, Delinea, Fizz, Harvey, Superhuman, DV Trading, Klaviyo, Okta, Verkada, Robinhood, HP IQ, Pure Storage, PDT Partners, Artera, Voleon, Belvedere Trading, Tevora, Dex, Circleback, Browser Use, Swif.ai, Cloudglue, a0.dev, Mesh, Crustdata, Promptless, Bandwidth DevSecOps, Cloudflare Security, Together AI Security, Gemini, Gallup, MEMX, Schonfeld, Sigma Computing, Lucid Motors, iCapital, Roadie, DoorDash

## Outstanding Pipeline Items (from all scans)

The following items remain pending in pipeline.md and have not been applied to yet:

| Score | Company | Role | Notes |
|-------|---------|------|-------|
| 4.0/5 | Tenstorrent | Applied AI Workflow Automation Intern | Report #363; Austin TX/Santa Clara/Fort Collins; n8n in JD + CV |
| 4.0/5 | ElevenLabs | Forward Deployed Engineer - Recent Graduate | Report #364; Remote+SF/NY; voice AI $3.3B |
| 3.8/5 | Cua (YC) | Research Intern Summer 2026 | SF/Remote; $8K-9.25K/mo; AI computer-use agents |
| 3.7/5 | Speak (YC) | Full-stack Engineer Internship | SF in-person; $6-10K/mo; React/Node/Python |
| 3.7/5 | Zscaler | Software Engineer Intern (Summer 2026) | San Jose CA hybrid; $45-65/hr; cloud security |
| 3.7/5 | Lenovo | AI Application Development Intern | Morrisville NC; LangChain+Python+LLM |
| 3.5/5 | Aledade | Summer Internship - AI Researcher | Remote 10wks; browser-use agents; healthcare domain |
| 3.3/5 | Hootsuite | Co-op Intern, Internal AI Operations | URGENT: interview window April 14-24; Anthropic API role |
| 3.2/5 | Commvault | AI & Support Automation Intern | Remote USA; May 26-Aug 7 |
| 3.1/5 | Bandwidth | Software Development Intern (SW Infra) | Raleigh NC in-person |
| 3.0/5 | WeRide.ai | New Grads 2026 - General SWE | San Jose CA in-person; verify graduation eligibility |
| 3.0/5 | a0.dev (YC) | Software Engineering Intern | SF in-person; TypeScript/Next.js |
| 2.8/5 | Bandwidth | Network Development Engineering Intern | Raleigh NC; Python/Go/Linux |
| 2.5/5 | Versana | Tech Internship | NYC in-office; Java/SQL/React; fintech |

## Recommended Next Actions

1. **URGENT — Hootsuite interview window closes April 24:** Verify US work eligibility for Canadian co-op before applying
2. **Apply to Tenstorrent (#363) and ElevenLabs FDE (#364)** — both scored 4.0/5, reports ready
3. **Evaluate Cua, Speak, Zscaler, Lenovo** — all scored 3.7-3.8/5, worth full evaluation
4. **Run `/career-ops pipeline`** to process remaining pending items
5. **Note on Palantir DS Internship:** If Carlos is graduating December 2026 or May 2026, the Deployment Strategist, Internship (commercial) at $6,700/mo is worth a second look — Palantir brand is strong and the role is consulting-adjacent. Verify graduation timeline before applying.

---
*Generated by career-ops autonomous scan agent — 2026-04-14 (scan v63)*
