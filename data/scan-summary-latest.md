# Portal Scan Summary — 2026-04-10 (v21)

**Run type:** Autonomous agent — incremental scan
**Previous scan:** v20 (2026-04-10, same day — this run found companies/listings not covered by v20)

---

## Stats

| Metric | Count |
|--------|-------|
| Queries executed | 18 |
| Companies/portals checked | 20+ |
| Raw URLs found | ~35 |
| Already seen (history) | ~22 |
| Filtered (geo/seniority/closed) | 8 |
| **New listings added to pipeline** | **8** |
| Full evaluations written | 1 |

---

## New Listings Added to Pipeline

| # | Company | Role | Est. Score | Notes |
|---|---------|------|-----------|-------|
| ⭐ | **Mechanize** | Software Engineering Intern | **4.6/5** | $100/hr — highest rate in all scans; RL eval infra for frontier AI labs |
| + | Cloudflare | AI Automation Intern (M&A) | ~3.5 | $24/hr; build LLM agents at Cloudflare; Austin/SF/NYC |
| + | TransMarket Group | DevOps/SRE Intern | ~3.5 | Chicago; quant trading; Python+Docker+CI/CD |
| + | Cloudflare | Research Engineer Intern | ~3.2 | Austin; security/crypto/systems research; Rust/C/Go preferred |
| + | Allen Institute for AI | Research Internship (Agentic LLMs) | ~3.3 | Seattle; agentic LLM research; research background preferred |
| + | 10a Labs | AI Red Teamer (Entry Level) | ~3.3 | NYC/SF/DC; entry-level red team AI; verify full-time vs intern |
| + | Vapi | Infrastructure Engineer - Security | ~3.2 | Full-time (not intern); security at voice AI infra; verify new-grad eligibility |
| + | Primer | Spring/Summer 2026 Engineering Intern | ~3.3 | NLP for defense/intel; verify location + clearance req |

---

## Evaluated This Run

### ⭐ Mechanize — Software Engineering Intern (4.6/5)
**Report:** [281](reports/281-mechanize-swe-intern-2026-04-10.md)
**URL:** https://jobs.ashbyhq.com/mechanize/d148d54f-6db7-4c28-9699-0304596f554e

The standout find of this scan cycle. Mechanize builds RL evaluation environments used by frontier AI labs to train and evaluate coding models. $100/hour is the highest intern compensation seen across all 281 evaluations in this system.

Why it's a near-perfect match:
- Adversarial LLM testing project on CV = exact skill match for "analyze where models fail"
- 35K-line Python production codebase = Python proficiency at scale
- Multi-model AI pipeline ($0.003/app) = deep LLM behavior intuition
- ATS scoring engine (785 keywords, quality floor) = grading infrastructure experience

Only constraint: SF on-site. Relocation required from College Station TX. At $100/hr for 12 weeks, economically justified.

**→ Apply immediately. Top opportunity in the v21 scan.**

---

## Filtered / Skipped

| URL | Company | Reason |
|-----|---------|--------|
| ...cloudflare.../7574676 | Cloudflare | Cannot verify — likely closed or London track |
| ...grammarly.../7491439 | Grammarly | 404 — listing closed |
| ...willowtree.../8094349002 | TELUS Digital | 404 — listing closed |
| ...baringa.../4778983101 | Baringa | UK-based, no US role |
| ...perplexity.../b9e1ff | Perplexity | Berlin internship — geo-excluded |
| ...perplexity.../79a07e | Perplexity | UK internship — geo-excluded |
| ...digs.../4663936006 | Digs | Spring 2026 only — timing miss |

---

## Companies Checked This Run

**WebSearch portals scanned:**
- Ashby: Mechanize, Vapi, Primer, Perplexity, Replit (new grad), Notion (fall), Giga, Zettabyte
- Greenhouse: Cloudflare (all tracks), TransMarket Group, Allen Institute for AI, 10a Labs, Grammarly, TELUS Digital/WillowTree, Baringa, Bandwidth, Zscaler, Gemini, Rockstar (sec ops), Dark Wolf, C3 AI, Glean, Pendo, Mercury, xAI
- Lever: Mistral AI (FDE intern, new grad), Weights & Biases (no intern listings found), Symmetry Systems, Voleon, Shield AI
- Salesforce: confirmed already in v20 history (jr308796, jr326948, jr313214)
- Sierra: confirmed already in v20 history (8bb2509d)

---

## Recommended Next Actions

1. **Apply to Mechanize** — immediately. Top priority. Cover letter: adversarial LLM testing + ATS scoring engine as grading infrastructure.
2. **Evaluate Cloudflare AI Automation Intern** — $24/hr is low but Cloudflare brand + LLM agent project may be worth it.
3. **Check 10a Labs AI Red Teamer** — confirm if entry-level full-time vs intern. Cybersecurity minor is a strong match.
4. **Evaluate TransMarket Group DevOps** — Chicago quant firm, Python+Docker, solid secondary-archetype fit.
5. **Run `/career-ops pipeline`** to process 50+ pending entries from v17-v21 scans.

---

*Run pipeline: `/career-ops pipeline`*
*View all pending: `data/pipeline.md`*
*Health check: `node verify-pipeline.mjs`*
