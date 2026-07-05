# Hugo Gustavo Cordeiro
**Full Stack Developer** — Web systems & ERP integration <br>
Computer Science student @ UNIOESTE · Foz do Iguaçu, Brazil

<br>

I build the internal web systems a mid-size retail group runs on: an ERP-integrated
purchasing platform, an HR system I built end-to-end, and a self-hosted AI platform.
My focus is **web systems development and ERP integration** — data-heavy front-ends,
typed API-first back-ends, and turning messy operational processes into reliable software.
Comfortable going full-stack and stepping into native mobile when a problem needs it.
Fluent in English.

💼 Developer @ a mid-size retail group

---

## Currently

**Self-hosted AI Platform** — an internal, company-wide AI platform (in pilot): a RAG
pipeline over a vector store with custom MCP integrations, self-hosted so data stays in-house.
<br>
**Stack:** RAG · vector embeddings · custom MCP integrations · self-hosted infra.
<br>
**Relevance:** retrieval-augmented generation and tool integrations, taken from concept to a
working internal pilot.

Also: undergraduate research on biometric stress analysis for wearables — see *UpTrader Wear* below.

---

## What I've Built

> The projects below are professional, internal systems — descriptions focus on the
> engineering and what I built, not on repository access (private repos).

<details open>
  <summary><strong>HR System — solo, full-stack, end-to-end</strong></summary>
  <br>Owned the entire system from architecture to deploy: database, API, and <em>two</em>
  separate front-ends for different audiences (a public institutional site and an internal
  admin panel). It runs a mid-size retail group's employee admission process.
  <br><br>
  <strong>Back-end:</strong> Node.js + TypeScript · Express · Prisma + PostgreSQL ·
  JWT + bcrypt auth · MinIO (S3-compatible) object storage via multer · Zod validation ·
  Swagger/OpenAPI docs (swagger-autogen).
  <br>
  <strong>Institutional front-end:</strong> React 18 + Vite + TypeScript · TanStack Query +
  Axios · <em>typed API client generated with Orval from the OpenAPI contract (API-first)</em> ·
  Bootstrap 5 + Radix UI + Tailwind + CVA (shadcn-style) · react-hook-form + Zod.
  <br>
  <strong>Admin panel:</strong> React 18 + Vite · MUI v6 + MUI X Data Grid ·
  drag-and-drop (dnd-kit) · interactive maps with clustering (Leaflet) · TanStack Query.
  <br><br>
  <em>Relevance:</em> end-to-end ownership across the stack, an API-first pipeline that keeps
  back-end and front-end contracts in sync through codegen, and a data-rich UI spanning
  grids, geographic maps, and drag-and-drop.
</details>

<details>
  <summary><strong>Purchasing Platform (ERP-integrated) — mission-critical front-end</strong></summary>
  <br>Built the front-ends that drive a multi-store purchasing operation on top of the
  company's existing ERP APIs. A data-heavy, high-throughput tool used daily on the shop floor.
  <br><br>
  <strong>Stack:</strong> React 19 + TypeScript + Vite 6 · the full TanStack ecosystem
  (Router, Query, Store, Table, <em>Virtual</em>, Form) · Radix UI + Tailwind CSS v4 +
  CVA (shadcn-style) · cmdk command palette · Recharts · Biome (lint/format) ·
  Vitest + Testing Library.
  <br><br>
  <em>Engineering highlights:</em>
  <ul>
    <li><strong>Offline-first resilience:</strong> pending orders are queued in localStorage and
    auto-resent when connectivity returns (TanStack <code>onlineManager</code> + health-check polling).</li>
    <li><strong>Operator productivity:</strong> full keyboard-driven UX with terminal/legacy-ERP-style
    shortcuts (navigate items, quick search, submit) for heavy daily use.</li>
    <li><strong>Large-data UX:</strong> virtualized tables and nested tables synced to a per-store
    cart state.</li>
    <li><strong>RBAC:</strong> role-based access via a custom auth context with session handling.</li>
  </ul>
</details>

<details>
  <summary><strong>UpTrader Wear — Wear OS (Kotlin), applied research</strong></summary>
  <br>A Wear OS companion app for the UpTrader product, built as part of my undergraduate
  research (biometric data collection for stress analysis) — native mobile work outside the web stack.
  <br><br>
  <strong>Stack:</strong> Kotlin · native Wear OS · Jetpack Compose (Wear Compose Material3) ·
  Gradle Kotlin DSL + version catalogs · MVVM + StateFlow.
  <br><br>
  <em>Engineering highlights:</em>
  <ul>
    <li><strong>Two health-sensor SDKs, interchangeable:</strong> AndroidX Health Services
    (foreground + background monitoring that survives the app being killed) and the Samsung
    Health Sensor SDK (HRV, SpO₂, skin temperature), swappable at runtime with a fake/simulation
    source for hardware-free UI testing.</li>
    <li><strong>Real-time streaming</strong> watch → phone over the Wear Data Layer API.</li>
    <li><strong>On-device signal processing:</strong> custom HRV (RMSSD) computed from a
    quality-filtered sliding window of inter-beat intervals.</li>
  </ul>
</details>

## Open Source & Academic

<details>
  <summary><strong>Deu Time — Swift (HackaTruck / IBM)</strong></summary>
  <br>An app our team built during the final week of HackaTruck, an intensive course on Swift, IoT, and cognitive cloud services offered by IBM in partnership with Instituto Eldorado. It helps people find nearby groups to play sports.

<br><img src="https://github.com/prestesvinicius/deu-time/blob/main/HomeView.gif" alt="Menu GIF" width="280" height="576">

  <br>[Repository](https://github.com/prestesvinicius/deu-time)
</details>

<details>
  <summary><strong>Deu Time — React Native</strong></summary>
  <br>The Android version of Deu Time, built by the [CrewFE](https://github.com/crewFE) team for the entrepreneurship course of the Computer Science program. Front-end in React Native, back-end in Java.

<br><img src="https://github.com/crewFE/deutime-front-native/blob/main/IMG-20250326-WA0015.jpg" alt="Menu screenshot" width="280" height="576">

  <br>[Repository](https://github.com/orgs/crewFE/repositories)
</details>

<details>
  <summary><strong>Hybrid TCP / UDP Chat</strong></summary>
  <br>A terminal (REPL) chat system in JavaScript, implementing the TCP and UDP protocols for a Distributed Systems course.

  <br><img src="https://github.com/ugoincc/tcp-udp-hybridchat/blob/main/user_demo.png" alt="demo" width="480" />

  <br>[Repository](https://github.com/ugoincc/tcp-udp-hybridchat)
</details>

## BootDev Portfolio
<a target="_blank" rel="noopener" href='https://www.boot.dev/u/ugoincc' align="left">
  <img src="https://api.boot.dev/v1/users/public/995d4354-c79f-48e2-97ee-9faef11ded74/thumbnail" width='300' >
</a>

## Languages & Tools

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F54A2A?logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)

**Front-end**
![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB)
![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?logo=reactquery&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?logo=radixui&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?logo=mui&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_v3%2Fv4-%2338B2AC.svg?logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?logo=reacthookform&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white)

**Back-end**
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?logo=drizzle&logoColor=000)
![Swagger](https://img.shields.io/badge/Swagger%2FOpenAPI-85EA2D?logo=swagger&logoColor=000)
![Orval](https://img.shields.io/badge/Orval_(typed_client)-6E56CF)

**Mobile**
![React Native](https://img.shields.io/badge/React_Native-%2320232a.svg?logo=react&logoColor=%2361DAFB)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?logo=jetpackcompose&logoColor=white)
![Wear OS](https://img.shields.io/badge/Wear_OS-4285F4?logo=wearos&logoColor=white)

**Data, AI & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?logo=minio&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_%2B_Embeddings-412991?logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=000)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

**Testing & Tooling**
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?logo=testinglibrary&logoColor=white)
![Biome](https://img.shields.io/badge/Biome-60A5FA?logo=biome&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?logo=eslint&logoColor=white)

## Contact
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hugogustavoc12@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hugo-gustavo-9ab995209/?trk=opento_sprofile_topcard)
