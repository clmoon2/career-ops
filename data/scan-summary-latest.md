# Portal Scan — 2026-04-21 (v147)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Scan:** v147 (147th consecutive exhaustive scan)
**Date:** 2026-04-21
**Market status:** Summer 2026 FULLY SATURATED

## Portals scanned

| Source | Method | Result |
|--------|--------|--------|
| Greenhouse APIs (Anthropic/Airtable/Vercel/Glean/Arize/RunPod/Temporal/HumeAI/Intercom) | API | All 503 (intermittent outage) |
| Greenhouse board pages | WebFetch | All 503 |
| Ashby (jobs.ashbyhq.com) | WebSearch | All dup v7–v146 |
| Greenhouse boards (job-boards.greenhouse.io) | WebSearch | All dup v7–v146 |
| Lever (jobs.lever.co) | WebSearch | All dup v7–v146 |
| SimplifyJobs (github.com/SimplifyJobs) | WebFetch | Same top-50 as v146 — all dup/non-target |
| SpeedyApply SWE + AI repos | WebSearch | All dup v7–v146 |
| Y Combinator / Work at a Startup | WebSearch | All dup v30–v146 |
| Wellfound (wellfound.com) | WebSearch | All dup v7–v146 |
| HackerNews "Who is Hiring?" April 2026 | WebFetch | 503 Service Unavailable |
| Jobright.ai | WebSearch | All dup v7–v146 |
| **NEW: Circle careers (careers.circle.com)** | WebSearch | **2 new URLs found** |

## Results

```
Queries executed:    20+
Listings found:      3277 total in scan-history (9 new entries added)
Duplicated:          3275 (already in history)
New added to pipeline: 2 (both below 4.0/5 threshold)
Reports filed:       0
```

## New listings (below threshold)

| Company | Role | Score | Notes |
|---------|------|-------|-------|
| Circle (CRCL) | Intern, Application Security | ~3.5/5 | Remote; May 26–Aug 14; CodeQL+AI agents+CI/CD AppSec; **crypto/blockchain domain filter** |
| Circle (CRCL) | Software Engineer, Intern (Summer 2026) | ~3.0/5 | Remote; generic SWE; **crypto domain filter** |

**Why Circle is below threshold:** Circle.com is the issuer of USDC stablecoin. The portals.yml explicitly filters out `Blockchain` and `Crypto` domain roles. The AppSec role itself is well-matched technically (CodeQL, AI agent security tooling, CI/CD — direct overlap with Carlos's security engineering work), but the company's core business triggers the domain filter. Score capped at ~3.5/5.

## Top matches (score ≥ 4.0) — NONE NEW this scan

All high-scoring roles are from previous scans. **Urgent action items:**

| Priority | Role | Score | Deadline | Report |
|----------|------|-------|----------|--------|
| ⚡ URGENT | Anthropic — AI Security Fellow | 4.7/5 | **Apr 26 (5 DAYS)** | #246 |
| ⚡ URGENT | Anthropic — AI Safety Fellow | 4.2/5 | **Apr 26 (5 DAYS)** | #370 |
| ⚡ URGENT | Anthropic — ML Systems Fellow | 4.1/5 | **Apr 26 (5 DAYS)** | #372 |
| ⚡ HIGH | ByteDance — AI Security Intern (San Jose) | 4.3/5 | Apply ASAP | #388 |
| HIGH | Netflix — SWE Intern (Summer 2026) | 4.2/5 | Apply ASAP | #391 |
| HIGH | TikTok — Product Security Intern | 4.0/5 | Apply ASAP | #392 |
| MEDIUM | Verkada — Security SWE New Grad 2026 | 4.1/5 | Apply ASAP | #389 |
| MEDIUM | Rockstar Games — Security Eng Automation Intern | 4.0/5 | Apply ASAP | #390 |

## Recommended next actions

1. **IMMEDIATELY** apply to Anthropic Fellows AI Security (#246, 4.7/5) — deadline April 26
2. **IMMEDIATELY** apply to Anthropic Fellows AI Safety (#370, 4.2/5) — deadline April 26
3. **IMMEDIATELY** apply to Anthropic Fellows ML Systems (#372, 4.1/5) — deadline April 26
4. Apply to ByteDance AI Security Intern (#388, 4.3/5) — rolling deadline, apply this week
5. Apply to Netflix SWE Intern (#391, 4.2/5) — rolling, competitive, apply soon
6. Review Circle AppSec Intern (pipeline, ~3.5/5) — if crypto domain is acceptable, upgrade score

## Scan health

- **Greenhouse APIs:** All 503 (intermittent daily outages). Resume L2 scanning when APIs stabilize.
- **Summer 2026 market:** Fully saturated after 147 consecutive scans. Most deadlines have passed or positions filled.
- **Fall 2026 opportunities:** Limited — Center for AI Safety Research Eng (deadline May 29) is still open. Consider expanding Fall 2026 co-op search.
- **New grad 2026 opportunities:** Still open at Replit, Airtable, Decagon, Benchling, Harvey, Glean, Palantir, Mistral AI, Cohere, Pinecone, Vapi — all in pipeline/evaluated.

→ Run `/career-ops pipeline` to evaluate any pending pipeline items.
→ Run `/career-ops oferta` with an Anthropic Fellows JD to begin applying immediately.
