# Harsher Core

**Modular, open-source tooling and reference implementations for social platforms, e-commerce and cross-platform apps.**

Harsher Core is a collection of interoperable solutions, libraries and conventions that together form a repeatable, production-grade foundation for building web applications, mobile apps, e-shops and content platforms. The project is technology-agnostic by design but centers on the stack we use in production: **Vue.js**, **Nette (PHP)** and **React Native**, with styling via **CSS / SCSS / SASS**.

---

## Why Harsher Core

- Modular by design – pick only the pieces you need (social engine, CMS, e-commerce, mobile sync).
- Practical compatibility – supports new JS/TS projects and gradual adoption alongside PHP/Nette/Baraja codebases.
- Production engineering – default patterns for API design, security, observability and deployment.
- Opinionated, not prescriptive – we provide recommended implementations and reference apps so teams can move faster.

---

## Key Capabilities

- Social features: posts, comments, groups, private messaging, moderation, notifications.
- E-commerce primitives: Product → Cart → Order → Inventory → Checkout.
- CMS & Content Engine: pages, blocks, media management, SEO helpers, multilingual content.
- Mobile layer: React Native reference app, push notifications, offline sync patterns.
- API: REST (OpenAPI) + GraphQL optional, with auto-generated docs.
- Integrations: payments, mailers, CDNs, SSO and third-party APIs.
- DevOps defaults: Docker dev setups, CI pipelines, deployment templates.

---

## Technology Overview

- Frontend:  Vue.js 2/3 (Composition API), optional TypeScript, classic CSS / SCSS / SASS
- Mobile: React Native (iOS & Android)
- Backend: Nette Framework (PHP 8+), Doctrine/Dibi for data layer
- Datastore: MySQL / SQLite/ MariaDB / PostgreSQL (pluggable)
- Tooling: Composer, npm/yarn, GitHub Actions / GitLab CI, Docker, Sentry, Cloudflare

> Note: Harsher Core deliberately excludes utility frameworks like Tailwind by default – styling is based on classic CSS/SCSS/SASS approaches to keep visual systems flexible and framework-neutral.

---

## Team

- **Mgr. Daniel Dobrý — Product Owner · Frontend Developer · Visual & UX Lead**  
  (danieldobry.cz)  
  Responsible for product strategy, UX and frontend delivery. Coordinates design and development, manages backlogs and client communication.

- **Jakub Filip — Owner, PrismSoft · Backend Lead**  
  (prismsoft.cz)  
  Responsible for backend architecture, integrations and platform reliability. Leads server, API and data-layer design.

---

## Roadmap (high level)

- Complete modularization of social and e-commerce modules.
- Production reference for React Native mobile sync and offline-first patterns.
- Improved orchestration templates for Docker / Kubernetes deployment.
- Registry for reusable Harsher packages and a package manager workflow.

---

## About the Maintainers

### Daniel Dobrý - Product Owner & Frontend Lead
**[danieldobry.cz](https://danieldobry.cz)** 

**Summary**
- Freelance developer & PM since December 2017.
- Building custom websites, e-shops, company systems and mobile experiences.
- Over 7 years of experience in frontend engineering, UX, SEO and performance.
- Coordinates teams and external specialists for full-cycle delivery.

**Technologies**
- **Frontend**: HTML (Latte), CSS, SCSS, SASS, JavaScript (vanilla, jQuery, Vue.js), React, React Native, Next.js
- **Backend**: PHP, MySQL, Nette Framework, Composer
- **CMS**: WordPress development (themes, plugins, WooCommerce, child themes)
- **DevOps / Tooling**: Git, GitHub, GitLab, Docker, Azure, Sentry, Cloudflare
- **SEO / Performance**: Core Web Vitals, caching, lazy loading, image optimization
- **Other**: basic Python, dataset prep for ML/AI, content writing, graphics (Adobe suite)

**Education**
- **Masaryk University** — Theory of Interactive Media (Mgr., 2023–2025)  
- **Net Office Orlová** — IT (2015–2019)

---

### Jakub Filip - Backend Lead & DevOps
**[prismsoft.cz](https://prismsoft.cz)** • PrismSoft s.r.o.

**Summary**
- Founder & lead engineer at PrismSoft.
- Specializes in backend architecture, APIs, secure integrations and performance-focused systems.
- Provides DevOps, infrastructure automation, CI/CD and enterprise-grade backend solutions.

**Technologies**
- PHP, Nette Framework, MySQL, PostgreSQL
- Docker, Docker Compose, Kubernetes
- REST/GraphQL API design
- Cloud automation & deployments
- System integrations, scalability, observability

**Education**
- **Net Office Orlová** — IT (2015–2019)

---

**Clients & collaborations**
Carebot s.r.o., baraja.cz, obscurefreaks.cz, Sanctuary.cz, Kampot.cz, nobugs.cz, BeeSystematic and others.

---

## License

Harsher Core is released under the **MIT License**. See `LICENSE` for details.
