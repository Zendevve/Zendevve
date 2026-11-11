# Zendevve

**Full-Stack & Systems Engineer** · `SaaS` · `Web` · `Desktop`

Full-stack and systems engineer building, shipping, and monetizing production SaaS platforms, municipal-grade systems, and commercial desktop utilities. Focused on multi-tenant architecture, zero-trust data protection (`AES-256-GCM`), and offline-first synchronization using **TypeScript, Python, Rust, React, and Django**.

[![Email](https://img.shields.io/badge/Email-zendevve%40duck.com-18181b?style=flat-square&logo=protonmail&logoColor=white)](mailto:zendevve@duck.com)
[![GitHub](https://img.shields.io/badge/GitHub-Zendevve-18181b?style=flat-square&logo=github&logoColor=white)](https://github.com/Zendevve)

---

## Featured Systems & Projects

### [nxtDMD](https://nxtdmd.com) — Production Multi-Tenant Dental SaaS
`Python 3.12` · `Django 5.2` · `PostgreSQL` · `Celery` · `Redis` · `Django Channels` · `PWA`
* **Scale:** Core engineer on a production EHR and clinical operations platform actively serving **13 dental clinics**.
* **Zero-Trust Security:** Implemented `AES-256-GCM` field-level encryption, blind indexing for fast encrypted search queries, and cryptographically signed private media delivery.
* **Real-Time Concurrency:** Orchestrated live clinic queues, doctor workflows, and appointment scheduling via WebSockets (Django Channels + Redis) to eliminate double-booking during peak hours.
* **Automation:** Built automated subscription billing via PayMongo webhooks, asynchronous PDF clinical reporting with Celery, and offline-resilient PWA capabilities.

### QuentaPOS — Universal Multi-Branch Point-of-Sale Platform
`React` · `TypeScript` · `Vite` · `PostgreSQL` · `Supabase` · `WebSockets` · `PWA` · `Tailwind CSS`
* **Offline-First Engine:** Architected a durable local `IndexedDB` transaction queue with idempotent synchronization and automated conflict resolution for zero transaction dropouts during network outages.
* **Tamper-Proof Auditing:** Enforced strict PostgreSQL Row-Level Security (RLS) and server-side RBAC governing cashier shifts, manager overrides, discount guardrails, and immutable refund logs.
* **Live Inventory Ledger:** Engineered a real-time stock movement ledger handling automated multi-branch deductions and preventing duplicate checkout submissions.

### CC Version Guard — Commercial Desktop Utility
`Rust` · `Tauri` · `JavaScript` · `Tailwind CSS` · `Win32 API`
* **Traction:** **69 GitHub Stars** · **22 Forks** · **30 Paid Commercial Licenses**
* **Systems Engineering:** Built low-level binary isolation routines and non-destructive Windows registry controls in Rust to block forced auto-updates and breaking changes for video editors.
* **Zero-Corruption Rollbacks:** Engineered direct legacy binary fetching from official vendor CDNs paired with snapshot-based directory backups.

### DXVK Studio — Commercial Game Optimization Utility
`Electron` · `React` · `TypeScript` · `better-sqlite3` · `Vite` · `Tailwind CSS`
* **Traction:** **37 GitHub Stars** · **15 Paid Commercial Licenses**
* **Runtime Automation:** Automated Vulkan-based DXVK setup across Steam, GOG Galaxy, and Epic Games Store with `PE32/PE32+` executable architecture detection and fork switching.
* **Safety Protocols:** Built anti-cheat detection, automatic fallback restore points, and fast local configuration caching via `better-sqlite3`.

### eLUNSAD — Municipal Business Permit & Licensing System
`React 18` · `TypeScript` · `Vite` · `Supabase` · `PostgreSQL` · `Deno Edge Functions` · `Leaflet` · `Recharts`
* **Architecture:** Designed and delivered a digital business permit and licensing platform modernizing municipal registration and regulatory workflows.
* **Data Governance:** Structured PostgreSQL schemas with department-scoped JWT verification and granular RLS policies to protect applicant financials and audit trails.
* **Analytics:** Built 18 real-time analytical dashboards and GIS visualizations using Leaflet and Recharts alongside automated document pipelines on Deno Edge Functions.

---

## Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, Python, Rust, SQL, Java, C++ |
| **Frontend** | React 18/19, Next.js, Vite, Tailwind CSS, shadcn/ui, Radix UI, TanStack Query, Zustand |
| **Backend & Distributed** | Django, Node.js, Deno, REST APIs, WebSockets, Celery, Redis, Django Channels |
| **Databases & Cloud** | PostgreSQL, Supabase, SQLite (`better-sqlite3`), MySQL, Deno Edge Functions, RLS |
| **Systems & Security** | Multi-Tenant Architecture, RBAC, JWT, OTP, AES-256-GCM, Blind Indexing, Offline Sync |
| **Desktop & Mobile** | Tauri, Electron, React Native, Expo, Service Workers, PWA |
| **Tooling & CI/CD** | Git, GitHub Actions, Docker, Vitest, Playwright, Linux |

---

## Certifications & Credentials

* **AWS Certified AI Practitioner (AIF-C01)** — Amazon Web Services (2026)
* **Claude Code 101 & Claude Code in Action** — Anthropic (2026)
* **Junior Cybersecurity Analyst Career Path** — Cisco Networking Academy
* **Ethical Hacker & Endpoint Security** — Cisco Networking Academy
* **Inclusive Open Source Community Orientation (LFC102)** — The Linux Foundation (2025)
* **Python & Data Analytics Essentials** — Cisco Networking Academy (2025)
* **B.S. in Information Technology** — *Graduated with Academic Distinction (2026)*
