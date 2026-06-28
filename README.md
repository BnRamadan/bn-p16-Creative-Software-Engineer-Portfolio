# BnRamadan Portfolio

> **Modern, animated, high-performance portfolio platform** — a Creative Software Engineer showcase backed by a custom database-driven CMS, an AI content layer, and full agent/SEO readiness, available in **18 languages**.

[![Next.js](https://img.shields.io/badge/Next.js-15.2-black?logo=next.js)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-19_RC-61DAFB?logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwind-css)](https://tailwindcss.com)
[![GSAP](https://img.shields.io/badge/GSAP-3.12-00D084?logo=greensock)](https://gsap.com)
[![Three.js](https://img.shields.io/badge/Three.js_CDN-0.147-000000?logo=three.js)](https://threejs.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?logo=mongodb)](https://www.mongodb.com)
[![i18n](https://img.shields.io/badge/i18n-18_languages-26A69A?logo=i18next)](https://next-intl.dev)
[![AI](https://img.shields.io/badge/AI-Multi--provider-8b5cf6?logo=openai&logoColor=white)](#ai-content-tooling)
[![Vercel](https://img.shields.io/badge/Vercel-Live-000000?logo=vercel)](https://bnramadan.com)
[![License](https://img.shields.io/badge/License-All_Rights_Reserved-red)](LICENSE)

---

## Table of Contents

-   [Live](#live)
-   [Features](#features)
    -   [Core Features](#core-features)
    -   [Headless CMS & Admin](#headless-cms--admin)
    -   [AI Content Tooling](#ai-content-tooling)
    -   [Interactive Magic](#interactive-magic)
    -   [Project Showcase](#project-showcase)
    -   [Global Localization](#global-localization)
    -   [Answer-Engine Optimization (AEO)](#answer-engine-optimization-aeo)
-   [Tech Stack](#tech-stack)
-   [Architecture](#architecture)
-   [Performance & Benchmarks](#performance--benchmarks)
-   [Featured Work](#featured-work)
-   [SEO & Accessibility](#seo--accessibility)
-   [License](#license)
-   [Author](#author)
-   [Support](#support)

---

## Live

**Try It in Seconds (No Setup Needed):** [bnramadan.com](https://bnramadan.com)

## Features

### Core Features

-   **Database-Driven Content** – Projects, skills, filters, hero stats, footer & CV all served from MongoDB
-   **Responsive Design** – Mobile, tablet, desktop optimized
-   **Smooth Animations** – GSAP with ScrollTrigger for fluid interactions
-   **High Performance** – Lighthouse 90+ scores across all categories
-   **Smart Localization** – Auto-detects user country & language (18 languages supported)
-   **Global SEO** – Hreflang tags & localized metadata for maximum reach
-   **SEO & Accessibility** – WCAG 2.1 AA compliant, JSON-LD structured data

### Headless CMS & Admin

-   **No-Code Content Management** – A secure admin dashboard to manage every part of the site — projects, skills, categories/filters, hero statistics, footer links, and the CV — with zero code changes
-   **Editable Everywhere** – Hero, tagline, about and footer copy are all editable from the dashboard — not just structured data
-   **Auto-Translation** – New content is automatically translated into all 18 languages on save
-   **Multi-Category Filtering** – Each project can belong to several filters, with sub-filters (e.g. e-commerce → Shopify / WooCommerce)
-   **Draft & Publish** – Work on projects privately before they go live
-   **Drag-and-Drop Ordering, Activity Log & Toasts** – A polished, modern editing experience
-   **Authenticated & Hardened** – JWT-secured, rate-limited access (implementation details intentionally not documented here)
-   **Automated Weekly Backups** – Scheduled database snapshots for peace of mind

### AI Content Tooling

-   **AI Description Generator** – Paste a README, a presentation, or rough notes (in any language) and generate a polished project description that matches the site's house style
-   **AI CV Auto-Fill** – Paste a full CV/resume and the AI structures it into every field of the CV editor
-   **Multi-Provider Fallback** – Routes across several AI providers automatically, so generation stays fast and resilient
-   **Built-in Guardrails** – Uses only the facts provided, never invents data, and ignores instructions embedded in the source

### Interactive Magic

-   **Custom Animated Cursor** – Desktop-only interactive cursor with smooth tracking
-   **Scroll Progress Indicator** – Visual progress bar showing scroll position
-   **Particle Background** – Dynamic particle system for visual depth
-   **Lenis Smooth Scrolling** – Buttery smooth scroll experience
-   **Page Transition Animations** – Seamless transitions between pages
-   **Hover Project Previews** – Interactive video previews on project hover
-   **3D Skills Sphere** – Interactive Three.js sphere showcasing technical skills
-   **Global Reach Map** – Interactive world map plotting every country a project was delivered in, with hover/keyboard tooltips
-   **Localized CV Page** – A fully designed, downloadable CV available in all 18 languages with RTL support
-   **Optimized Preloader** – Lightweight animated bars with synchronized text reveal for instant site visibility

### Project Showcase

-   **18+ Real Projects** – MERN, Shopify, WordPress, and more
-   **Smart Filtering** – Filter by category & platform
-   **Live Demos** – Direct links to deployed projects
-   **Source Code** – GitHub repositories for each project
-   **Video Previews** – Auto-playing video previews (desktop & mobile optimized)
-   **Dynamic Routing** – Individual project detail pages with rich content

### Global Localization

-   **18 Supported Languages** – English, Arabic, French, German, Spanish, Japanese, Chinese, Russian, Portuguese, Turkish, Polish, Korean, Hindi, Urdu, Persian, Latin, Italian, Dutch.
-   **Smart Middleware** – Automatically redirects users based on their country (Saudi Arabia → Arabic, Japan → Japanese, ...etc).
-   **RTL Support** – Full Right-to-Left layout support for Arabic, Urdu, and Persian.
-   **Localized Content** – Fully translated interface, projects, and metadata.

### Answer-Engine Optimization (AEO)

Built to be discoverable not just by search engines, but by AI answer engines (ChatGPT, Claude, Perplexity, Gemini):

-   **Dynamic `llms.txt`** – An AI-readable summary of the site, generated live from the database
-   **AI Crawler Signals** – Explicit `robots.txt` permissions and content-usage signals for answer engines
-   **WebMCP Tools** – Exposes the portfolio as agent-usable tools (search/open projects, get contact) for AI browsers
-   **Dynamic Open Graph Images** – A branded share card generated per project
-   **Rich Structured Data** – Person, Organization & ProfessionalService JSON-LD

---

## Tech Stack

| Category         | Technology                 | Purpose                              |
| ---------------- | -------------------------- | ------------------------------------ |
| **Framework**    | Next.js 15 (React 19)      | SSR, ISR & routing                   |
| **Language**     | TypeScript 5               | Type-safe development                |
| **Database**     | MongoDB + Mongoose         | Headless CMS content store           |
| **Auth**         | JWT + bcrypt               | Secured admin access                 |
| **AI Layer**     | Multi-provider chat API    | Content generation & CV parsing      |
| **Localization** | next-intl (18 languages)   | Internationalization & middleware    |
| **Styling**      | Tailwind CSS 3.4           | Utility-first CSS framework          |
| **Animations**   | GSAP 3.12 + ScrollTrigger  | Advanced scroll-triggered animations |
| **3D & Maps**    | Three.js · d3-geo          | Skills sphere & interactive world map|
| **Scrolling**    | Lenis 1.1                  | Smooth scroll behavior               |
| **Icons**        | Lucide React               | Icon library                         |
| **Analytics**    | Google Tag Manager + GA4   | Tag-managed behavior tracking        |
| **Hosting**      | Vercel                     | Edge network deployment              |

---

## Architecture

A modern Next.js **App Router** application with a clean separation of concerns:

-   **Presentation** – Server Components for fast, SEO-friendly HTML; Client Components only where interactivity is needed (3D sphere, world map, smooth scroll). Heavy libraries are dynamically imported on demand.
-   **Internationalization** – Locale-aware routing and middleware that detects the visitor's country and serves the right language, with full RTL support.
-   **Content layer** – A MongoDB-backed **headless CMS** powers all dynamic content. Public pages read through cached, revalidate-on-edit data loaders; the secured admin dashboard writes to it.
-   **AI layer** – A provider-agnostic generation service with automatic fallback handles description writing and CV parsing.
-   **Edge delivery** – Static generation + ISR, optimized media via CDN, and Vercel's edge network for global speed.

> Admin, API, and authentication internals are intentionally omitted from this overview.

---

## Performance & Benchmarks

> **"A website that loads faster than you can blink."**

This portfolio is engineered for **extreme performance**, achieving near-perfect scores across all major benchmarking tools. Built with **Next.js 15**, **React 19**, and deployed on **Vercel's Edge Network** for global speed.

---

### Official Test Results

[![Lighthouse](https://img.shields.io/badge/Lighthouse-100%25_SEO-4285F4?logo=lighthouse&logoColor=white)](https://pagespeed.web.dev/analysis/https-bnramadan-com/)
[![GTmetrix](https://img.shields.io/badge/GTmetrix-Grade_A-00D084?logo=gtmetrix&logoColor=white)](https://gtmetrix.com/)
[![Best Practices](https://img.shields.io/badge/Best_Practices-100%2F100-success?logo=google&logoColor=white)](https://pagespeed.web.dev/)

| Platform                        |                    Performance                    |                         SEO                         |                     Accessibility                     |
| :------------------------------ | :-----------------------------------------------: | :-------------------------------------------------: | :---------------------------------------------------: |
| **Google Lighthouse (Desktop)** | ![93](https://img.shields.io/badge/93%25-success) | ![100](https://img.shields.io/badge/100%25-success) | ![94](https://img.shields.io/badge/94%25-brightgreen) |
| **Google Lighthouse (Mobile)**  | ![82](https://img.shields.io/badge/82%25-success) | ![100](https://img.shields.io/badge/100%25-success) | ![94](https://img.shields.io/badge/94%25-brightgreen) |
| **GTmetrix**                    | ![85](https://img.shields.io/badge/85%25-success) | ![100](https://img.shields.io/badge/100%25-success) | ![94](https://img.shields.io/badge/94%25-brightgreen) |

### Test It Yourself

Verify these results in real-time:

-   [Google PageSpeed Insights](https://pagespeed.web.dev/analysis/https-bnramadan-com/)
-   [GTmetrix Report](https://gtmetrix.com/)

---

### Core Web Vitals (Real-World Metrics)

These are **real measurements** from production, not simulated:

| Metric                             |  Value   | Google Standard |      Status      |
| :--------------------------------- | :------: | :-------------: | :--------------: |
| **LCP** (Largest Contentful Paint) |  `1.1s`  |     < 2.5s      | 🟢 **Excellent** |
| **FCP** (First Contentful Paint)   |  `1.0s`  |     < 1.8s      | 🟢 **Excellent** |
| **TBT** (Total Blocking Time)      | `260ms`  |     < 300ms     | 🟢 **Excellent** |
| **CLS** (Cumulative Layout Shift)  |  `0.00`  |      < 0.1      |  🟢 **Perfect**  |
| **TTFB** (Time to First Byte)      | `~400ms` |     < 800ms     |   🟢 **Fast**    |
| **Speed Index**                    |  `1.8s`  |     < 3.4s      |   🟢 **Fast**    |

> **What does this mean?**
> Your users see content in **1 second** or less, the page never shifts unexpectedly, and interactions feel instant. This is **world-class performance**.

---

### How We Achieved These Results

#### **Smart Asset Management**

-   **Next/Image Component:** Automatic AVIF/WebP conversion + lazy loading
-   **Font Optimization:** Google Fonts optimized with `next/font` (zero layout shift)
-   **CDN Delivery:** Static assets served from Vercel Edge Network (120+ locations)
-   **Brotli Compression:** Text files compressed to 70% of original size

#### **Code Architecture**

-   **Tree Shaking:** Unused code eliminated at build time
-   **Code Splitting:** Only load JavaScript needed for current page
-   **Dynamic Imports:** Heavy 3D libraries (Three.js) loaded on-demand
-   **Minification:** All JS/CSS minified and optimized

#### **Performance Budget**

-   **Total Page Size:** < 2MB (including all assets)
-   **JavaScript Bundle:** < 650KB (gzipped)
-   **First Load JS:** ~200KB
-   **Font Files:** 258KB (cached for 1 year)

#### **Analytics & Monitoring**

-   **Tag-Managed:** A single Google Tag Manager container loads GA4 (no duplicate trackers)
-   **Service Worker:** Smart caching for returning visitors
-   **Resource Hints:** dns-prefetch + preconnect for critical origins

---

### Load Time Breakdown

```
TTFB ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 400ms
FCP  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.0s
LCP  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1s
TTI  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.4s
```

**Summary:** Users see the main content in **1.1 seconds**, and the page is fully interactive in **4.4 seconds**.

---

## Featured Work

Projects are managed through the built-in CMS and showcased **live** — always current, with no static list to maintain here.

**Browse the full, up-to-date portfolio:** [bnramadan.com](https://bnramadan.com/en/projects/allprojects)

Each project page includes a live demo, source link (where available), an auto-playing video preview, the tech stack, and a localized description.

---

## SEO & Accessibility

### SEO Features

-   **Semantic HTML** – Proper HTML5 semantic elements
-   **Meta Tags** – Comprehensive meta tags for social sharing
-   **Open Graph** – Rich previews for social media platforms (Localized)
-   **Twitter Cards** – Optimized Twitter sharing cards
-   **JSON-LD Structured Data** – Schema.org markup for better search visibility
-   **Hreflang Tags** – Correct language targeting for Google
-   **Localized Metadata** – Dynamic titles, descriptions, and keywords for every language
-   **Dynamic Sitemap** – Auto-generated sitemap for all routes and locales
-   **robots.txt** – Crawl rules with explicit signals for AI answer engines
-   **`llms.txt` & WebMCP** – AI-agent-readable site summary and agent tools (AEO)
-   **Dynamic OG Images** – Branded share cards generated per project

### Accessibility (WCAG 2.1 AA)

-   **ARIA Labels** – Proper ARIA attributes for screen readers
-   **Keyboard Navigation** – Full keyboard support with focus management
-   **Color Contrast** – Minimum 4.5:1 contrast ratio for text
-   **Focus Indicators** – Visible focus states for all interactive elements
-   **Screen Reader Support** – Semantic markup and descriptive labels
-   **Focus Trap** – Modal menus with proper focus trapping

---

## License

© Mohamed Bn Ramadan — **All rights reserved.**

This repository is shared publicly for **showcase and reference only**. It is **not**
licensed for reuse, redistribution, or deployment as your own. If you'd like to
collaborate or hire, please reach out via the links below.

---

## Author

**Mohamed Bn Ramadan**
Full-Stack Developer | Animation Enthusiast | Open Source Lover

-   **Portfolio:** [bnramadan.com](https://bnramadan.com)
-   **GitHub:** [@BnRamadan](https://github.com/BnRamadan)
-   **Email:** [contact@bnramadan.com](mailto:contact@bnramadan.com)
-   **WhatsApp:** [+20 102 598 0987](https://wa.me/+201025980987)
-   **LinkedIn:** [@BnRamadan](https://www.linkedin.com/in/bnramadan/)

---

## Support

For questions, suggestions, or collaboration opportunities:

-   **Email:** contact@bnramadan.com
-   **WhatsApp:** [+20 102 598 0987](https://wa.me/+201025980987)
-   **LinkedIn:** [@BnRamadan](https://www.linkedin.com/in/bnramadan/)

---

## Project Info

**Last Updated:** June 2026
**Version:** 3.0.0 — database-driven platform with AI tooling
**Status:** Live in Production

---

> **"Built with passion, animated with precision, deployed in seconds."**
