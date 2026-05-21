<div align="center">

<!-- BARRA DE STATUS -->
![Status](https://img.shields.io/badge/SYSTEM__STATUS:_ONLINE-0d1117?style=for-the-badge&logo=statuspage&logoColor=00FF99)
![Role](https://img.shields.io/badge/Ingeniero_en_Sistemas_de_Informaci%C3%B3n-0d1117?style=for-the-badge&logo=target&logoColor=00FF99)

<!-- HEADER ANIMADO -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00FF99,100:0d1117&height=200&section=header&text=GEREMY%20SALAS.&fontSize=52&fontColor=00FF99&fontAlignY=38&animation=fadeIn" width="100%" />

<!-- ANIMACIÓN DE TEXTO -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=00FF99&center=true&vCenter=true&repeat=true&width=600&height=30&lines=Ingeniero+Backend+%7C+Ecuador;Construyendo+SaaS+%7C+Multi-Tenant;Python+%2B+TypeScript+%2B+FastAPI+%2B+Next.js;Arquitectura+Segura+%7C+RBAC+%2B+Auditoría)](https://git.io/typing-svg)

<br>

> Desarrollador web y móvil con pasión por crear aplicaciones<br>
> y experiencias de usuario de calidad. Siempre aprendiendo.

<br><br>

[![Portfolio](https://img.shields.io/badge/Portfolio-geremysalas.dev-0D1117?style=for-the-badge&logo=google-chrome&logoColor=00FF99)](https://studio-rho-liart.vercel.app/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0D1117?style=for-the-badge&logo=linkedin&logoColor=00FF99)](https://www.linkedin.com/in/geremy-jampier-salas-garcia-6a3a39302) [![GitHub](https://img.shields.io/badge/GitHub-Follow-0D1117?style=for-the-badge&logo=github&logoColor=00FF99)](https://github.com/geremyjampiersalasgarcia-eng) [![Email](https://img.shields.io/badge/Email-Contact-0D1117?style=for-the-badge&logo=gmail&logoColor=00FF99)](mailto:geremyjampiersalasgarcia@gmail.com)

</div>

<!-- SEPARADOR -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- SOBRE MÍ -->
<div align="center">

### 🤓 Sobre Mí

</div>

```yaml
nombre: Geremy Salas
rol: Ingeniero en Sistemas de Información
ubicación: Ecuador
enfoque:
  - Desarrollo backend con Python y FastAPI
  - Aplicaciones web con Next.js y TypeScript
  - Bases de datos y arquitectura de APIs
  - Aprendiendo sobre IA e integraciones
construyendo:
  - KONTRAX  — Gestión de contratistas
  - NOVADIFY — Alojamiento y turismo
filosofía: "Aprender construyendo proyectos reales"
```

<!-- SEPARADOR -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- STACK TECNOLÓGICO -->
<img align="right" alt="Cyberpunk Coder GIF" height="190px" width="200px" src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif"/>

### 🛠 Stack Tecnológico

#### Languages & Frameworks

<p> <a href="https://skillicons.dev"> <img src="https://skillicons.dev/icons?i=python,typescript,javascript,html,css,react,nextjs,fastapi,svelte,astro&perline=10" /> </a> </p>

#### Backend & Databases

<p> <a href="https://skillicons.dev"> <img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,django,postgresql,mysql,mongodb,redis,graphql,docker&perline=10" /> </a> </p>

#### Tools & Cloud

<p> <a href="https://skillicons.dev"> <img src="https://skillicons.dev/icons?i=git,github,docker,vscode,figma,aws,supabase,vercel,tailwind,linux&perline=10" /> </a> </p>

<!-- SEPARADOR -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- PROYECTOS DESTACADOS -->
<div align="center">

## Proyectos Destacados

</div>

<!-- KONTRAX -->
<table>
<tr>
<td>

### <img src="https://img.shields.io/badge/PÚBLICO-00FF99?style=flat-square&logoColor=white" /> KONTRAX &mdash; Gestión de Contratistas Empresarial

[![Kontrax CI](https://github.com/geremyjampiersalasgarcia-eng/Kontrax/actions/workflows/ci.yml/badge.svg)](https://github.com/geremyjampiersalasgarcia-eng/Kontrax/actions)

> Plataforma SaaS multi-tenant para gestionar el proceso de incorporación de contratistas.
> Integra verificación de identidad (Stripe), firma de contratos (DocuSign) y dashboards operativos.

<details>
<summary><b>Arquitectura y Tecnologías</b></summary>
<br>

| Capa | Tecnología | Propósito |
|:-----|:-----------|:----------|
| **API** | FastAPI + Pydantic v2 + SQLAlchemy 2.0 | API REST asíncrona con validación estricta |
| **Base de Datos** | PostgreSQL + Alembic | Aislamiento multi-tenant con migraciones y soft-delete |
| **Cola / Cache** | Redis + Celery + Celery Beat | Jobs async, monitoreo SLA 72h, backoff exponencial |
| **Frontend** | Next.js 15 + TypeScript + Shadcn UI | App Router, SSR, i18n, Zustand + TanStack Query |
| **Identidad** | Stripe Identity | KYC bancario con verificación biométrica facial |
| **Contratos** | DocuSign (Embedded Signing) | Firma electrónica vinculante vía iframe |
| **Almacenamiento** | AWS S3 / Supabase Storage | Bóveda encriptada con URLs presignadas |
| **Correo** | Resend + Jinja2 | Emails transaccionales con templates HTML |
| **Seguridad** | AES-256 + RBAC | Encriptación en reposo, auditoría inmutable |
| **CI/CD** | GitHub Actions + Pytest + Playwright | Tests automatizados + simulación E2E |

</details>

<details>
<summary><b>Capacidades Principales</b></summary>
<br>

- **Aislamiento Multi-Tenant B2B** &mdash; Segmentación por `tenant_id`, branding por subdominio, GDPR/CCPA
- **RBAC de 4 Niveles** &mdash; System Admin / Admin / Operador / Contratista
- **Onboarding en 5 Pasos** &mdash; Datos > Documentos (S3) > Contrato (DocuSign) > Pago > KYC (Stripe)
- **Dashboard Operador** &mdash; Recharts, SLAs 72h, embudos de conversión, actividad semanal
- **Workspace Post-Aprobación** &mdash; Asignación de tareas con prioridad, entregables, aprobaciones
- **Workers Celery** &mdash; Emails async con backoff exponencial, auto-cierre SLA vía Beat
- **Auditoría Inmutable** &mdash; Actor, timestamp, IP, estado anterior vs. nuevo
- **i18n** &mdash; Soporte ES/EN en tiempo real con next-intl
- **BI** &mdash; Reportes CSV: rosters, asignaciones, auditoría

</details>

<div align="center">

[![Ver Repositorio](https://img.shields.io/badge/Ver_Repositorio-0d1117?style=for-the-badge&logo=github&logoColor=00FF99)](https://github.com/geremyjampiersalasgarcia-eng/Kontrax)
![Commits](https://img.shields.io/badge/145+_Commits-0d1117?style=for-the-badge&logo=git&logoColor=00FF99)
![Estado](https://img.shields.io/badge/Producción-0d1117?style=for-the-badge&logo=statuspage&logoColor=00FF99)

</div>

</td>
</tr>
</table>

<br>

<!-- NOVADIFY -->
<table>
<tr>
<td>

### <img src="https://img.shields.io/badge/PRIVADO-8b949e?style=flat-square&logoColor=white" /> NOVADIFY &mdash; Plataforma de Alojamiento y Turismo

> Plataforma full-stack de alojamiento y turismo inspirada en Airbnb, enfocada en Ecuador.
> Conecta anfitriones y turistas con pagos reales (PayPal), asistente IA y facturación PDF.

<details>
<summary><b>Arquitectura y Tecnologías</b></summary>
<br>

| Capa | Tecnología | Propósito |
|:-----|:-----------|:----------|
| **Framework** | Next.js 15 (App Router) | SSR, Edge API Routes, SEO con `generateMetadata` |
| **Lenguaje** | TypeScript 5+ | Tipado estático en todo el proyecto |
| **Base de Datos** | Supabase (PostgreSQL) | RLS, triggers SQL, suscripciones real-time |
| **Auth** | Supabase Auth + Google OAuth | Magic Link y Login Social |
| **IA** | Google Gemini 1.5 | Asistente de viaje conversacional con NLP |
| **Pagos** | PayPal React SDK | Captura USD con auditoría de transacciones |
| **PDF** | @react-pdf/renderer | Facturas A4 server-side con branding |
| **Correo** | Resend | Confirmaciones, alertas, solicitudes de review |
| **Estado** | Zustand + TanStack Query | Estado global + actualizaciones optimistas |
| **Estilos** | Tailwind CSS 4+ | Arquitectura Zero Layout Shift |
| **Analítica** | Recharts + Google Analytics 4 | Dashboards SVG + tráfico en tiempo real |
| **Testing** | Vitest + Playwright | Unit + E2E (Desktop + Mobile) |
| **CI/CD** | GitHub Actions | Lint > TSC > Unit > E2E > Vercel |

</details>

<details>
<summary><b>Capacidades Principales</b></summary>
<br>

- **Super App Unificada** &mdash; Alojamientos + Experiencias + Servicios Privados en una plataforma
- **RBAC Triple** &mdash; Turista / Anfitrión / Admin en Middleware + RLS simultáneo
- **Zero Layout Shift** &mdash; Route Group `(home)`, Navbar persistente, scroll dual-mode
- **IA de Viaje** &mdash; Gemini lee propiedades en vivo para recomendaciones personalizadas
- **Wallet del Anfitrión** &mdash; Dashboard de ingresos con cálculo automático de comisiones
- **Checkout PayPal** &mdash; Fechas > Resumen > Captura > Email > Factura PDF
- **DB Auto-Reparable** &mdash; Triggers SQL recalculan ratings en cada review
- **Wishlist** &mdash; Favoritos real-time con protección RLS
- **Server Components** &mdash; SSR con `generateMetadata`, Client Components aislados
- **UI Optimista** &mdash; `useMutation` para confirmaciones instantáneas

</details>

<div align="center">

[![Ver Sitio](https://img.shields.io/badge/Ver_Sitio-0d1117?style=for-the-badge&logo=vercel&logoColor=00FF99)](https://novadify.vercel.app/)
![Estado](https://img.shields.io/badge/Producción-0d1117?style=for-the-badge&logo=statuspage&logoColor=00FF99)
![Acceso](https://img.shields.io/badge/Repositorio_Privado-0d1117?style=for-the-badge&logo=lock&logoColor=8b949e)

</div>

</td>
</tr>
</table>

<!-- SEPARADOR -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ESTADÍSTICAS -->
<div align="center">

## Estadísticas de GitHub

<br>


<a href="https://github.com/geremyjampiersalasgarcia-eng">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=geremyjampiersalasgarcia-eng&theme=chartreuse-dark&background=0d1117&hide_border=true&ring=00FF99&fire=00FF99&currStreakLabel=00FF99&sideLabels=8b949e&dates=8b949e&currStreakNum=00FF99&sideNums=00FF99&locale=es" />
</a>

<br><br>

<a href="https://github.com/geremyjampiersalasgarcia-eng">
  <img src="https://github-profile-trophy.vercel.app/?username=geremyjampiersalasgarcia-eng&theme=matrix&no-bg=true&no-frame=true&column=7&margin-w=10" />
</a>

<br><br>

<a href="https://github.com/geremyjampiersalasgarcia-eng">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=geremyjampiersalasgarcia-eng&bg_color=0d1117&color=00FF99&line=00FF99&point=8b949e&area=true&area_color=00FF9930&hide_border=true&custom_title=L%C3%ADnea%20de%20Tiempo%20de%20Contribuciones" />
</a>

<br><br>

<!-- SERPIENTE DE CONTRIBUCIONES -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/geremyjampiersalasgarcia-eng/geremyjampiersalasgarcia-eng/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/geremyjampiersalasgarcia-eng/geremyjampiersalasgarcia-eng/output/github-snake.svg" />
  <img alt="Animación de serpiente de contribuciones" src="https://raw.githubusercontent.com/geremyjampiersalasgarcia-eng/geremyjampiersalasgarcia-eng/output/github-snake.svg" />
</picture>

<br><br>

<!-- FRASE DEV ALEATORIA -->
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&border=true" alt="Frase de desarrollo" />

</div>

<!-- SEPARADOR -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- PRINCIPIOS -->
<div align="center">

## Principios de Ingeniería

</div>

```
 AISLAMIENTO MULTI-TENANT    ARQUITECTURA SEGURA       DISEÑO EVENT-DRIVEN
 ========================    =====================     ====================
 Segmentación por tenant_id  Encriptación AES-256      Celery + Redis async.
 en todas las capas.         en reposo. Auditoría      Backoff exponencial.
 Compatible GDPR/CCPA.       inmutable. RBAC.          Auto-cierre SLA 72h.

 DISEÑO API-FIRST            TESTING AUTOMATIZADO      INFRA AS CODE
 ========================    =====================     ====================
 FastAPI + Pydantic v2.      Pytest + Vitest unit.     Docker Compose local.
 Validación estricta.        Playwright E2E multi-     GitHub Actions CI/CD.
 OpenAPI auto-docs.          browser headless.         Deploy edge Vercel.
```

<!-- SEPARADOR -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- CONECTAR -->
<div align="center">

## Conectar

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00FF99)](https://www.linkedin.com/in/geremy-jampier-salas-garcia-6a3a39302)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=00FF99)](https://github.com/geremyjampiersalasgarcia-eng)
[![Portafolio](https://img.shields.io/badge/Portafolio-0d1117?style=for-the-badge&logo=vercel&logoColor=00FF99)](https://studio-rho-liart.vercel.app/)
[![Correo](https://img.shields.io/badge/Correo-0d1117?style=for-the-badge&logo=gmail&logoColor=00FF99)](mailto:geremyjampiersalasgarcia@gmail.com)

<br>

![](https://komarev.com/ghpvc/?username=geremyjampiersalasgarcia-eng&color=00FF99&style=flat-square&label=Visitas+al+Perfil)

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00FF99,100:0d1117&height=120&section=footer" width="100%" />

</div>
