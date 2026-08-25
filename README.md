<div align="center">

# Mridha Imran Kabir

**Backend Engineer** — Django · Laravel · FastAPI

<p>
<img src="https://img.shields.io/badge/IT_Engineer-BIFPCL-0d1117?style=flat-square&labelColor=0d1117&color=161b22" alt="IT Engineer at BIFPCL"/>
<img src="https://img.shields.io/badge/Lead_Backend-CloudHub-0d1117?style=flat-square&labelColor=0d1117&color=161b22" alt="Lead Backend Engineer at CloudHub"/>
<img src="https://img.shields.io/badge/Bagerhat-Bangladesh-0d1117?style=flat-square&labelColor=0d1117&color=161b22" alt="Bagerhat, Bangladesh"/>
<a href="mailto:imrankabir325@gmail.com"><img src="https://img.shields.io/badge/imrankabir325@gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=ea4335&labelColor=0d1117&color=161b22" alt="Email"/></a>
</p>

</div>

---

Most of my work is unglamorous: slow queries made fast, jobs that survive bad input, systems
that tell you when they break.

I care about the 2am details — idempotent jobs, per-row error isolation, tenant data the
database itself keeps from leaking, indexes chosen for the real query. I've owned systems end
to end — a multi-tenant SaaS backend, a broad internal platform, workflow engines, data
pipelines — from schema design through migration, deployment, and the Linux boxes they run on.

`REST API design` · `Query optimisation & indexing` · `Background jobs & queues` ·
`Multi-tenant data isolation` · `Workflow & state machines` · `Schema design & migrations` ·
`Deployment & CI/CD`

## Stack

<table>
<tr>
<td><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=3776ab" alt="Python"/>
<img src="https://img.shields.io/badge/PHP-161b22?style=flat-square&logo=php&logoColor=777bb4" alt="PHP"/>
<img src="https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=f7df1e" alt="JavaScript"/>
</td>
</tr>
<tr>
<td><b>Frameworks</b></td>
<td>
<img src="https://img.shields.io/badge/Django-161b22?style=flat-square&logo=django&logoColor=44b78b" alt="Django"/>
<img src="https://img.shields.io/badge/Laravel-161b22?style=flat-square&logo=laravel&logoColor=ff2d20" alt="Laravel"/>
<img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI"/>
<img src="https://img.shields.io/badge/React-161b22?style=flat-square&logo=react&logoColor=61dafb" alt="React"/>
</td>
</tr>
<tr>
<td><b>Data</b></td>
<td>
<img src="https://img.shields.io/badge/MySQL-161b22?style=flat-square&logo=mysql&logoColor=4479a1" alt="MySQL"/>
<img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169e1" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/MSSQL-161b22?style=flat-square&logo=microsoftsqlserver&logoColor=cc2927" alt="MSSQL"/>
<img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=ff4438" alt="Redis"/>
</td>
</tr>
<tr>
<td><b>Infrastructure</b></td>
<td>
<img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ed" alt="Docker"/>
<img src="https://img.shields.io/badge/Celery-161b22?style=flat-square&logo=celery&logoColor=37814a" alt="Celery"/>
<img src="https://img.shields.io/badge/Nginx-161b22?style=flat-square&logo=nginx&logoColor=009639" alt="Nginx"/>
<img src="https://img.shields.io/badge/Linux-161b22?style=flat-square&logo=linux&logoColor=fcc624" alt="Linux"/>
<img src="https://img.shields.io/badge/AWS-161b22?style=flat-square&logo=amazonwebservices&logoColor=ff9900" alt="AWS"/>
<img src="https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=f05032" alt="Git"/>
</td>
</tr>
</table>

## Experience

### Backend Engineer (Contract) — CloudHub
<sub>**July 2026 — Present** · Lead backend author</sub>

**I own the backend architecture and the design docs that justify it.**
Lead backend author on a multi-tenant B2B SaaS platform. Tenant isolation is enforced in the
database with PostgreSQL Row-Level Security, so a missing `WHERE` clause fails closed instead
of leaking another tenant's data. Also built a transactional outbox for reliable notifications,
TimescaleDB time-series ingestion, and concurrency-safe scheduling.

<sub>`FastAPI` · `PostgreSQL` · `TimescaleDB` · `Row-Level Security` · `Transactional Outbox` · `Celery` · `Docker` · `Nginx`</sub>

### IT Engineer — [BIFPCL](https://www.bifpcl.com/)
<sub>**June 2025 — Present** · Sole author · 80+ models</sub>

**Migrated SQLite → MSSQL in place, then kept shipping on top of it.**
Titled IT Engineer, but the work is mostly backend. Primary author of a large internal Django
platform — a multi-module monolith I've built and maintained single-handed since late 2025.
Migrated it from SQLite to MSSQL in place, moved slow file handling onto background workers,
and extracted a heavily-used module into its own service. Plus Linux operations, containerised
deployment, and monitoring.

<sub>`Django` · `DRF` · `Celery` · `Redis` · `MSSQL` · `Linux` · `Nginx`</sub>

### Software Engineer — Barikoi Maps
<sub>**January 2025 — June 2025** · Backend</sub>

**Geofence and nearby-point queries stayed fast as the dataset grew.**
Location-intelligence backends in Laravel and MySQL: spatial filtering — geofence containment,
nearby-point lookups — and the indexing to keep it fast as data grew. Redis for caching and
queues, Laravel WebSockets for real-time, Docker on AWS.

<sub>`Laravel` · `MySQL` · `Spatial Indexing` · `Redis` · `WebSockets` · `Docker` · `AWS`</sub>

### Backend Developer — Phone Tech BD Ltd
<sub>**January 2024 — January 2025** · Backend · 2 apps shipped</sub>

**Both shipped; Shifttrek is still in production.**
First professional backend role. Built two Laravel applications from scratch — including
Shifttrek, a workforce-scheduling product now in production — covering schema design, REST
APIs, and authentication, and refactored legacy modules that had grown hard to change safely.

<sub>`Laravel` · `MySQL` · `Livewire` · `REST API` · `Database Design`</sub>

## Selected work

Backend systems don't photograph well, so each entry is a problem, a decision, and its
tradeoff — not a screenshot. Employer and client systems are described at the engineering
level only.

### CloudHR — multi-tenant B2B SaaS
<sub>Lead Backend Engineer · CloudHub — **In production** — client product, code is private</sub>

**Tenant isolation the database itself enforces — a missed `WHERE` clause fails closed, not open.**
A multi-tenant B2B SaaS I'm the lead backend author on. The whole design turns on tenant
isolation, enforced in the database rather than trusted to application-layer filtering.

- Tenant isolation via database-enforced Row-Level Security, not app-layer filtering
- Transactional outbox so notifications survive a broker outage
- TimescaleDB time-series ingestion with evaluation in a background worker

<sub>`FastAPI` · `PostgreSQL` · `TimescaleDB` · `Row-Level Security` · `Celery` · `Docker`</sub>

### BIFPCL Operations Platform
<sub>Sole backend author · BIFPCL — **In production** — internal system, code is private</sub>

**One author, one migration path, and still deployable as requirements keep arriving.**
The internal operations platform at BIFPCL — a multi-module Django monolith covering a broad
range of operational workflows. The engineering problem is keeping a system this wide coherent,
migratable, and deployable.

- 80+ models under one Django project, single-author ownership
- In-place SQLite → MSSQL migration behind a data-migration script
- Containerised nginx / uWSGI stack with a fail-fast CI pipeline

<sub>`Django` · `MSSQL` · `Docker` · `Nginx` · `uWSGI` · `CI/CD`</sub>

### Gatepass — approval workflow engine
<sub>Backend · BIFPCL — **In production** — internal system, code is private</sub>

**No approval can land half-applied — every transition is atomic and recoverable.**
BIFPCL's gate-pass approval system, extracted from the platform above into its own service.
Requests route through multiple approvers, each transition modelled as an explicit finite state
machine. The core problem is correctness under concurrent, multi-step approvals.

- Approval state machine on `django-fsm` — atomic and recoverable, no half-applied transitions
- JWT-authenticated API with bulk actions and CSV export
- Celery + Redis for background work and operational alerting

<sub>`Django` · `DRF` · `Celery` · `Redis` · `django-fsm` · `Docker`</sub>

### Vendor Procurement Portal
<sub>Backend · BIFPCL — **In production** — internal system, code is private</sub>

**Two audiences, one domain model, and business rules that live in exactly one place.**
A dual-portal design — external for vendors, internal for staff — over one shared domain model.
The focus is separation of concerns: business rules live in a dedicated services layer, not in
views or models.

- Dual-portal architecture over one shared domain model
- Business rules isolated in a dedicated services layer
- Database-driven fine-grained access control (UBAC) with a full audit trail

<sub>`Django` · `Services Layer` · `UBAC` · `Tailwind` · `Bootstrap`</sub>

### Reliable Background Import System
<sub>Solo — **Private repo** — 54 tests / 189 assertions</sub>

**One bad row can no longer abort the run — failures stay queryable and re-exportable.**
Monica CRM imports contacts synchronously in-request — the whole file loaded into memory,
timing out past a few hundred rows. I rebuilt it as an async pipeline: the CSV streams row by
row, work chains across queue jobs, and each row's outcome is recorded independently.

- Three-stage job chain, configurable batch size; streamed, never fully buffered
- Per-row error isolation — failed rows stay queryable and export as a corrected CSV
- 54 tests / 189 assertions, plus ADRs on the key tradeoffs

<sub>`Laravel 11` · `MySQL` · `Redis` · `Queue Workers` · `PHPUnit`</sub>

### Legal Document Intelligence Pipeline
<sub>Solo — **Private repo** — 57 tests</sub>

**Every generated claim traces back to the source passage it came from.**
An ingestion-to-draft pipeline for messy legal documents. PDFs are extracted (OCR fallback) and
cleaned, retrieved over a hybrid BM25 + vector index, then a grounded draft is generated with
citations back to the source.

- Hybrid retrieval — BM25 for exact terms, Chroma vectors for semantic recall
- Grounded output with an evidence trail back to source passages
- Learns from operator edits (capture → diff → pattern store) · 57 tests, dockerised

<sub>`FastAPI` · `Python` · `Chroma` · `BM25` · `React` · `Docker`</sub>

### Other work

<table>
<tr>
<td width="33%" valign="top">

**[Shifttrek](https://www.shifttrek.com/)**<br/>
<sub>Backend · Phone Tech BD — **Live**</sub>

A production workforce-scheduling product, now serving live operational workflows. My work
centred on backend stability and database efficiency — schema design, query tuning, and
predictable scheduling logic under real use.

<sub>`Laravel` · `MySQL` · `Livewire` · `TailwindCSS`</sub>

</td>
<td width="33%" valign="top">

**[CV Studio](https://cv-studio-v1.vercel.app/)**<br/>
<sub>Solo — **Live** · no sign-up</sub>

A free CV builder for freshers. Local-first — everything lives in the browser, with optional
Supabase sync that stays off by default. The hard parts are product ones: guiding someone
staring at a blank field, and a PDF export that stays selectable and ATS-readable.

<sub>`React 19` · `Vite` · `Supabase` · `localStorage`</sub>

</td>
<td width="33%" valign="top">

**BanglaHealth**<br/>
<sub>Solo — **Prototype** · ~20 models</sub>

A health-records prototype built around the hard domain problems rather than CRUD:
patient–practitioner relationships, consent over who can read a record, and reporting
aggregation. Honest status: the domain modelling is done, the test suite is not.

<sub>`Django` · `DRF` · `Celery` · `PostgreSQL` · `Docker`</sub>

</td>
</tr>
</table>

## Education

| | | |
|---|---|---|
| **B.Sc in Computer Science & Engineering** | Khulna University — Khulna, Bangladesh | January 2018 — March 2024 |
| **HSC in Science** | Digraj Degree College — Mongla, Bagerhat | 2014 — 2016 |

## GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=imrankabir02&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" height="160" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=imrankabir02&layout=compact&hide_border=true&langs_count=8" height="160" />

</div>

---

<div align="center">

Several of the systems above are private — I'm happy to walk through the architecture and the
tradeoffs on a call.

**[imrankabir325@gmail.com](mailto:imrankabir325@gmail.com)** · Khulna, Bangladesh

</div>
