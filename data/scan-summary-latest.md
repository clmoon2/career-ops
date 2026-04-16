# Scan Summary — 2026-04-16 (v89)

**Agent:** Autonomous scanner (scheduled run)
**Scan version:** v89
**Date:** 2026-04-16
**History entries after scan:** 2,362

---

## Summary Stats

| Metric | Count |
|---|---|
| Companies scanned | 25+ |
| Greenhouse APIs queried | 8 (Anthropic, Airtable, Glean, Arize AI, RunPod, Together AI, Intercom, Hume) |
| WebSearch queries executed | 15+ |
| Ashby/Lever boards checked | 8 (Cohere, ElevenLabs, Decagon, Vapi, Pinecone, LangChain, Cloudflare, Notion) |
| New URLs found (total) | 7 |
| Scored ≥ 4.0 | **2** |
| Reports written | **2** (#357, #358) |
| Tracker entries added | **2** (#371 Roadie, #372 Anthropic Fellows ML Systems) |
| Skipped (dup/closed) | ~50+ |

---

## ⚠️ URGENT — Act Before April 26

Three Anthropic Fellows tracks close April 26. Two are already evaluated:

| # | Role | Score | Deadline | Notes |
|---|---|---|---|---|
| #246 | Anthropic Fellows — AI Security | **4.7/5** | April 26 | Already in pipeline — APPLY NOW |
| #370 | Anthropic Fellows — AI Safety | **4.2/5** | April 26 | Already in pipeline — APPLY NOW |
| **#372** | **Anthropic Fellows — ML Systems & Performance** | **4.1/5** | **April 26** | **NEW this scan — Report #358** |
| — | Anthropic Fellows — Reinforcement Learning | 3.6/5 | April 26 | Below threshold; consider after applying to above three |
| — | Anthropic Fellows — AI Safety (new listing 5183044008) | ~3.9/5 | April 26 | Confirm vs #370 before applying (may be same track) |

---

## Top Matches (score ≥ 4.0)

### 1. Roadie (UPS) — AI Engineer Intern | Score: 4.2/5 | Report #357
**URL:** https://job-boards.greenhouse.io/roadie/jobs/8479096002
**Location:** Remote
**Comp:** Not disclosed (UPS subsidiary, market rate expected)

**Why this is a 4.2:** The JD reads like a job description for what Carlos already built at Finch. Exact stack match: Python, FastAPI, LangChain, LangGraph, RAG, pgvector, FAISS, AWS EKS/S3, Docker. Responsibilities include LLM-powered chatbot agents, fraud detection with embeddings, data pipelines, and agent evaluation frameworks — all things Carlos has shipped in production.

**Action:** Apply immediately. Lead with Finch multi-model pipeline as primary proof point.

---

### 2. Anthropic Fellows — ML Systems & Performance | Score: 4.1/5 | Report #358 | ⚠️ APRIL 26 DEADLINE
**URL:** https://job-boards.greenhouse.io/anthropic/jobs/5183051008
**Location:** SF / London / Toronto / Remote (US, UK, CA)
**Comp:** $3,850/week + $15K/month compute + benefits
**Duration:** 4 months (July 2026 cohort)

**Why this is a 4.1:** $3,850/week stipend at the top AI lab. Carlos's 35K-line Python codebase, distributed AWS deployment, multi-model ML pipeline, and 602-test suite shows the ML engineering depth the fellowship values. Main gap: HPC/GPU infrastructure focus of past fellows vs. Carlos's API-based cloud systems. Fellowship explicitly encourages applications from non-traditional candidates. 10 days left to apply.

**Action:** Apply before April 26. Frame as production ML systems engineer (not researcher). Finch pipeline + TidalHack + quantitative trading system as proof points.

---

## Below Threshold (added to pipeline for reference)

| URL | Company | Role | Score | Notes |
|---|---|---|---|---|
| `greenhouse.io/anthropic/jobs/5183044008` | Anthropic | Fellows — AI Safety (new listing) | ~3.9/5 | Different ID from #370; confirm not duplicate before applying |
| `greenhouse.io/cloudflare/jobs/7792962` | Cloudflare | Solutions Engineer Intern (Summer & Fall 2026) | ~3.7/5 | Austin TX; July-Dec 2026; Carlos uses Workers/Pages |
| `greenhouse.io/anthropic/jobs/5183052008` | Anthropic | Fellows — Reinforcement Learning | ~3.6/5 | April 26 deadline; Carlos lacks RL training exp |
| `ashbyhq.com/notion/5b15697c` | Notion | SWE Intern (Fall 2026) | ~3.5/5 | Fall timing; may conflict with semester |

---

## Key Observations

1. **Together AI intern roles closed**: SWE Intern (5012768007) and Security Intern (5012785007) no longer in Together AI Greenhouse API — both likely closed.

2. **Glean SWE Intern likely closed**: `4595665005` (Software Engineer, Intern Summer 2026) not found in current Glean API. Apply if link still works.

3. **Anthropic added 3 new Fellows tracks** since last full API scan: ML Systems & Performance, Reinforcement Learning, and a new AI Safety listing. The AI Security and AI Safety tracks were already flagged as urgent.

4. **Airtable New Grad 2026 (8409376002) appears closed** — not in current Airtable API response.

5. **Pipeline is heavily saturated** from v86-v88 sweeps. This scan focused on API freshness checks and found one genuinely new company (Roadie) + three new Anthropic fellowship tracks.

---

## Recommended Next Actions

1. **APPLY: Anthropic Fellows AI Security (#246) — DEADLINE APRIL 26** (highest priority, 4.7/5)
2. **APPLY: Anthropic Fellows ML Systems & Performance (#372) — DEADLINE APRIL 26** (new this scan, 4.1/5)
3. **APPLY: Anthropic Fellows AI Safety (#370) — DEADLINE APRIL 26** (already evaluated, 4.2/5)
4. **APPLY: Roadie AI Engineer Intern (#371)** — Remote, exact stack match, open deadline
5. **REVIEW: Anthropic Fellows AI Safety (5183044008)** — confirm if same track as #370 before separate application
6. Run `/career-ops pipeline` to process existing pending URLs
