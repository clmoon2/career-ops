# Portal Scan — 2026-04-12 (scan-v42)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Run Stats

| Metric | Count |
|--------|-------|
| Companies scanned | 22 |
| Greenhouse API queries | 8 |
| Ashby pages scanned | 12 |
| Lever pages attempted | 3 (403 — fell back to WebSearch) |
| WebSearch queries | 15+ |
| External sources checked | SimplifyJobs GitHub, SpeedyApply GitHub |
| Total listings seen | 180+ |
| Filtered by title (positive match) | 45 |
| Duplicates (already in history/pipeline) | 42 |
| **New listings added to pipeline** | **3** |
| **Evaluated (score >= 4.0)** | **2 (OpenAI 4.5, Harvey 4.1)** |

---

## New Listings Added

| URL | Company | Role | Score | Status |
|-----|---------|------|-------|--------|
| [Workday link](https://iheartmedia.wd5.myworkdayjobs.com/External_iHM/job/San-Antonio-TX-Stone-Oak/Software-Engineer-Intern_Req37982-2) | iHeartMedia | Software Engineer Intern | ~2.5 | pipeline pending |
| [Oracle Cloud link](https://ejta.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2001/job/9464) | Fortive | AI / Software Engineering Intern | ~3.0 | pipeline pending |
| [Greenhouse link](https://job-boards.greenhouse.io/botauto/jobs/5182922008) | Bot Auto | Intern SWE-Operation Platforms | ~2.8 | pipeline pending |

---

## Evaluations Completed This Run

### ⭐ OpenAI — Software Engineer Internship (Summer 2026) — **4.5/5**
- **URL:** https://openai.com/careers/software-engineer-internship-co-op-applied-emerging-talent-(summer-2026)/
- **Report:** [#350](reports/350-openai-swe-intern-summer-2026-2026-04-12.md)
- **Tracker:** #353
- **Location:** SF or Seattle, in-person
- **Comp:** ~$60/hr
- **Why top match:** Carlos is already building what OpenAI Applied Engineering ships — 5-provider multi-model pipeline (including GPT-4o), blue/green CI/CD, 602-test suite, full-stack Python/React/TypeScript. Near-perfect stack alignment. Strong recommendation to apply immediately.

### Harvey — Software Engineering Intern (Summer 2026) — **4.1/5**
- **URL:** https://jobs.ashbyhq.com/harvey/b6509622-5c1e-4a3f-916b-6e56b8fd212f
- **Report:** [#351](reports/351-harvey-swe-intern-summer-2026-2026-04-12.md)
- **Tracker:** #354
- **Location:** SF, in-person
- **Comp:** ~$60/hr
- **Why strong match:** Agentic AI for legal professionals — matches Carlos's TidalHack 6-agent AutoGen system and LangChain 12-stage pipeline patterns. Python/TypeScript/React/Tailwind exact stack. a16z-backed, $300M+ raised.

---

## Notes on Scan Coverage

- **High dedup rate** (42/45 filtered matches were already known): scans v38-v41 were comprehensive. The pipeline is now well-populated with legitimate leads.
- **Discovery channels that found new listings:** SimplifyJobs Summer2026 GitHub repo (updated 2026-04-10/11) and SpeedyApply 2026-AI-College-Jobs GitHub repo were the most productive new sources.
- **Lever 403 errors:** All 3 Lever boards (Palantir, W&B, Mistral) returned 403. Fell back to WebSearch — Palantir/Mistral listings already in history.
- **Ashby JS-blocked:** All Ashby pages require JavaScript rendering. WebSearch with `site:jobs.ashbyhq.com` is the correct workaround until Playwright is used.
- **OpenAI/Harvey evaluation correction:** scan-v41 noted these as evaluated with report numbers #293 and #295 — both wrong (taken). Correct report numbers are #350 and #351. Pipeline entries updated.

---

## Priority Next Actions

1. **Apply to OpenAI** (4.5/5, report #350) — highest priority. Lead with Finch multi-model pipeline + $0.003/application cost optimization. Apply via jobs.ashbyhq.com/openai.
2. **Apply to Harvey** (4.1/5, report #351) — high priority. Lead with TidalHack 6-agent AutoGen system. Apply via jobs.ashbyhq.com/harvey/b6509622...
3. **Evaluate Priority Pending queue** (run `/career-ops pipeline` to process):
   - Cohere ML Intern (est. ~4.0) — Remote-flexible, LLM focus
   - Databricks SWE Intern (est. ~3.9) — SF/remote, distributed systems
   - Snowflake Solution Engineer TX (est. ~3.8) — Remote TX ⭐
   - CrowdStrike SWE Intern (est. ~3.8) — Security minor match
   - Salesforce SWE Intern (est. ~3.8) — SF/NYC/Seattle, Agentforce team
   - Notion AI Intern (est. ~3.8) — SF, React/Next.js

---

## Portals Covered This Run

| Portal / Method | Companies |
|---|---|
| Greenhouse API (L2) | Anthropic, Arize AI, Hume AI, Intercom, Glean, RunPod, PolyAI, Parloa |
| Ashby WebSearch | Cohere, ElevenLabs, Deepgram, Vapi, LangChain, Pinecone, Attio, Bland AI |
| Lever WebSearch | Palantir, Weights & Biases, Mistral AI, Clarity AI |
| WebSearch (L3) | OpenAI, Salesforce, ByteDance, Databricks, Snowflake, CrowdStrike, Notion |
| External repos | SimplifyJobs/Summer2026-Internships, speedyapply/2026-AI-College-Jobs |
| Direct company | iHeartMedia (Workday), Fortive (Oracle Cloud), Bot Auto (Greenhouse) |
