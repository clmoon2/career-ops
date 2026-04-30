# Report #421 — Loop | 2026 New Grad | Software Engineer, Full-Stack

**Score:** 4.0/5
**URL:** https://job-boards.greenhouse.io/loop/jobs/5780582004
**Also available:** Chicago ($125K) https://job-boards.greenhouse.io/loop/jobs/5981831004 | NYC https://job-boards.greenhouse.io/loop/jobs/5981828004
**PDF:** ❌
**Status:** Evaluated
**Date:** 2026-04-30

---

## Company

Loop is a supply chain data platform using AI to structure unorganized logistics data (PDFs, invoices, emails) for enterprise customers. The platform unlocks "profits trapped in the supply chain" via AI-driven audit and payment automation. Engineering-heavy, AI-native, and tool-forward — they explicitly expect Claude Code and Cursor proficiency from new grads on Day 1.

## Role

Full-stack software engineer for 2026 graduates. 9-month rotation program: first 3 months = 3 entry-level projects with increasing scope; months 4-9 = cross-team rotation (Platform, Core Product, Commercial, or Special Projects). Evaluated for mid-level performance at month 9+. Production code ships on Day 1. Work spans frontend → LLM agents → databases → event infrastructure.

**Location:** San Francisco CA (4 days/week in-office)
**Comp:** $150,000 base + full benefits (health, 401k match, unlimited PTO, professional dev budget)
**Chicago variant:** $125,000 base | **NYC variant:** comp likely SF parity or close

## Score Breakdown

| Dimension | Score | Notes |
|-----------|-------|-------|
| Match con CV | 4.5/5 | Exact stack match: Python/Flask → React 19/TypeScript → PostgreSQL → LLM pipelines → AWS/Docker/CI/CD. Finch is nearly identical architecture at 35K lines. Carlos already uses Claude Code (this system). |
| North Star | 3.5/5 | "Agentic/Automation" archetype — LLM agents automating complex enterprise data workflows. Supply chain domain isn't pure AI/security but engineering is identical. |
| Comp | 5.0/5 | $150K SF for new grad = top quartile (above profile.yml $120K ceiling). Excellent. |
| Cultural signals | 4.0/5 | Ship-on-Day-1, Claude Code-native culture, self-directed builders, intensive rotation. Perfect match for Carlos's hacker pace. |
| Red flags | -0.5 | FTE requires graduation (verify TAMU expected graduation date); 4d/week in-office = relocation from College Station required; supply chain domain ~= moderate mismatch with AI/security trajectory. |
| **Global** | **4.0/5** | Worth applying. Strong stack match + elite comp overcomes domain gap. |

## CV → JD Mapping

| JD Requirement | Carlos's Proof Point |
|----------------|---------------------|
| Full-stack production systems | Finch: 35,800-line Python backend (43 API routes) + React 19 SPA + TypeScript Chrome extension |
| LLM agents & AI pipelines | Multi-model pipeline: Claude Sonnet (enrichment) + DeepSeek V3 (content gen) + Gemini Flash (filtering) + GPT-4o-mini (cover letters) at $0.003/application |
| Databases (PostgreSQL, event infra) | PostgreSQL admission control with PL/pgSQL stored functions + row-level locking; Supabase; SQLite |
| AWS infrastructure & Docker | Blue/green CI/CD on AWS EC2 with ALB routing, ECR, Docker, 5 GitHub Actions workflows |
| AI-native tools (Claude Code, Cursor) | Building this evaluation system with Claude Code; uses Cursor daily |
| Self-directed builder with side projects | Co-founder of Finch (live product, 100+ jobs/day); 673 GitHub contributions; multiple hackathon projects |
| Ships fast under pressure | TidalHack: 11-step pipeline + 6-agent AI system built in 24hrs |
| Understanding of LLM strengths/limitations | Two-pass enrichment pipeline with deterministic validation gates + auto-retry with temperature reduction |

## Ideal Opening Pitch (for Cover Letter / Application)

> I've built exactly what Loop builds — a production AI pipeline that structures messy, unstructured data into automated workflows. At Finch, I architected a 35,800-line Python backend orchestrating five LLM providers (Claude, DeepSeek, Gemini, GPT-4o) that processes 100+ job applications per day end-to-end, from raw text to formatted PDF with ATS scoring. The pipeline is cost-optimized to $0.003/application running on blue/green AWS infrastructure with 602 automated tests. Loop is applying that same pattern to supply chain data — and I use Claude Code every day, exactly as you'd expect from a Day 1 contributor.

## ⚠️ Pre-Application Checklist

1. **Verify graduation date** — This is FTE for 2026 grads. Confirm TAMU expected graduation (May/December 2026 vs 2027).
2. **Relocation** — SF (4d/wk) requires move from College Station. Chicago ($125K, 4d/wk) is lower cost of living if budget-sensitive.
3. **NYC variant** — Check comp for NYC posting (5981828004); likely SF-parity.
4. **Apply to all three locations** — Separate Greenhouse applications; optimize for SF or Chicago based on graduation timing.

## STAR Story (Finch → Loop mapping)

**Situation:** Building Finch — an AI job automation SaaS processing 100+ applications/day.
**Task:** Architect a production multi-model LLM pipeline that structures raw job postings + user profiles into tailored PDF resumes and cover letters.
**Action:** Designed a 7-stage pipeline (scrape → filter → enrich → generate → ATS-score → compile → deliver) orchestrating 5 LLM providers with cost optimization, deterministic validation gates, and blue/green AWS CI/CD — 35K lines, 602 tests.
**Result:** Live product serving real users at $0.003/application. Same architecture Loop uses for supply chain data: messy inputs → structured AI outputs → enterprise workflows.
**Reflection:** Learned that multi-model orchestration requires deterministic fallbacks, not just prompt engineering — exactly the reliability challenges Loop faces at scale.
