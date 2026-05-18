<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00FF99,100:0d1117&height=220&section=header&text=GEREMY%20SALAS&fontSize=50&fontColor=00FF99&fontAlignY=35&desc=Backend%20Engineer%20%7C%20SaaS%20Architect%20%7C%20Enterprise%20Systems&descSize=16&descColor=8b949e&descAlignY=55&animation=fadeIn" width="100%" />

<!-- TYPING ANIMATION -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=00FF99&center=true&vCenter=true&repeat=true&width=750&height=35&lines=Backend+Engineer+from+Ecuador+%7C+Building+production-grade+SaaS;Obsessed+with+scalable+architecture+%26+enterprise+security;From+idea+to+deployed+infrastructure+%E2%80%94+end+to+end;Python+%2B+TypeScript+%7C+FastAPI+%2B+Next.js+%7C+PostgreSQL+%2B+Redis)](https://git.io/typing-svg)

</div>

<!-- DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ABOUT ME -->
<table>
<tr>
<td width="50%" valign="top">

### `> whoami`

```yaml
name: Geremy Salas
role: Backend Engineer & SaaS Builder
location: Ecuador
focus:
  - Enterprise multi-tenant architecture
  - Scalable backend systems
  - Security-first infrastructure
  - AI-powered integrations
currently_building:
  - KONTRAX  — Enterprise contractor management SaaS
  - NOVADIFY — Full-service accommodation & tourism platform
philosophy: "Ship production-grade code, not prototypes"
```

</td>
<td width="50%" valign="top">

### `> cat tech_stack.yml`

**Backend & Infrastructure**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00FF99)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=00FF99)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=00FF99)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=00FF99)
![Celery](https://img.shields.io/badge/Celery-0d1117?style=flat-square&logo=celery&logoColor=00FF99)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-0d1117?style=flat-square&logo=sqlalchemy&logoColor=00FF99)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=00FF99)
![AWS](https://img.shields.io/badge/AWS_S3-0d1117?style=flat-square&logo=amazons3&logoColor=00FF99)
![Supabase](https://img.shields.io/badge/Supabase-0d1117?style=flat-square&logo=supabase&logoColor=00FF99)

**Frontend & UI**

![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=00FF99)
![Next.js](https://img.shields.io/badge/Next.js_15-0d1117?style=flat-square&logo=next.js&logoColor=00FF99)
![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=00FF99)
![TailwindCSS](https://img.shields.io/badge/Tailwind-0d1117?style=flat-square&logo=tailwindcss&logoColor=00FF99)
![Zustand](https://img.shields.io/badge/Zustand-0d1117?style=flat-square&logo=react&logoColor=00FF99)
![ShadcnUI](https://img.shields.io/badge/Shadcn_UI-0d1117?style=flat-square&logo=shadcnui&logoColor=00FF99)

**Integrations & DevOps**

![Stripe](https://img.shields.io/badge/Stripe-0d1117?style=flat-square&logo=stripe&logoColor=00FF99)
![PayPal](https://img.shields.io/badge/PayPal-0d1117?style=flat-square&logo=paypal&logoColor=00FF99)
![DocuSign](https://img.shields.io/badge/DocuSign-0d1117?style=flat-square&logo=docusign&logoColor=00FF99)
![Google Gemini](https://img.shields.io/badge/Gemini_AI-0d1117?style=flat-square&logo=google&logoColor=00FF99)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=flat-square&logo=githubactions&logoColor=00FF99)
![Playwright](https://img.shields.io/badge/Playwright-0d1117?style=flat-square&logo=playwright&logoColor=00FF99)
![Pytest](https://img.shields.io/badge/Pytest-0d1117?style=flat-square&logo=pytest&logoColor=00FF99)

</td>
</tr>
</table>

<!-- DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- FEATURED PROJECTS -->
<div align="center">

## `// FEATURED PROJECTS`

</div>

<!-- KONTRAX -->
<table>
<tr>
<td>

### <img src="https://img.shields.io/badge/PUBLIC-00FF99?style=flat-square&logoColor=white" /> KONTRAX &mdash; Enterprise Contractor Management SaaS

[![Kontrax CI](https://github.com/geremyjampiersalasgarcia-eng/Kontrax/actions/workflows/ci.yml/badge.svg)](https://github.com/geremyjampiersalasgarcia-eng/Kontrax/actions)

> Multi-tenant B2B SaaS platform for enterprise contractor lifecycle management.
> Zero Trust security model with bank-grade KYC verification, automated legal workflows via DocuSign embedded signing, and real-time operational governance dashboards.

<details>
<summary><b>Architecture & Technology Matrix</b></summary>
<br>

| Layer | Technology | Purpose |
|:------|:-----------|:--------|
| **API** | FastAPI + Pydantic v2 + SQLAlchemy 2.0 | Async REST API with strict DTO validation |
| **Database** | PostgreSQL + Alembic | Multi-tenant isolation with migration control and soft-delete |
| **Cache / Queue** | Redis + Celery + Celery Beat | Background jobs, SLA monitoring (72h), exponential backoff retries |
| **Frontend** | Next.js 15 + TypeScript + Shadcn UI | App Router, SSR, i18n (next-intl), Zustand + TanStack Query |
| **Identity** | Stripe Identity | Bank-grade KYC with biometric facial verification |
| **Contracts** | DocuSign (Embedded Signing) | Legally binding e-signatures via in-app iframe rendering |
| **Storage** | AWS S3 / Supabase Storage | Encrypted document vault with presigned URL upload/download |
| **Email** | Resend + Jinja2 | Transactional emails with branded HTML templates |
| **Security** | AES-256 + RBAC + Zero Trust | Military-grade encryption, immutable audit logs, brute-force detection |
| **CI/CD** | GitHub Actions + Pytest + Playwright | Automated backend tests and full E2E browser simulation |

</details>

<details>
<summary><b>Core Capabilities</b></summary>
<br>

- **Multi-Tenant B2B Isolation** &mdash; Strict `tenant_id` segmentation, dynamic subdomain branding (`agency.kontrax.com`), GDPR/CCPA compliant
- **RBAC Authorization** &mdash; Four-tier role system: System Admin / Admin / Operator / Contractor
- **5-Step Onboarding Pipeline** &mdash; Personal Data > Documents (S3) > Contract (DocuSign Embedded) > Payment > KYC (Stripe Identity)
- **Real-Time Operator Dashboard** &mdash; Recharts analytics, SLA monitoring (72h), conversion funnels, weekly activity tracking
- **Post-Onboarding Workspace** &mdash; Task assignment with priority levels (Low/Medium/High/Critical), deliverable uploads, approval workflows
- **Celery Workers** &mdash; Async email dispatch with exponential backoff, SLA auto-close via Celery Beat cronjobs
- **Immutable Audit Trail** &mdash; Every action logged with actor ID, timestamp, IP, previous vs. new state
- **Internationalization** &mdash; Full ES/EN support with runtime locale switching (next-intl)
- **Business Intelligence** &mdash; CSV report export for talent rosters, assignment history, and audit summaries

</details>

<div align="center">

[![View Repository](https://img.shields.io/badge/View_Repository-0d1117?style=for-the-badge&logo=github&logoColor=00FF99)](https://github.com/geremyjampiersalasgarcia-eng/Kontrax)
![Commits](https://img.shields.io/badge/145+_Commits-0d1117?style=for-the-badge&logo=git&logoColor=00FF99)
![Status](https://img.shields.io/badge/Status:_Production-0d1117?style=for-the-badge&logo=statuspage&logoColor=00FF99)

</div>

</td>
</tr>
</table>

<br>

<!-- NOVADIFY -->
<table>
<tr>
<td>

### <img src="https://img.shields.io/badge/PRIVATE-8b949e?style=flat-square&logoColor=white" /> NOVADIFY &mdash; Full-Service Accommodation & Tourism Platform

> Production-ready full-stack platform inspired by Airbnb, purpose-built for the Ecuadorian market.
> Connects Hosts, Tourists and Administrators with integrated AI travel assistant, real-time PayPal payments, automated PDF invoicing, and Google Analytics 4.

<details>
<summary><b>Architecture & Technology Matrix</b></summary>
<br>

| Layer | Technology | Purpose |
|:------|:-----------|:--------|
| **Framework** | Next.js 15 (App Router) | SSR engine, Edge API Routes, `generateMetadata` for SEO |
| **Language** | TypeScript 5+ | Static typing across the entire codebase |
| **Database** | Supabase (PostgreSQL) | RLS policies, SQL triggers for auto-rating, real-time subscriptions |
| **Auth** | Supabase Auth + Google OAuth | Magic Link and Social Login |
| **AI** | Google Gemini 1.5 | Conversational travel assistant with NLP-driven recommendations |
| **Payments** | PayPal React SDK | Secure USD payment capture with transaction audit trail |
| **PDF** | @react-pdf/renderer | Server-side A4 invoice generation with corporate branding |
| **Email** | Resend | HTML booking confirmations, host alerts, review prompts |
| **State** | Zustand + TanStack React Query | Global state management + optimistic UI updates |
| **Styles** | Tailwind CSS 4+ | Design system with Zero Layout Shift route architecture |
| **Analytics** | Recharts + Google Analytics 4 | Admin SVG dashboards + real-time traffic metrics |
| **Testing** | Vitest + Playwright | Unit tests + E2E browser simulation (Desktop + Mobile) |
| **CI/CD** | GitHub Actions | Lint > TSC > Unit > E2E > Vercel deploy pipeline |

</details>

<details>
<summary><b>Core Capabilities</b></summary>
<br>

- **Unified Super App Ecosystem** &mdash; Accommodations + Cultural Experiences + Private Services (Chefs, Mixology, Wellness) in one platform
- **Three-Tier RBAC** &mdash; Tourist / Host / Admin enforced at Edge Middleware + PostgreSQL RLS simultaneously
- **Zero Layout Shift Architecture** &mdash; `(home)` Route Group with persistent Navbar, dual-mode scroll transitions, SVG icon system
- **AI Travel Assistant** &mdash; Gemini-powered conversational interface reading live property data for personalized recommendations
- **Host Financial Wallet** &mdash; Dynamic revenue dashboard with automated commission calculation
- **PayPal Checkout Flow** &mdash; Dates > Summary > PayPal Capture > Email Dispatch > PDF Invoice Download
- **Self-Healing Database** &mdash; SQL triggers auto-recalculate property/experience ratings on every review insert
- **Wishlist Engine** &mdash; Real-time heart favoriting with instant visual feedback and RLS protection
- **Server Components Refactor** &mdash; SSR property pages with `generateMetadata`, isolated Client Components for interactivity
- **Optimistic UI** &mdash; TanStack Query `useMutation` for instant booking confirmations without full-page reloads

</details>

<div align="center">

![Status](https://img.shields.io/badge/Status:_Production-0d1117?style=for-the-badge&logo=statuspage&logoColor=00FF99)
![Access](https://img.shields.io/badge/Access:_Private_Repository-0d1117?style=for-the-badge&logo=lock&logoColor=8b949e)

</div>

</td>
</tr>
</table>

<!-- DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- GITHUB ANALYTICS -->
<div align="center">

## `// GITHUB ANALYTICS`

<br>

<a href="https://github.com/geremyjampiersalasgarcia-eng">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=geremyjampiersalasgarcia-eng&show_icons=true&theme=chartreuse-dark&bg_color=0d1117&hide_border=true&icon_color=00FF99&title_color=00FF99&text_color=8b949e&ring_color=00FF99" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=geremyjampiersalasgarcia-eng&layout=compact&theme=chartreuse-dark&bg_color=0d1117&hide_border=true&title_color=00FF99&text_color=8b949e" />
</a>

<br><br>

<!-- STREAK STATS -->
<a href="https://github.com/geremyjampiersalasgarcia-eng">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=geremyjampiersalasgarcia-eng&theme=chartreuse-dark&background=0d1117&hide_border=true&ring=00FF99&fire=00FF99&currStreakLabel=00FF99&sideLabels=8b949e&dates=8b949e&currStreakNum=00FF99&sideNums=00FF99" />
</a>

<br><br>

<!-- TROPHIES -->
<a href="https://github.com/geremyjampiersalasgarcia-eng">
  <img src="https://github-profile-trophy.vercel.app/?username=geremyjampiersalasgarcia-eng&theme=matrix&no-bg=true&no-frame=true&column=7&margin-w=10" />
</a>

<br><br>

<!-- CONTRIBUTION GRAPH -->
<a href="https://github.com/geremyjampiersalasgarcia-eng">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=geremyjampiersalasgarcia-eng&bg_color=0d1117&color=00FF99&line=00FF99&point=8b949e&area=true&area_color=00FF9930&hide_border=true&custom_title=Contribution%20Timeline" />
</a>

</div>

<!-- DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ARCHITECTURE PHILOSOPHY -->
<div align="center">

## `// ENGINEERING PRINCIPLES`

</div>

```
 MULTI-TENANT ISOLATION     ZERO TRUST SECURITY       EVENT-DRIVEN DESIGN
 =====================     ====================      ====================
 Strict tenant_id           AES-256 encryption        Celery + Redis
 segmentation across        at rest. Immutable         async task queue.
 all data layers.           audit logs. RBAC          Exponential backoff.
 GDPR/CCPA compliant.       role enforcement.         SLA auto-close 72h.

 API-FIRST DESIGN           AUTOMATED TESTING         INFRASTRUCTURE AS CODE
 =====================     ====================      ====================
 FastAPI + Pydantic v2      Pytest + Vitest unit.     Docker Compose local.
 strict schema validation.  Playwright E2E.           GitHub Actions CI/CD.
 OpenAPI auto-docs.         Multi-browser headless.   Vercel edge deploys.
```

<!-- DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- CONNECT -->
<div align="center">

## `// CONNECT`

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00FF99)](https://www.linkedin.com/in/geremy-jampier-salas-garcia-6a3a39302)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=00FF99)](https://github.com/geremyjampiersalasgarcia-eng)
[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=00FF99)](https://studio-rho-liart.vercel.app/)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00FF99)](mailto:geremyjampiersalasgarcia@gmail.com)

<br>

<!-- VISITOR COUNTER -->
![](https://komarev.com/ghpvc/?username=geremyjampiersalasgarcia-eng&color=00FF99&style=flat-square&label=Profile+Views)

<br>

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00FF99,100:0d1117&height=120&section=footer" width="100%" />

</div>
