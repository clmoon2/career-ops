# Portal Scan — 2026-04-13 (scan-v54)

**Agent:** Autonomous scan
**Scan version:** v54
**Previous scans today:** v50, v51, v52, v53 (extensive coverage already in history)

---

## Summary

| Metric | Count |
|--------|-------|
| WebSearch queries executed | 18 |
| Greenhouse API checks | 2 (Temporal 503, Factorial 503) |
| External repos checked | SimplifyJobs README, speedyapply AI repo |
| Companies/portals scanned | 25+ |
| New listings found (not in history) | 8 |
| Filtered by title (not relevant) | 5 |
| Skipped (duplicates) | ~50+ (extensive prior scanning today) |
| **New added to pipeline** | **8** |
| **Evaluated (score ≥ 4.0)** | **2** (NVIDIA new + Voleon missing report created) |

---

## Context

Today's scan (v54) ran after extensive prior scanning (v50–v53) that already covered most of portals.yml. The primary strategy for v54 was depth-first discovery of genuinely new listings:
- SimplifyJobs GitHub README (most recent additions)
- speedyapply 2026-AI-College-Jobs repo
- Adobe careers page (new role IDs not in history)
- NVIDIA Workday (new intern JD IDs JR2006826, JR2007644)
- TikTok/ByteDance lifeattiktok.com (new 2026 start listings)
- Cloudflare new intern roles (non-SWE filtered out)
- Targeted WebSearch for security/AI companies not yet checked

---

## ⭐ Evaluated (score ≥ 4.0)

### NEW — Written this scan:
| # | Company | Role | Score | Report |
|---|---------|------|-------|--------|
| 362 | NVIDIA | System Software Engineer Intern, AI Infrastructure (Summer 2026) | 4.1/5 | [362](362-nvidia-system-swe-intern-ai-infra-2026-04-13.md) |

### Previously Missing Report — Created this scan:
| # | Company | Role | Score | Report |
|---|---------|------|-------|--------|
| 361 | The Voleon Group | Software Engineer Intern (Summer 2026) | 4.1/5 | [361](361-voleon-swe-intern-2026-04-13.md) |

---

## 🔷 Priority Pending (score est. 3.7–4.0)

| Company | Role | URL | Est. Score | Notes |
|---------|------|-----|------------|-------|
| Adobe | 2026 Intern — Generative AI Software Engineer | [Link](https://careers.adobe.com/us/en/job/R162233/2026-Intern-Generative-AI-Software-Engineer) | ~3.8 | Firefly Foundry team; Python/LLMs; $45-55/hr; San Jose hybrid |
| TikTok | Security SWE Project Intern (Product Security) | [Link](https://lifeattiktok.com/search/7600535181632457013) | ~3.7 | $45-60/hr; pentests, security tooling, Go/Python/Rust; ByteDance brand risk |

---

## 🔸 Additional Pipeline Additions

| Company | Role | URL | Est. Score | Notes |
|---------|------|-----|------------|-------|
| NVIDIA | Software Engineering Intern, Omniverse | [Link](https://nvidia.wd5.myworkdayjobs.com/en-US/NVIDIAExternalCareerSite/job/Software-Engineering-Intern--Omniverse---Summer-2026_JR2007644) | ~3.5 | Robotics/simulation; less pipeline fit but NVIDIA brand |
| Adobe | 2026 AI/ML Intern — Machine Learning Engineer | [Link](https://careers.adobe.com/us/en/job/R158493/2026-AI-ML-Intern-Machine-Learning-Engineer) | ~3.5 | ML research track; San Jose; diffusion/LLM models |
| TikTok | SWE Project Intern (Content AI Infrastructure) | [Link](https://lifeattiktok.com/search/7621299118434961669) | ~3.5 | AI infra + distributed systems; ByteDance brand risk |
| TikTok | Backend SWE Intern (Privacy and Security) | [Link](https://lifeattiktok.com/search/7582152132208429365) | ~3.4 | Backend + privacy/security focus; ByteDance brand risk |

---

## Companies Checked — No New Listings

- Greenhouse API: Temporal (503), Factorial (503)
- All portals.yml companies: covered in v50–v53
- SimplifyJobs today additions: GoLinks (dup), Ampere/Hyundai (not relevant)
- Snap SWE Intern: **CLOSED** January 2026
- Datadog, NVIDIA JR2003206/JR2008503, Charles River Associates, Celonis, Booz Allen, Deloitte: already in history

---

## Recommended Next Actions

1. **Apply to NVIDIA AI Infrastructure Intern (report #362)** — rolling deadline, apply immediately. Lead with multi-model AI pipeline and LangChain agent work.
2. **Apply to Voleon Group (report #361)** — elite quant firm, $160K annualized. Lead with quant trading system (Bloomberg/Alpaca/Sharpe 1.79).
3. **Evaluate Adobe GenAI Intern** — run `/career-ops pipeline` to evaluate and decide on score
4. **Evaluate TikTok Security Intern** — $45-60/hr security match, but weigh ByteDance brand risk
5. **Process pipeline backlog** — 60+ priority pending roles from v41–v53 still unevaluated
6. **URGENT: Anthropic Fellows Program deadline APRIL 26, 2026** — must apply within 13 days

---

## Pipeline Health

- **Total evaluated:** 203 entries in applications.md
- **Pending in pipeline.md:** ~65+ unevaluated roles across priority bands
- **Top priority unprocessed:** OpenAI Systems Research Intern, Cohere ML Intern, Snowflake SE/Solution Engineer, CrowdStrike SWE Intern, Notion AI Intern, Databricks New Grad
