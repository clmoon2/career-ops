# Cartesia — Intern (Software Engineer) | Summer 2026

**Score:** 4.0/5
**URL:** https://jobs.ashbyhq.com/cartesia/57126466-2554-4ae5-baa6-ea56e18db942
**PDF:** ❌
**Date:** 2026-04-12
**Verification:** unconfirmed (Ashby pages require JavaScript)

---

## Company Snapshot

Cartesia AI is the startup that invented **Mamba** (state-space models / SSMs), a transformer-alternative architecture that achieves linear-time inference with no attention overhead. Their research team (Albert Gu, Tri Dao, et al.) published foundational work on SSMs and are now commercializing it as a production AI inference platform — audio, speech, and language models that run efficiently anywhere, including edge devices.

- **Funding:** Seed/Series A — Index Ventures, Felicis, others (~$30M+)
- **Headcount:** ~30-50 (small, research-driven)
- **Mission:** "Build the next generation of real-time AI — ubiquitous, interactive intelligence that runs wherever you are"
- **Products:** Sonic (real-time TTS), Mamba-3 (SSM language model), inference APIs
- **Stack:** Go + Python backend, Next.js frontend, distributed ML serving

---

## Role Summary

**Intern (Software Engineer)** — building production inference infrastructure for SSM models.

Key responsibilities (from index job listing):
- Design and build low-latency, scalable model inference and serving stack for SSM foundation models
- Work across research → product translation: take research prototypes to deployed systems
- Build highly parallel data processing and evaluation infrastructure
- Bridge academic and applied research by making SSMs robust at scale

**Comp:** $8,000–$12,000/month (top 5% of all intern comp — adjusts by CoL and experience)
**Location:** Cambridge, MA (primary) or San Francisco, CA
**Duration:** Summer 2026 (implied ~12 weeks)

---

## Scoring Breakdown

### A. CV Match — 3.5/5

**Strengths:**
- Finch backend: 35K-line Python codebase serving 43 API routes, $0.003/job inference cost optimization — directly analogous to Cartesia's inference serving work
- Multi-model AI pipeline (5 LLM providers: Claude Sonnet, DeepSeek, Gemini, GPT-4o-mini) — experience routing and optimizing LLM calls at scale
- Cloudflare Workers edge API gateway with Hono: low-latency serving architecture is exactly what Cartesia needs for real-time AI
- AWS EC2 + Docker + nginx + blue/green CI/CD — production infrastructure Cartesia uses
- AIPHRODITE: FastAPI backend with composite indexes reducing p95 latency by 40% — performance engineering mindset
- carlosOS: custom x86 bootloader, kernel, scheduler, syscalls — demonstrates systems depth that SSM inference engineering requires
- 673 GitHub contributions, 602-test suite — strong engineering discipline

**Gaps:**
- No Go experience (main Cartesia backend language)
- No direct SSM/Mamba ML model knowledge
- No CUDA/GPU/kernel-level inference optimization
- No distributed ML serving at Cartesia's scale

Verdict: Strong backend + AI infra foundation, but the Go and SSM gaps are real. The inference serving architecture work at Finch (Cloudflare Workers + cost optimization pipeline) is the most direct analog.

### B. North Star Alignment — 4.0/5

Cartesia sits at the intersection of Carlos's AI/ML Engineering archetype (secondary) and AI Platform/LLMOps archetype. This is deeper than most AI internships — not building apps on top of OpenAI, but building the actual runtime that future AI apps will use. The company is at the frontier of AI architecture research.

Differentiation: Most interns are at companies that consume AI. Cartesia is building AI infrastructure at the model level — a rare opportunity that would stand out on a resume and accelerate understanding of how LLMs actually work.

### C. Compensation — 4.5/5

$8K–$12K/month = $96K–$144K annualized equivalent. This exceeds Carlos's target range ($80K–$120K FTE equivalent) and far clears the $70K minimum. Even at the lower bound ($8K/mo), this is among the highest-paying internships across all sectors.

Comparable: SafetyKit ($12.5K–$16.5K/mo), ThirdLayer ($6–$10K/mo), Ramp FDE ($11K/mo). Cartesia lands near the top of Carlos's intern comp distribution.

### D. Cultural Signals — 4.5/5

- Research-first culture: actual ML researchers in the founding team (Albert Gu, Tri Dao)
- Small team = high ownership, direct access to founders, rapid learning
- Working at the frontier (Mamba-3 just published, competing with GPT-4/Claude at architecture level)
- Index Ventures backing signals strong institutional confidence

### E. Red Flags — -0.5

- **Go gap**: Cartesia's backend is primarily Go. Carlos has Python, TypeScript, Rust — but no Go. Go is learnable in weeks, but it's a real onboarding cost.
- **SSM knowledge required**: Interns will need to understand why SSMs are different from transformers, how Mamba handles state, etc. Not insurmountable but requires self-study.
- **Small team risk**: Fewer people = less structured mentorship, higher expectations on self-sufficiency.

### Global Score: 4.0/5

Exceptional company, exceptional comp, legitimate skill match at the infrastructure level. Go gap reduces it from a 4.5 — but the Python/systems/AI infra foundation is solid enough to make Carlos a competitive candidate.

---

## Application Strategy

**Should apply:** Yes — immediately. This is a top-5 opportunity in the current pipeline.

**Proof points to lead with:**
1. **Finch inference pipeline**: "Optimized multi-model AI pipeline to $0.003/application — Claude Sonnet, DeepSeek, Gemini, GPT-4o-mini — with cost modeling and dynamic provider routing." Maps directly to Cartesia's inference cost + serving problems.
2. **Cloudflare Workers edge gateway**: "Built edge API layer with adaptive endpoint discovery and sub-100ms request routing." Shows low-latency serving experience.
3. **Blue/green CI/CD on AWS**: "Automated smoke testing, sub-second rollback via ALB rule swaps." Shows production infrastructure discipline.
4. **carlosOS**: "Built x86 kernel from scratch in C/x86 assembly with custom scheduler and syscall interface." Demonstrates systems depth.

**Address Go gap proactively**: "Primary language is Python + TypeScript, actively learning Go — completed [X] before start date" (actually do a Go tour and small project before applying).

**Cover letter hook**: Quote Mamba-3's stated advantage ("2x smaller states, enhanced MIMO decoding efficiency") and connect it to Carlos's cost-optimization work at Finch. Shows genuine technical interest.

---

## Next Actions

- [ ] Apply at https://jobs.ashbyhq.com/cartesia/57126466-2554-4ae5-baa6-ea56e18db942
- [ ] Learn Go basics before submitting (tour.golang.org, one small project)
- [ ] Read Mamba paper (arxiv.org/abs/2312.00752) and Mamba-3 blog post
- [ ] Tailor CV to lead with inference pipeline + edge serving + systems depth
- [ ] Write cover letter citing specific Cartesia research
