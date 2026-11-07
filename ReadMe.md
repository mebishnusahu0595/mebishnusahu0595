# Bishnu Prasad Sahu

**Full-Stack Systems Architect & Mobile Engineer**  
Bhilai, Chhattisgarh, India · [bishnu.pro](https://bishnu.pro) · [contact@bishnu.pro](mailto:contact@bishnu.pro) · [LinkedIn](https://linkedin.com/in/mebishnusahu05) · [GitHub](https://github.com/mebishnusahu0595)

---

### About Me

I am a full-stack engineer and mobile developer with 2+ years of production experience building distributed backends, mobile application suites, and computer vision systems. 

- **Production Track Record:** Shipped 12+ Android APKs and architected 20+ live platforms serving real businesses and customers.
- **US Copyright Registrations:** 9 commercial software architectures formally registered with the US Copyright Office.
- **Open Source:** Contributor to `supabase-py` (fixed a critical storage client URL bug and wrote 12+ integration tests).
- **Competitions & Research:** Winner of RIFT Hackathon Bangalore (Money Muling Graph Detector), 2nd place at AVISHKAR 2025 (FAMS AI Medical Assistant), and published research preprint on Zenodo.

---

### Key Production Systems

#### 1. Indraprastha Petroleum — Petrol Pump Automation Suite
Comprehensive software suite automating daily petrol pump operations across 4 mobile apps and 3 web panels:
- **Mobile Fleet (4 Android APKs):** Admin console, Station Manager, Staff Nozzle Operator, and Customer Loyalty app.
- **Web Panels (3 Dashboards):** Superadmin central hub, Station Operations, and Financial Audit ledgers.
- **Core Capabilities:** Real-time nozzle fuel dispensing metering, underground tank dip level calculations, shift day-end cash/digital reconciliation, and B2B credit party ledger billing.

```text
  [Fuel Dispenser Telemetry]           [Tank Dip Level Sensors]
              │                                   │
              └─────────────────┬─────────────────┘
                                ▼
                 [Node.js / Express Backend Hub]
                                │
        ┌───────────────────────┴───────────────────────┐
        ▼                                               ▼
  [4 Mobile Android APKs]                     [3 Web Portals]
  ├── Admin Executive APK                     ├── Superadmin Dashboard
  ├── Station Manager APK                     ├── Station Operations Hub
  ├── Staff Nozzle Operator APK               └── Financial Audit Ledger
  └── Customer Loyalty APK
```

#### 2. Vaniki Crop Science — Agrochemical Platform & StaffTrack
Sole developer architecting the complete agrochemical e-commerce ecosystem in a TypeScript Turborepo, serving 50+ active dealers:
- **Mobile Fleet (6 Android APKs):** Customer shopping app, Vaniki Crop Partners dealer ordering app, StaffTrack field workforce GPS tracking APK, agronomist field task app, territory lead manager, and logistics QA.
- **Web Layer (3 Portals):** Superadmin command portal, B2B dealer order approval web, and warehouse inventory management.
- **Backend & Integrations:** Node.js/Express REST APIs, Redis/BullMQ task queues, Razorpay payment flows, and automated two-way XML sync with Tally ERP.

```text
  [Turborepo TypeScript Monorepo]
        │
        ├── [6 React Native Android APKs]
        │   ├── Customer Agrochemical App (Google Play)
        │   ├── Vaniki Crop Partners Dealer App
        │   └── StaffTrack (Real-Time GPS Field Workforce Geofence Tracking)
        │
        ├── [3 React Web Admin Portals]
        │   ├── Superadmin Command Console
        │   ├── Dealer Order Approval Portal
        │   └── Warehouse Management System
        │
        └── [Distributed Backend & ERP Bridge]
            ├── Node.js / Express API Cluster
            ├── Redis / BullMQ Job Queues
            └── Tally ERP Automated XML Sync Agent
```

#### 3. Zexton & ONCorg — Multi-Tenant Platform Cluster
Architected and deployed 17 commercial platforms across healthcare, insurance, hospitality, and enterprise SaaS:

```text
  [Incoming Web & Mobile Traffic] ──> [Nginx Reverse Proxy / SSL]
                                               │
       ┌───────────────────────┬───────────────┴───────────────┬───────────────────────┐
       │                       │                               │                       │
  [Healthcare]          [Fintech & Insurance]          [Hospitality & POS]     [Enterprise SaaS]
  ├── ONCorg Network    ├── Optavise Marketplace       ├── Kea By The Pool POS ├── SCM Logistics Engine
  ├── Biomed Asset CMS  │   (35+ US Carriers)          │   (Table KOT POS)     ├── E-Blast Campaign Engine
  ├── POC Consults OSHA └── Starbounds Job Board       ├── TheMark Hotel POS   ├── Living Word ChurchWebsite
  └── CollegeMobi       │   (Talent Directory)         │   (Room Folio PMS)    └── Organic & Organic
                                                       └── StayNTour PMS           (Mongo Replica Set)
```

---

### Commercial Platforms & US Copyright Registrations

Platforms architected, developed, and maintained for Zexton Software Solutions, Centralized Medical Solutions, and ONCorg:

| Platform | Domain | Architecture & Stack | Purpose / Domain | US Copyright Status |
|---|---|---|---|---|
| **ONCorg Healthcare Network** | [oncorg.com](https://oncorg.com) | Next.js 15, Node.js, PostgreSQL 16, MongoDB | Hospital Management & Oncology Clinical Network | **TX-9-102-488** (Registered) |
| **Living Word ChurchWebsite** | [churchwebsite.zexton.com](https://churchwebsite.zexton.com) | Node.js, Express, MongoDB | Member Management & Giving Portal | **TX-9-106-201** (Registered) |
| **CollegeMobi Nursing School** | [nursingschool.collegemobi.com](https://nursingschool.collegemobi.com) | Node.js, Express, MongoDB | Medical Education & Nursing Curriculum Portal | **TX-9-109-504** (Registered) |
| **Organic & Organic E-Commerce** | [organicandorganic.com](https://organicandorganic.com) | Node.js, MongoDB Replica Set (rs0) | Natural & Organic Food Marketplace | **TX-9-108-403** (Registered) |
| **POC Consults & OSHA Dashboard** | [pocconsults.com](https://pocconsults.com) | Node.js, Express, MongoDB | Point of Care & OSHA Clinical Compliance | **TX-8-941-205** (Registered) |
| **WebAshore Digital Agency** | [webashore.com](https://webashore.com) | Node.js, Express, MongoDB | Digital Agency Client & Project Hub | **TX-9-004-118** (Registered) |
| **Zexton E-Blast Campaign Engine** | [eblastportal.zexton.com](https://eblastportal.zexton.com) | Node.js, Persistent JSON FileStore | High-Volume Email Delivery & Analytics | **TX-9-107-302** (Registered) |
| **Zexton Enterprise Solutions** | [zexton.com](https://zexton.com) | Node.js, Express, MongoDB | Enterprise Client & Architecture Portal | **TX-8-755-312** (Registered) |
| **TuneInPrayer Community** | [tuneinprayer.com](https://tuneinprayer.com) | Node.js, Express, MongoDB | Faith Community & Prayer Platform | **SR-771-420** (Registered) |
| **BbNTour Hospitality (StayNTour)** | [bbntour.com](https://bbntour.com) | Node.js, Express, MongoDB | Hospitality & Short-Term Property PMS | PENDING-BBN-2026-01 |
| **Biomed Asset / CMS Platform** | [biomedasset.com](https://biomedasset.com) | React, Node.js, MongoDB | Clinical Equipment & Biomedical Asset CMS | In Preparation |
| **CMercial B2B Directory** | [cmercial.com](https://cmercial.com) | React, Node.js, MongoDB | Enterprise B2B Directory & Commercial Market | PENDING-CMER-2026 |
| **Optavise Insurance Services** | [optavise.net](https://optavise.net) | Next.js, TypeScript, MongoDB | Insurance Comparison for 35+ US Carriers | PENDING-OPTA-2026 |
| **PressPlay Media Platform** | [pressplay1.com](https://pressplay1.com) | Node.js, Express, MongoDB | Video Streaming & Media Pipeline | In Preparation |
| **SCM Supply Chain Management** | [scm.cmslinc.com](https://scm.cmslinc.com) | Node.js Microservices, MongoDB | Logistics & Supply Chain Coordination | In Preparation |
| **Starbounds Job Board** | [starbounds.com](http://starbounds.com) | Microsoft IIS, MS SQL Server | Enterprise Talent Board & Candidate Portal | In Preparation |
| **Kea By The Pool Restaurant POS** | [keabythepool.com](https://keabythepool.com) | React, Node.js, Socket.IO, MongoDB | Restaurant POS, Table Floorplans & KOT Routing | Live Production POS |
| **TheMark Hotel POS** | [themark.in](https://themark.in) | React, Node.js, Express, MongoDB | Hotel Room Reservation & Guest PMS | Live Production PMS |

---

### Honors & Research

- **Winner [1st Place] — RIFT Hackathon, Bangalore**  
  *Money Muling Detector:* Financial fraud engine combining a custom Red-Black Tree and Decision Tree at O(N log N) time complexity to detect money muling rings across 10,000+ live transactions.
- **Silver [2nd Place] — AVISHKAR 2025 (80+ Teams)**  
  *FAMS AI Medical Assistant:* Real-time diagnostic assistant combining computer vision facial distress detection with voice conversational AI and LLM reasoning.
- **Finalist — HackOmania 2025**  
  *FarmView AI:* Satellite crop telemetry computing NDVI indices from Sentinel Hub imagery with edge YOLOv8 plant disease detection.
- **Published Research Preprint — Zenodo**  
  *Kuya Cloud:* Automated rule-based data analytics and visualization engine.  
  *Sahu, B. P. (2026). Kuya Cloud. Zenodo.* **DOI:** [`10.5281/zenodo.18803300`](https://doi.org/10.5281/zenodo.18803300)

---

### Work Experience

- **Vaniki Crop Science** — Full Stack & Android Developer *(May 2026 – Present)*
  - Architected the company's entire agrochemical mobile and web platform in a TypeScript Turborepo (6 Android APKs + 3 React web portals).
  - Built StaffTrack: real-time GPS workforce tracking APK with automated geofencing.
  - Automated Tally ERP XML accounting synchronization via Node.js microservices.
- **Zexton / Centralized Medical Solutions / ONCorg** — Software Engineer & Systems Architect *(Jun 2024 – Present)*
  - Architected 17+ commercial platforms, securing 9 US Copyright Office registrations.
  - Engineered Drevo Wheels car/bike rental booking engine and Android APKs on Google Play.
  - Built Optavise insurance aggregator comparing policies across 35+ national carriers.
- **Indraprastha Petroleum** — Lead Systems Architect & Developer *(2026)*
  - Built full petrol pump automation software: 4 mobile Android APKs + 3 web dashboards.
  - Automated fuel dispenser nozzle metering, underground tank dip tracking, and daily cash reconciliation.
- **Kea By The Pool & TheMark Hotel** — Full Stack POS Engineer *(2026)*
  - Built active restaurant POS for Kea By The Pool (table floorplans, waiter orders, KOT routing).
  - Built TheMark Hotel PMS (room reservations, folios, check-in/out).
- **Supabase** — Open Source Contributor *(Jan 2026 – Present)*
  - Fixed a critical storage client URL parsing bug in `supabase-py`.
  - Authored 12+ integration tests covering edge cases across synchronous and asynchronous clients.

---

### Tech Stack

- **Languages:** TypeScript, JavaScript, Python, C++, Java, SQL, Go, HTML5, CSS3
- **Frontend & Mobile:** React, React Native, Expo, Next.js 15, Turborepo, Tailwind CSS, TanStack Query, Vite
- **Backend & Microservices:** Node.js, Express, REST APIs, Redis, BullMQ, Socket.IO, FastAPI, Flask, .NET C#
- **Databases:** MongoDB (Replica Set), PostgreSQL 16, MySQL, Microsoft SQL Server, Redis
- **DevOps & Cloud:** Ubuntu Linux, Nginx, Docker, PM2, GitHub Actions CI/CD, Microsoft IIS, SSL/TLS (Certbot)
- **AI & Vision:** OpenCV, YOLOv8, Deep SORT, TensorFlow, PyTorch, LLM APIs

---

### Get In Touch

I am open to full-time engineering roles (SDE-1 / Systems Architect / Mobile / Backend).

- **Website:** [https://bishnu.pro](https://bishnu.pro)
- **Email:** [contact@bishnu.pro](mailto:contact@bishnu.pro)
- **LinkedIn:** [linkedin.com/in/mebishnusahu05](https://linkedin.com/in/mebishnusahu05)
- **GitHub:** [github.com/mebishnusahu0595](https://github.com/mebishnusahu0595)
- **Phone / WhatsApp:** [+91 93011 05706](tel:+919301105706)
