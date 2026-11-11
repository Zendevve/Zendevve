# Zendevve

**Full-Stack & Systems Engineer** · `SaaS` · `Web` · `Desktop`

Full-stack and systems engineer building, shipping, and monetizing production SaaS platforms, municipal-grade systems, and commercial desktop utilities. Focused on multi-tenant architecture, zero-trust data protection (`AES-256-GCM`), and offline-first synchronization using **TypeScript, Python, Rust, React, and Django**.

[![Email](https://img.shields.io/badge/Email-zendevve%40duck.com-18181b?style=flat-square&logo=protonmail&logoColor=white)](mailto:zendevve@duck.com)
[![GitHub](https://img.shields.io/badge/GitHub-Zendevve-18181b?style=flat-square&logo=github&logoColor=white)](https://github.com/Zendevve)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-zendevve-18181b?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/zendevve)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy_Me_a_Coffee-zendevve-18181b?style=flat-square&logo=buy-me-a-coffee&logoColor=white)](https://buymeacoffee.com/zendevve)

---

## Featured Systems & Projects

### [nxtDMD](https://nxtdmd.com) — Production Multi-Tenant Dental SaaS
[![Live App](https://img.shields.io/badge/Live-nxtdmd.com-18181b?style=flat-square&logo=vercel&logoColor=white)](https://nxtdmd.com)

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

### [CC Version Guard (CCVG)](https://github.com/Zendevve/CCVG) — Commercial Desktop Utility
[![Repo](https://img.shields.io/badge/GitHub-Zendevve%2FCCVG-18181b?style=flat-square&logo=github&logoColor=white)](https://github.com/Zendevve/CCVG)
[![Get License](https://img.shields.io/badge/Store-Get_License-18181b?style=flat-square&logo=buy-me-a-coffee&logoColor=white)](https://buymeacoffee.com/zendevve/e/503073)
[![Stars](https://img.shields.io/github/stars/Zendevve/CCVG?style=flat-square&color=18181b&labelColor=27272a)](https://github.com/Zendevve/CCVG/stargazers)
[![Forks](https://img.shields.io/github/forks/Zendevve/CCVG?style=flat-square&color=18181b&labelColor=27272a)](https://github.com/Zendevve/CCVG/network/members)

`Rust` · `Tauri` · `JavaScript` · `Tailwind CSS` · `Win32 API`
* **Traction:** **69+ GitHub Stars** · **22+ Forks** · **[30 Paid Commercial Licenses](https://buymeacoffee.com/zendevve/e/503073)**
* **Systems Engineering:** Built low-level binary isolation routines and non-destructive Windows registry controls in Rust to block forced auto-updates and breaking changes for video editors.
* **Zero-Corruption Rollbacks:** Engineered direct legacy binary fetching from official vendor CDNs paired with snapshot-based directory backups.

### [DXVK Studio](https://github.com/Zendevve/DXVK-Studio-CE) — Commercial Game Optimization Utility
[![Repo](https://img.shields.io/badge/GitHub-Zendevve%2FDXVK--Studio--CE-18181b?style=flat-square&logo=github&logoColor=white)](https://github.com/Zendevve/DXVK-Studio-CE)
[![Get License](https://img.shields.io/badge/Store-Get_License-18181b?style=flat-square&logo=buy-me-a-coffee&logoColor=white)](https://buymeacoffee.com/zendevve/e/530420)
[![Stars](https://img.shields.io/github/stars/Zendevve/DXVK-Studio-CE?style=flat-square&color=18181b&labelColor=27272a)](https://github.com/Zendevve/DXVK-Studio-CE/stargazers)

`Electron` · `React` · `TypeScript` · `better-sqlite3` · `Vite` · `Tailwind CSS`
* **Traction:** **37+ GitHub Stars** · **[15 Paid Commercial Licenses](https://buymeacoffee.com/zendevve/e/530420)**
* **Runtime Automation:** Automated Vulkan-based DXVK setup across Steam, GOG Galaxy, and Epic Games Store with `PE32/PE32+` executable architecture detection and fork switching.
* **Safety Protocols:** Built anti-cheat detection, automatic fallback restore points, and fast local configuration caching via `better-sqlite3`.

### [eLUNSAD](https://dasnule.netlify.app/) — Municipal Business Permit & Licensing System
[![Live Demo](https://img.shields.io/badge/Live_Demo-dasnule.netlify.app-18181b?style=flat-square&logo=netlify&logoColor=white)](https://dasnule.netlify.app/)

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

## Licenses & Certifications

| Certification | Issuing Organization | Issued | Credential |
| :--- | :--- | :--- | :--- |
| **AWS Certified AI Practitioner (AIF-C01)** | Amazon Web Services (AWS) | Nov 2026 | [Verify ↗](https://e-tesda.gov.ph/mod/customcert/view.php?id=93681&downloadown=1) |
| **Claude Code in Action** | Anthropic | Aug 2026 | [Verify ↗](https://verify.skilljar.com/c/97xfedgssp4i) |
| **Claude Code 101** | Anthropic | Aug 2026 | [Verify ↗](https://verify.skilljar.com/c/topscfqttoiu) |
| **Endpoint Security** | Cisco | Dec 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/84794d9a-7fc3-4f9d-92fd-ad74c69b2c0c) |
| **Networking Basics** | Cisco | Dec 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/5fe5f015-c5ca-4533-8df6-c2a330546f51) |
| **Junior Cybersecurity Analyst Career Path** | Cisco | Sep 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/69224146-06de-44f0-a109-1a568a9bec0c) |
| **Data Analytics Essentials** | Cisco Networking Academy | Sep 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/27e10d6a-001c-42d2-87e3-059f9c3c1218) |
| **Introduction to Data Science** | Cisco | Sep 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/a7ce69d1-9b64-4822-85f9-57a0c9fb4728) |
| **Python Essentials 2** | Cisco | Sep 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/24712d9c-4625-452b-9b52-08ac9960e788) |
| **Python Essentials 1** | Cisco | Sep 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/5a9e1872-91c2-4fb7-8165-673597eed77c) |
| **Computer Hardware Basics** | Cisco | Sep 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/af966ca3-c4eb-43e2-838f-6c5313ec45cb) |
| **LFC102: Inclusive Open Source Community Orientation** | The Linux Foundation | May 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/bd202121-2a87-40f1-ba78-3962b5b489a9) |
| **Ethical Hacker** | Cisco | Apr 2025 | [Verify ↗](https://www.credly.com/earner/earned/badge/653b6975-1b5b-4ee0-a902-f6818ea99e44) |
| **Introduction to Cybersecurity** | Cisco | Nov 2024 | [Verify ↗](https://www.credly.com/earner/earned/badge/6311ea47-97f9-4557-b703-4bd9711097bc) |

* **Education:** B.S. in Information Technology — *Graduated with Academic Distinction (2026)*
