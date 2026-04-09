# Portal Scan — 2026-04-09 (Scan v14 — Wave 4)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
**Run:** Autonomous Agent Wave 4 (Scan v14)
**Scan history entries before this run:** 860
**Companies/portals checked this run:** 35+

## Scan Scope

Waves 1-13 had covered ~860 unique listings across major job boards. This wave focused on:
1. Exhaustive check of portals.yml remaining companies (Hume AI, Temporal, RunPod, W&B, Retool)
2. New discovery sweeps: Fortinet, Zendesk, Mastercard, Vapi (intern listing)
3. Verification of previously-unscanned corners: HRT (closed), Orca/Snyk/Lacework (no interns), Palo Alto Networks (0 listings)

## Results

| Metric | Count |
|--------|-------|
| Queries/API calls executed | 35+ |
| Companies checked this run | 35+ |
| New listings found | 5 |
| Filtered (closed/UK/not relevant) | 1 (Cloudflare London) |
| Added to pipeline.md | 5 |
| Scored ≥ 4.0 (full report) | 1 (Cloudflare AI & Automation 4.5) |
| Scan history entries added | 18 |

## New Listings Found This Wave

| Company | Role | Score | Action |
|---------|------|-------|--------|
| **Cloudflare** ⭐ | Product Marketing Engineer Intern (AI & Automation) | **4.5** | ✅ Report #285 — APPLY NOW |
| Zendesk | Software Engineer Intern (Austin, TX) | ~3.8 | Pipeline — evaluate soon |
| Fortinet | Software Development Engineer Intern (Sunnyvale) | ~3.8 | Pipeline — cybersecurity match |
| Vapi | Software Engineering Intern (SF) | ~3.8 | Pipeline — voice AI backend |
| Mastercard | Software Engineer Intern (US) | ~3.5 | Pipeline — financial systems |

## ⭐ Top Match: Cloudflare AI & Automation Intern (4.5/5)

**URL:** https://job-boards.greenhouse.io/cloudflare/jobs/7781953  
**Location:** Austin, TX — hybrid (3-5 days/week)  
**Report:** [285](reports/285-cloudflare-ai-automation-intern-2026-04-09.md)

**Why exceptional:**
- Carlos built a Cloudflare Workers + Hono API gateway at Finch (20+ proxied endpoints, OAuth, S3 signed URLs) — this role asks for Workers AI experience
- JD explicitly mentions Claude Code as a desired tool — Carlos has direct hands-on use
- Build AI agents + autonomous workflows = exact Agentic/Automation archetype match
- TypeScript/React/Tailwind exact stack match
- Austin, TX (hybrid) — no relocation, same state as TAMU
- Despite "Product Marketing" in the title, this is a pure engineering role building GTM automation tools and AI agents

**Apply this week.**

## Companies Scanned → No Roles

| Company | Reason |
|---------|--------|
| Hume AI | No intern/new grad roles |
| Temporal | No open positions at all |
| RunPod | No intern/new grad roles |
| Weights & Biases | All senior FT only |
| Hudson River Trading | Applications closed (Summer 2026) |
| Retool | No intern/new grad roles |
| Cursor/Anysphere | No structured intern program |
| Orca Security | All senior FT only |
| Snyk | No intern listings |
| Palo Alto Networks | 0 active intern listings currently |

## Pipeline Health Note

Reports #281-#284 (CrowdStrike Red Team, Prophet Security, Baseten, Proofpoint) are referenced in applications.md from Wave 3 but may be missing from disk. Run `node verify-pipeline.mjs` to confirm and re-generate if needed.

## Recommended Next Actions

1. **APPLY IMMEDIATELY:** Cloudflare AI & Automation Intern (Austin, TX) — report #285. Strongest find of the wave.
2. **EVALUATE:** Zendesk SWE Intern (Austin, $98-148K annualized) — strong comp, AI project, same city
3. **EVALUATE:** Fortinet SDE Intern — cybersecurity minor is the differentiator, network security background
4. **APPLY (existing ⭐ reports):** Haize Labs 4.7, CrowdStrike Red Team 4.5, Stripe 4.5 — if not yet applied
5. **Run:** `node verify-pipeline.mjs` to audit pipeline integrity

## Market Status Note (April 2026)

The job market for Summer 2026 internships is late-cycle. Many elite firms (Jane Street, HRT, Two Sigma, D.E. Shaw) have closed. Focus on:
- Companies still actively hiring (Cloudflare, Zendesk, Fortinet, Vapi)
- Re-verifying older pipeline items for closure before applying

---

# Portal Scan — 2026-04-09 (Scan v13)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
**Run:** Autonomous Agent (scan v13)
**Scan history entries before this run:** 843
**Companies scanned this run:** 21+

## Scan Scope

Previous agents (v1–v12) had already covered most major job boards. This run focused on:
1. Unscanned portals.yml tracked companies: PolyAI, Parloa, Intercom (Greenhouse APIs)
2. Brand new companies: Proofpoint, Tanium, Mach Industries, Naptha AI, MatX
3. Broad discovery sweeps across Ashby, Greenhouse, Lever

## Results

| Metric | Count |
|--------|-------|
| Queries / API calls executed | 25+ |
| New listings found | 17 |
| Filtered (grad-level, India-based, not relevant) | 7 |
| Added to pipeline.md | 6 |
| Scored ≥ 4.0 (full reports) | 1 |
| Scan history entries added | 17 |

## New Listings Added to Pipeline

| Company | Role | Score | Notes |
|---------|------|-------|-------|
| Proofpoint | Software Engineering Intern, AI Agents (Satori) | **4.2** ⭐ | Agentic AI at top cybersecurity co; multi-agent + guardrails; Draper UT |
| Proofpoint | Software Engineer Intern (Summer 2026) | ~3.7 | Data Security Platform; Python/AWS/ML; Boston MA |
| Proofpoint | Agentic AI Workflows Intern | ~3.5 | Enterprise AI adoption workflows; Sunnyvale CA |
| Tanium | Solution Engineering Intern | ~3.4 | Endpoint security; Addison TX (DFW); $27/hr Jun-Aug |
| Naptha AI | Software Engineer Intern | ~3.5 | AI agent infrastructure startup; verify details |
| Mach Industries | Summer Intern 2026 - Software | ~3.0 | Defense autonomous systems; Huntington Beach CA |

## Top Match

### ⭐ Proofpoint — Software Engineering Intern, AI Agents (Satori) — 4.2/5
- URL: https://proofpoint.wd5.myworkdayjobs.com/en-US/ProofpointCareers/job/Software-Engineering-Intern---AI-Agents_R13776
- Carlos's TidalHack 6-agent AutoGen system + Finch's LangChain validation gates = direct archetype match
- Report: [284](reports/284-proofpoint-swe-intern-ai-agents-2026-04-09.md)
- Action: Apply ASAP

## Companies Scanned → No Relevant Roles
- PolyAI: All senior FT, no internships
- Parloa: All senior FT, no internships
- Intercom: All senior FT, no internships
- Tanium AI Research Intern: Master's/PhD required
- MatX ML Research Intern: Hardware chip background required
- CloudSEK: India-based

## Recommended Next Actions
1. Apply immediately to Proofpoint AI Agents (4.2/5, report 284 ready)
2. Run `/career-ops pipeline` to evaluate backlog of 60+ pending URLs
3. Apply to existing ⭐ roles: Haize Labs (4.7), CrowdStrike Red Team (4.5), Best Egg (4.5), Notion AI (4.5)

---

# Portal Scan — 2026-04-09 (Scan v12)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
**Autonomous scan agent run** | Continuation of v9-v11 from earlier today
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Stats

| Metric | Count |
|--------|-------|
| WebSearch queries executed | ~20 |
| Greenhouse API calls | 5 (Airtable, Intercom, Together AI, Scale AI, Cloudflare) |
| Companies/portals scanned | 25+ |
| Total candidates evaluated | ~150+ results reviewed |
| Filtered by title (negative) | ~60 |
| Duplicates (already in history) | ~80 |
| **New listings added to pipeline** | **11** |
| **Full evaluations written (≥4.0)** | **2** |

---

## New Listings Added to pipeline.md

| Company | Role | Score | Notes |
|---------|------|-------|-------|
| **Prophet Security** ⭐ | SWE New Grad (Backend/ML) | **4.3/5** | Agentic AI SOC platform, Accel $41M, Python+LLMs+security crossover |
| **Baseten** ⭐ | Software Engineering Intern | **4.0/5** | ML inference platform, FDE/Infra track, 2026 grads only |
| Suno | SWE Internship (Summer 2026) | ~3.5 | Music AI, Cambridge MA, Python/TypeScript |
| Schonfeld | 2026 SWE Summer Intern | ~3.6 | Quant trading, NYC, Carlos's quant project is differentiator |
| Virtu Financial | SWE Intern | ~3.5 | HFT, Austin TX or NYC, systems depth relevant |
| Synthflow AI | Forward Deployed Engineer | ~3.5 | Voice AI, FDE full-time role |
| Exa | Forward Deployed Engineer | ~3.5 | AI search API, FDE full-time |
| Anduril Industries | SWE Intern, Frontier Systems | ~3.5 | Defense tech, Irvine CA, new UUID found |
| Sigma Computing | SWE Intern (Summer 2026) | ~3.4 | BI + AI copilot, SF |
| Enova International | SWE Internship (Hybrid) | ~3.3 | Fintech AI, Chicago hybrid Jun-Aug |
| Suno | Software Engineer, Early Career | ~3.3 | Music AI, full-time new grad |

---

## Full Evaluation Reports Written

### 282 — Prophet Security — SWE New Grad (Backend/ML) — 4.3/5 ⭐
- **Why:** $41M Accel/Bain Capital-backed Agentic AI SOC Platform. Direct crossover of Carlos's AI pipeline engineering + security hardening + adversarial LLM testing.
- **Stack:** Python, Go, LLMs, security tool integrations
- **Location:** Menlo Park, CA (in-person, relocation needed)
- **Apply:** Yes — this week. Lead with adversarial LLM testing + HMAC/TLS security engineering.

### 283 — Baseten — Software Engineering Intern — 4.0/5 ⭐
- **Why:** ML inference/model serving platform. 4 tracks; FDE or Infrastructure track is strongest fit. 90th percentile comp target. Carlos's multi-model pipeline + blue/green infra = strong signal.
- **Stack:** Python, Go, distributed systems, ML inference
- **Location:** SF or NYC, 3 days/week
- **Apply:** Yes — target FDE track. Lead with 5-provider LLM pipeline + production infra engineering.

---

## Key Finds from Companies NOT Previously Scanned

| Company | Status |
|---------|--------|
| Prophet Security | ✅ Found — new grad role (security + AI) |
| Baseten | ✅ Found — intern role (ML inference) |
| Suno | ✅ Found — intern + early career roles |
| Virtu Financial | ✅ Found — SWE intern (Austin TX) |
| Schonfeld | ✅ Found — SWE summer intern (different from Cyber intern) |
| Synthflow AI | ✅ Found — FDE full-time |
| Exa | ✅ Found — FDE full-time |
| Enova International | ✅ Found — fintech SWE intern |
| Together AI | ⚠️ Intern roles no longer visible in API (may be closed) |
| Arcesium | ⚠️ FDE intern listing may be closed |
| Intercom | 📋 No intern/entry-level roles; all senior |
| Cloudflare | 📋 No new intern listings beyond what was already in pipeline |

---

## Recommended Next Actions

1. **APPLY NOW — Prophet Security (4.3/5):** Adversarial AI SOC platform is the perfect fit. Apply this week before it closes.
2. **APPLY — Baseten (4.0/5):** Target FDE track. Apply within 3-5 days.
3. **EVALUATE — Schonfeld SWE Intern (3.6):** Quant trading background = differentiator. Verify deadline/status.
4. **EVALUATE — Virtu Financial SWE Intern (3.5):** HFT firm, Austin TX location is accessible.
5. **SKIP — Enova, Sigma (3.3-3.4):** Below threshold; only apply if other pipeline empties out.
6. **PROCESS PIPELINE:** Run `/career-ops pipeline` to evaluate all pending entries from today's scans (v9-v12).

---

## Cumulative Pipeline Status (2026-04-09)

| Category | Count |
|----------|-------|
| Total pipeline entries | 60+ |
| High priority (≥4.0, unevaluated) | ~15 |
| Medium (3.5-3.9) | ~25 |
| Low/skip (<3.5) | ~20 |
| Evaluated today (reports written) | 2 (Prophet Security, Baseten) |
| Previously evaluated (reports exist) | 10+ (Haize Labs, Sierra, Cloudflare, Stripe, Semgrep, Scale AI, Point72, CrowdStrike, etc.) |

---

*Scan v12 completed by autonomous agent — 2026-04-09*
*Next scan recommended: 2026-04-12 (3 days)*
