# Portal Scan — 2026-04-12 (v38)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Scan version:** v38
**Date:** 2026-04-12
**Method:** Freshness sweep via speedyapply/2026-AI-College-Jobs (April 12 "0d" listings) + Actian Lever portal + Okta Playwright check + Dev Technology Greenhouse
**Context:** Continuation of v37 scan (April 11). Pipeline heavily saturated after 7 days of scanning — focus on new postings only.

---

## Results

| Metric | Count |
|--------|-------|
| Sources checked | 6 (speedyapply GitHub, Actian Lever, Greenhouse, BrowserOS YC, Output Biosciences Ashby, Okta) |
| Total URLs evaluated | 11 |
| Filtered by title (PhD/non-technical) | 2 |
| Closed / 404 | 2 |
| Duplicate (already in history) | 2 |
| **New added to pipeline** | **5** |
| Reports written (score >= 4.0) | 2 |

---

## New Listings Added to Pipeline

### Top Matches (Reports Written)

| # | Company | Role | Score | Comp | Report |
|---|---------|------|-------|------|--------|
| 293 | Replit | Software Engineer - New Grad (Summer 2026) | 4.5/5 | $140-180K + equity | [293](293-replit-swe-newgrad-2026-04-12.md) |
| 294 | BrowserOS | ML Research Engineer Intern | 4.2/5 | $6-10K/mo | [294](294-browseros-ml-research-intern-2026-04-12.md) |

### Secondary Additions (Pipeline Only)

| Company | Role | Score | Notes |
|---------|------|-------|-------|
| Actian | DevOps Backstage Intern | 3.5/5 | Remote; 12-week June 8; Kubernetes/CI/CD |
| GR0 | Applied AI Engineering Intern | ~3.0/5 | LA; 403 on fetch — verify JD before applying |
| Booz Allen Hamilton | AI Data Analyst Intern | 2.5/5 | Part-time; Secret clearance required; low priority |

---

## Skipped

| Company | Role | Reason |
|---------|------|--------|
| Output Biosciences | ML Research Intern | PhD required |
| Waypoint Transit | SWE Intern Summer 2026 | 404 — closed |
| Dev Technology | React/Node Application Developer Intern | Job not found — closed |
| Actian | AI Solutions Intern | Already in scan history |
| Actian | Engineering Intern, Pipeline Observability | Already in scan history |
| Okta | Digital Success Intern 2026 | Non-technical business role |

---

## Top Priority Actions

1. **Apply to Replit ASAP** — $140-180K new grad, AI agents + full-stack TS/React/Python exact match. Hybrid Foster City CA. Report: 293.

2. **Apply to BrowserOS** — YC S24 agentic browser, $6-10K/mo. Chrome MV3 + TypeScript + browser agents = rare triple match. Submit TypeScript project links. Report: 294.

3. **Work through existing priority queue** — Cloudflare Austin SWE (4.8/5), Together AI (4.5/5), Glean (4.1/5), Obsidian Security (4.0/5), Apple InfoSec (4.0/5) — these are still open, apply before they close.

---

## Pipeline Health

- scan-history.tsv: 1,502 entries (was 1,491 before this scan)
- pipeline.md: Updated with v38 section at top
- reports/: 293, 294 written today
- batch/tracker-additions/: 293-replit-swe-newgrad.tsv, 294-browseros-ml-research-intern.tsv

Run `node merge-tracker.mjs` to sync tracker additions into applications.md
Run `/career-ops pipeline` to evaluate remaining pending URLs
