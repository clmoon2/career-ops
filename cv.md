# Carlos Luna-Peña

## Summary

Computer Science student at Texas A&M University (Cybersecurity Minor, Statistics Emphasis) who co-founded and shipped a live AI-powered job automation platform processing 100+ jobs/day. Sole backend architect of a 35,800-line Python codebase serving 46 API routes across a multi-model AI pipeline (Claude Sonnet, DeepSeek, Gemini, GPT-4o), with blue/green deployment on AWS EC2 and a 602-test suite. Led a 6-person engineering team building full-stack across Python, React, FastAPI, and Chrome extensions, with production infrastructure on AWS and Cloudflare, and hands-on ML work with LangChain, RAG, and multi-model pipelines. 673 GitHub contributions in the last year.

## Experience

### Co-Founder & Lead Developer -- Finch (ApplyEasy)
**Jan 2024 -- Present** | College Station, TX

- Architected a layered Flask backend (23,800 LOC, 43 API routes) with strict unidirectional dependency flow, serving a 7-stage AI pipeline that processes job applications end-to-end -- scraping, filtering, content generation, LaTeX compilation, ATS scoring, and PDF delivery
- Built a multi-model AI pipeline orchestrating 5 LLM providers (Claude Sonnet for profile enrichment, DeepSeek V3.2 for content generation, Gemini Flash Lite for filtering, GPT-4o-mini for cover letters) with cost optimization down to $0.003/application and $0.20-0.30 per 50-job run
- Designed a two-pass LLM enrichment pipeline (Claude Sonnet 4.6) that generates role-specific bullet variations across 26 career archetypes, with deterministic validation gates and automatic retry with temperature reduction on failure
- Implemented a deterministic multi-signal domain classifier routing candidates across 17 professional domains, with weighted scoring (degree, title, skills, summary) driving domain-specific resume section ordering, ATS keyword banks, and filter behavior
- Built an ATS scoring engine with 785 keywords, 417 aliases, and word-boundary matching across 17 domains, with a quality floor that drops generated resumes below threshold
- Engineered a stateless OAuth proxy (Google + GitHub) with HMAC-SHA256 CSRF protection and timing-safe signature verification (hmac.compare_digest), bypassing Texas A&M's Cisco Umbrella enterprise firewall blocking Supabase auth endpoints
- Built blue/green CI/CD on AWS EC2 with ALB routing, ECR image management, automated smoke testing, sub-second rollback via ALB rule swaps, and 5 GitHub Actions workflows with confirmation gates for production promotion
- Developed a Manifest V3 Chrome extension with dual-mode autofill: ATS-specific selectors (Greenhouse, Lever, Workday) plus a universal AI pipeline (GPT-4o-mini) for unknown sites, with React synthetic event bypass using native property descriptors
- Implemented defense-in-depth security: CORS origin restrictions, request ID tracing with sanitization, LaTeX injection prevention, PII-safe Sentry error tracking, honeypot/financial field detection, CSP lockdown, and sensitive storage key purging on logout
- Built a Cloudflare Workers edge API gateway with Hono proxying 20+ endpoints, OAuth redirect handling preventing edge cache poisoning, S3 signed URL server-side streaming, and adaptive endpoint discovery with caching
- Configured TLS 1.2/1.3 with ECDSA certificates and Mozilla-recommended cipher suites, enforcing HTTP-to-HTTPS redirects and disabling session tickets for forward secrecy
- Implemented distributed tracing with trace IDs propagating across Chrome extension content script, service worker, and backend, with field-level verification (expected vs actual DOM value)
- Built a three-source data merge system (LinkedIn + GitHub + PDF resume) with idempotent merge semantics, rollback support via stored enricher baselines, and configurable priority rules per field
- Designed a PostgreSQL admission control system with PL/pgSQL stored functions using row-level locking for race-condition-safe pipeline quota enforcement
- React 19 SPA frontend with zero-dependency state management via hook composition (usePipeline: 1,348 lines orchestrating pipeline lifecycle), lazy-loaded route splitting, and unified error registry with ~30 typed error codes

**Tech Stack:** Python, Flask, LangChain, React 19, Vite, TypeScript, Chrome Manifest V3, Hono, Cloudflare Workers, Supabase/PostgreSQL, AWS EC2, Docker, nginx, GitHub Actions, LaTeX, Sentry, PostHog, GPT-4o, Claude Sonnet, DeepSeek, Gemini

### Technical Lead & Full Stack / ML Engineer -- AIPHRODITE (Aggies Create)
**Sep 2024 -- Jan 2026** | College Station, TX

- Directed a 6-person engineering team through 2-week agile sprints with daily standups, backlog grooming, and structured PR reviews, reducing rework rate by 35%
- Architected a FastAPI backend with a PostgreSQL schema featuring composite indexes that reduced p95 query latency by 40%, serving CV embeddings and outfit recommendations across 500+ wardrobe items
- Built computer vision classification pipeline using OpenAI Vision API achieving 87% accuracy on garment category, color, and pattern detection, with embedding-based similarity search for outfit recommendations
- Built the Next.js/React/Tailwind CSS frontend, containerized all microservices with Docker, and configured GitHub Actions CI/CD to support a 6-person team shipping across a full FastAPI/PostgreSQL/Next.js stack
- Shipped across three delivery platforms: Next.js web app, React Native/Expo mobile app, and a Chrome extension for wardrobe capture

**Tech Stack:** FastAPI, Python, PostgreSQL, Prisma, LangChain, OpenAI Vision API, OpenAI Embeddings, Hugging Face Transformers, Next.js, React, React Native, Expo, TypeScript, Tailwind CSS, Docker, GitHub Actions

## Projects

### Quantitative Trading System
**Tech Stack:** Python, yfinance, pandas, numpy, vectorbt, FRED API, Alpaca API, Bloomberg (xbbg/pdblp), SQLite

- Designed and backtested a regime-aware quantitative trading system with 4 strategies (Earnings Drift PEAD with best Sharpe ratio 1.79, Momentum, Sector Rotation, Mean Reversion), automated paper trading via Alpaca, and VIX-based regime classification for position sizing
- Built three-phase architecture: home prep (Claude + free data), Bloomberg terminal session (TAMU trading room), and post-session analysis with trade journal in SQLite
- Implemented fractional share ordering, bracket orders, and risk management via Alpaca API for live paper trading

### TidalHack 2026 -- ILI Corrosion Prediction System
**Tech Stack:** Python, FastAPI, XGBoost, SHAP, DTW (scipy), DBSCAN (scikit-learn), AutoGen, Google Gemini, LangChain, Streamlit, SQLAlchemy, ReportLab, Pytest, Hypothesis

- Built an 11-step three-way analysis pipeline for pipeline corrosion prediction processing 5,115 anomalies in under 30 seconds with 96.5% match rate on anomaly alignment
- Implemented a 6-agent AI storytelling system (AutoGen + Google Gemini) for natural-language exploration of corrosion data, with full regulatory compliance reporting (49 CFR, ASME B31.8S)
- Architecture split 70/30 between proven algorithms (DTW alignment, DBSCAN clustering, Hungarian matching, XGBoost prediction) and LLM augmentation, validated at $2.5M-$25M cost savings per analysis

### Real-Time Interview Assistant
**Tech Stack:** Python, PyQt6, OpenAI Whisper, EasyOCR, mss, OpenRouter, asyncio

- Built a real-time AI assistant for virtual interviews with sub-second audio transcription (Whisper via WebRTC VAD), screen OCR capture, and context-aware LLM suggestions streamed via OpenRouter
- Engineered an invisible overlay using OS-level display affinity APIs (Windows SetWindowDisplayAffinity, macOS NSWindow.sharingType) excluded from screen-sharing software
- Designed async pipeline orchestrator (18K lines) coordinating audio capture, screen capture, LLM inference, and overlay rendering with system tray UI and hotkey management

### carlosOS -- Custom Unix Shell & Educational Operating System
**Tech Stack:** C, C++, x86 Assembly, QEMU, GDB, Make

- Built a minimal x86 bootloader and kernel in C/C++ and x86 Assembly featuring custom memory management, a round-robin process scheduler, a system call interface, and IPC mechanisms
- Implemented Unix-semantic fork, exec, pipe, and signal handling from scratch, then built a userland shell supporting pipelines, I/O redirection, and background job control

### Typing Habit Analyzer (Rust)
**Tech Stack:** Rust (rdev, rusqlite, clap, chrono, serde), Python, systemd, SQLite

- Built a Rust-based typing analytics daemon with keystroke capture via rdev, SQLite persistence, per-finger performance analysis, and adaptive practice drills targeting weak keys
- Runs as a systemd service with auto-start support, session history tracking, and export functionality

### Application Automation Engine
**Tech Stack:** Python, Playwright, playwright-stealth, OpenAI, SQLite, computer vision

- Engineered a browser automation engine for job applications with anti-detection stealth suite, CAPTCHA solving, AI-powered form completion (GPT-4o), and computer vision recovery for failed states
- Handles edge cases across 50+ ATS platforms with DOM extraction, pre-filtering of dead listings, and comprehensive stress testing

### Aggie Events -- Campus Event Discovery Platform
**Tech Stack:** TypeScript, Next.js, React, Tailwind CSS, Node.js, PostgreSQL, Docker, Google OAuth, GitHub Actions

- Built responsive Next.js/React components for event search, detail views, organization pages, and user settings in an 8-person team monorepo
- Extended PostgreSQL schema with composite indexes reducing p95 query latency by 40%; configured GitHub Actions CI/CD with automated linting, type-checking, and branch protection rules
- Implemented Google OAuth authentication with secure session cookies, CORS configuration, and environment-based secrets management

### LaTeX Resume Builder & GitHub Action
**Tech Stack:** TypeScript, LaTeX, GitHub Actions

- Developed a TypeScript CLI that compiles structured JSON resume data into ATS-optimized single-page LaTeX PDFs; published as a reusable GitHub Action that auto-builds and uploads PDF artifacts on every push
- Integrated as the resume generation engine inside Finch's n8n automation pipeline, enabling per-job tailored PDF output at scale

### OSS Contribution Scanner Bot
**Tech Stack:** Python, GitHub API, cron, JSON, Markdown

- Built an automated OSS contribution scanner monitoring 6+ major Python repos (LangChain, FastAPI, Pydantic, httpx, Starlette, Scrapy), ranking opportunities by effort level, and generating daily digests
- Supports quick scans (GitHub API) and deep scans (repo clone, coverage analysis, type hint checking, broken link detection) on daily/weekly cron schedules

### LangChain Job Automation Pipeline
**Tech Stack:** Python, LangChain, OpenAI (GPT-4o/4.1-mini), Google Sheets API, Google Slides API, Apify, AnyMailFinder API, LaTeX, GitHub API

- Architected a 12-stage LangChain pipeline automating the full job application lifecycle: LinkedIn scraping (Apify), AI fit-filtering (GPT-4.1-mini), tailored LaTeX resume generation (GPT-4o), PDF compilation, GitHub upload, Google Slides presentation, decision-maker email discovery (AnyMailFinder), and Google Sheets tracking

### Firelight FiApply -- gRPC Microservices Platform
**Tech Stack:** Python, gRPC, React PWA, LangChain, LangGraph, Playwright, PostgreSQL, pgvector, Docker

- Built a 4-service gRPC microservices platform (API Gateway, AI Orchestrator, RAG Engine, LLM Manager) for AI-powered job applications with a React PWA frontend and full Docker Compose orchestration

### LLM Adversarial Testing (AI Security Research)
**Tech Stack:** Python, LangChain, Venice AI API

- Conducted adversarial prompt injection testing against uncensored LLM models, testing multiple system prompt bypass techniques including fake model identity, developer mode simulation, and leaked transcript framing

## Hackathons

- **TidalHack 2026 (PRC Track):** Pipeline corrosion prediction with multi-agent AI -- 11-step pipeline, 6 AI agents, 96.5% match rate
- **TAMUhack 2025:** "Monee" -- gamified financial literacy app with savings challenges, CSV transaction parsing, and Gemini-powered advice (Next.js, Framer Motion)
- **HECM Hackathon 2024:** Raspberry Pi + 6-axis robotic arm demo (hardware project)

## Education

### Bachelor of Science in Computer Science -- Texas A&M University
**In Progress** | College Station, TX

- Cybersecurity Minor and Statistics Emphasis
- Relevant Coursework: Software Engineering, Algorithms, Operating Systems, Artificial Intelligence, Computer Security, Computer Systems, Data Structures
- xv6 OS kernel modifications (RISC-V), thread pool implementation with sanitizer testing, FIFO IPC client-server systems

## Technical Skills

**Languages:** Python, TypeScript, JavaScript, C, C++, Rust, SQL, Java, x86 Assembly, HTML, CSS, LaTeX

**Frameworks & Libraries:** React 19, Next.js, FastAPI, Flask, LangChain, Node.js, Hono, Tailwind CSS, Vite, Prisma, Hugging Face Transformers, React Native/Expo, Playwright, PyQt6

**AI/ML:** OpenAI API (GPT-4o), Claude Sonnet (Anthropic), DeepSeek, Google Gemini, RAG, Prompt Engineering, Computer Vision (OpenAI Vision API), OpenAI Embeddings, XGBoost, SHAP, AutoGen, Multi-Model AI Architecture, Whisper (speech-to-text), EasyOCR

**Infrastructure & Tools:** AWS EC2, Cloudflare Workers/Pages, Docker, PostgreSQL, Supabase, GitHub Actions (CI/CD), nginx, Linux, Git, Chrome Extension (Manifest V3), QEMU, GDB, Apify, Sentry, PostHog, Alpaca API, Bloomberg Terminal

**Security:** HMAC-SHA256 CSRF protection, OAuth proxy engineering, TLS 1.2/1.3 configuration, CORS policy design, CSP configuration, PII redaction, LaTeX injection prevention, anti-detection/stealth automation, adversarial LLM testing, distributed tracing

**Data & Analytics:** pandas, numpy, vectorbt, yfinance, SQLite, SQLAlchemy, FRED API, Google Sheets/Slides API
