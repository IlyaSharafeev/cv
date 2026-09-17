<h1 align="center">Ilya Sharafeev</h1>
<h3 align="center">⚛️ Frontend Engineer — React / Next.js / TypeScript</h3>

<p align="center">
  <a href="./CV_Ilya_Sharafeev_React_NextJS.pdf"><b>📄 Download CV (PDF)</b></a>
</p>

<p align="center">
  <a href="mailto:ilyasharafeev01@gmail.com">✉️ ilyasharafeev01@gmail.com</a> &nbsp;·&nbsp;
  📞 +380 68 031 0159 &nbsp;·&nbsp;
  <a href="https://t.me/IlyaSharafeev">💬 Telegram</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/ilya-sharafeev-6428891ba/">💼 LinkedIn</a>
</p>

<p align="center">
  📍 Nessebar, Bulgaria (EET) &nbsp;·&nbsp; 🌍 100% remote &nbsp;·&nbsp; ⏰ Full-time, 5/2, full overlap with the Ukrainian working day &nbsp;·&nbsp; 🇬🇧 English B2
</p>

---

## ✨ In short

- 🧑‍💻 **4+ years** of commercial frontend, **1.5+ years** shipping production **Next.js**
- 🏗️ Built a platform's frontend **from zero** as the founding frontend engineer — design tokens → UI library → three apps in one monorepo
- 🔍 Architected an SSR platform for an SEO-dependent product — load time **~5 s → under 1 s**
- 🧩 Catalogues, filters, cards and galleries: a high-traffic marketplace and an automotive e-commerce storefront
- 🤝 Comfortable **owning the whole frontend next to a backend lead** — from the first component to production
- 🤖 **AI-first every day**: Claude Code does the scaffolding, refactors and tests — I own the architecture, the review and the final call

## 🏆 Numbers

| | |
|:---:|---|
| **−50%** | duplicated code across three apps after a monorepo + shared component library |
| **−60%** | UI CPU usage on a 1 000+ row CRM after virtualisation and query caching |
| **−35%** | initial load on an SSR platform I architected from scratch — Core Web Vitals and organic traffic up |
| **−40% / +25%** | legacy code / team velocity after leading a Vue 2 → Vue 3 migration |
| **−30%** | runtime errors after a full JavaScript → TypeScript migration |
| **10 000+** | concurrent WebSocket connections on a marketplace chat |

## 🛠️ Tech stack

**⚛️ React & Next.js**
`Next.js (App Router)` `Server Components` `SSR / SSG / ISR` `Route Handlers` `Metadata API` `next/image` `middleware & redirects` `React 16–18` `Hooks` `Suspense` `Vercel`

**🔷 TypeScript** — expert level
`generics` `discriminated unions` `utility & mapped types` `typed API clients` `strict mode` · led a full JavaScript → TypeScript migration on a production codebase

**🔄 Data & state**
`React Query` `SWR` `Zustand` `Redux Toolkit` · `REST by contract (OpenAPI, typed clients)` `GraphQL (Apollo)` `WebSockets` · caching, invalidation, optimistic updates, loading / error / empty states

**🎨 UI systems**
`design tokens → components → pages` `Storybook` `Tailwind CSS` `Styled Components` `CSS Modules` `SCSS` `Material UI` · complex responsive layouts, pixel-accurate implementation from Figma, accessible semantic markup

**🔍 SEO & performance**
`SSR / ISR` `metadata & canonical` `hreflang` `sitemap & redirect maps for migrations` `Core Web Vitals` `image optimisation (next/image, srcset, lazy loading)` `code splitting` `list virtualisation`

**🧪 Testing**
`Cypress (E2E)` `Jest` `Vitest` `React Testing Library`

**🤖 AI-first workflow**
`Claude Code` daily on real product work — agents for scaffolding, refactors, test generation and pre-review of my own diffs; custom skills and scripts for repetitive checks; strict verify-by-hand discipline for anything that ships

**⚙️ Workflow & infra**
`Git` `GitHub PR flow` `code review` `GitHub Actions` `GitLab CI` `Docker` `Vercel` `AWS (S3, CloudFront, Lambda)` `Jira`

**➕ Also**
`Vue 3 / Nuxt` `Angular` `Ionic & Capacitor`

## 💼 Experience

### 🚀 Gelios — Frontend Engineer
📅 Jan 2025 — Present &nbsp;·&nbsp; 🌍 Remote

> New EdTech platform built from zero on Next.js: student portal, teacher portal and an internal CRM.

- 🏗️ Joined as the **founding frontend engineer** and built the frontend from scratch on **Next.js (App Router) + TypeScript**: Turborepo monorepo, design tokens, a shared component library in Storybook and a common data layer — **over 50% less duplicated code** across three apps and a much shorter path to launch for a two-person team
- 📊 Built the data-heavy CRM — 1 000+ row lists with server-side filtering, sorting and pagination, bulk actions, multi-step forms — then fixed its performance with list virtualisation, React Query caching and debounced inputs: **UI CPU usage −60%**, no more freezes
- 🔌 Integrated REST and GraphQL APIs through typed clients with consistent loading / error / empty states and cache invalidation; added a WebSocket layer for real-time chat and notifications
- ✅ Covered the critical user flows with **Cypress E2E tests**; every change goes through PR review and GitHub Actions CI

🧰 `Next.js (App Router)` `React` `TypeScript` `Turborepo` `Zustand` `React Query` `GraphQL` `REST` `WebSockets` `Storybook` `Styled Components` `Cypress` `GitHub Actions`

### 🚗 Auto parts e-commerce storefront — Frontend Developer (contract)
📅 2026 &nbsp;·&nbsp; 🌍 Remote

> Complete storefront frontend for an automotive parts catalogue, implemented from Figma to a pixel-accurate spec.

- 🧩 Implemented the catalogue end to end: category pages with **filters and sorting**, search results with empty states, product page with **gallery** and stock states, cart and a multi-step checkout — three breakpoints (1920 / 768 / 390) served by one set of components
- ♿ Semantic, accessible markup to the client's spec (fieldset-based filters, native select sorting, list and link semantics in pagination, aria-labelled sections) and an automated geometry check against Figma coordinates with a 1 px tolerance

🧰 `Nuxt 3` `Vue 3` `TypeScript` `SCSS` `Puppeteer-based visual checks`

### 🏢 Onix-Systems — Frontend Engineer
📅 Dec 2022 — Dec 2024

> Outsourcing: long-running client products on React / Next.js and Vue / Nuxt.

- 🔍 Architected an **SSR platform from the ground up** for an SEO-dependent product (Nuxt): route- and component-level caching, optimised critical rendering path, aggressive code splitting — load time from ~5 s to sub-second, **−35% initial load**, Core Web Vitals up and search rankings with them
- ♻️ Led a phased **Vue 2 → Vue 3 migration** (−40% legacy code, +25% team velocity) and a full **JavaScript → TypeScript migration** (−30% runtime errors) — both on live products, without a feature freeze
- 🛒 Built product configuration and checkout flows on React / Next.js and Vue: dynamic option sets, dependent fields, backend-driven validation, generated PDF documents
- 📱 Delivered a cross-platform mobile app (Ionic + Capacitor) by reusing the existing component library — iOS and Android from one codebase, ~400 developer hours saved

🧰 `React` `Next.js` `Redux` `TypeScript` `Vue 3` `Nuxt.js` `Pinia` `React Query` `Tailwind CSS` `Quasar` `Ionic` `Capacitor` `Jest`

### 🛍️ Egolist — Frontend Developer
📅 Dec 2021 — Nov 2022

> High-traffic marketplace — listings, filters, seller dashboard, messaging.

- 🗂️ Developed listing and filtering pages, item cards and the seller dashboard on a Vue 2 + Vuex codebase, from written requirements and designs
- ⚡ Designed a low-latency **WebSocket layer handling 10 000+ concurrent connections** for chat and notifications
- 🚀 Built the GitLab CI/CD pipeline (tests, build, deploy) that turned manual releases into one-click ones

🧰 `Vue 2` `Vuex` `TypeScript` `SCSS` `WebSockets` `REST` `Jest` `Cypress` `GitLab CI`

## 🎓 Education

- **M.Sc. in Computer Science** — Oles Honchar Dnipro National University, Dnipro, Ukraine · 2024 — 2025

## 🗣️ Languages

- **English** — B2: technical documentation, written communication, code review and async work with international teams
- **Ukrainian** — native
- **Russian** — fluent
