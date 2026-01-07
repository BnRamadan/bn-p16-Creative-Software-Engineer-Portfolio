# BnRamadan Portfolio

> **Modern, animated, high-performance Creative Software Engineer portfolio** showcasing 11+ Completed projects with cutting-edge web technologies and available in +17 languages.

[![Next.js](https://img.shields.io/badge/Next.js-15.2-black?logo=next.js)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-19_RC-61DAFB?logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwind-css)](https://tailwindcss.com)
[![GSAP](https://img.shields.io/badge/GSAP-3.12-00D084?logo=greensock)](https://gsap.com)
[![Three.js](https://img.shields.io/badge/Three.js_CDN-0.147-000000?logo=three.js)](https://threejs.org)
[![Lenis](https://img.shields.io/badge/Lenis-1.1-10B981?logo=scroll)](https://lenis.darkroom.engineering)
[![Lucide](https://img.shields.io/badge/Lucide_React-0.460-000000?logo=lucide)](https://lucide.dev)
[![i18n](https://img.shields.io/badge/i18n-react--i18next-26A69A?logo=i18next)](https://react.i18next.com)
[![Vercel Demo](https://img.shields.io/badge/Vercel-Demo_Only-000000?logo=vercel)](https://bnramadan.com)
[![Hostinger](https://img.shields.io/badge/Hostinger-Production-FF6B00?logo=hostinger)](https://hostinger.ae?REFERRALCODE=bnramadan)
[![MIT License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Table of Contents

-   [Live Demo](#live-demo)
-   [Features](#features)
    -   [Core Features](#core-features)
    -   [Interactive Magic](#interactive-magic)
    -   [Project Showcase](#project-showcase)
    -   [Global Localization](#global-localization)
-   [Tech Stack](#tech-stack)
-   [Project Structure](#project-structure)
-   [Performance & Benchmarks](#performance--benchmarks)
-   [Projects Included](#projects-included)
-   [SEO & Accessibility](#seo--accessibility)
-   [License](#license)
-   [Author](#author)
-   [Support](#support)

---

## Live Demo

**Try It in Seconds (No Setup Needed):** [bnramadan.com](https://bnramadan.com)

## Features

### Core Features

-   **Responsive Design** – Mobile, tablet, desktop optimized
-   **Smooth Animations** – GSAP with ScrollTrigger for fluid interactions
-   **High Performance** – Lighthouse 90+ scores across all categories
-   **Smart Localization** – Auto-detects user country & language (18 languages supported)
-   **Global SEO** – Hreflang tags & localized metadata for maximum reach
-   **SEO & Accessibility** – WCAG 2.1 AA compliant, JSON-LD structured data
-   **Zero Config** – Just `pnpm dev` and you're ready to go

### Interactive Magic

-   **Custom Animated Cursor** – Desktop-only interactive cursor with smooth tracking
-   **Scroll Progress Indicator** – Visual progress bar showing scroll position
-   **Particle Background** – Dynamic particle system for visual depth
-   **Lenis Smooth Scrolling** – Buttery smooth scroll experience
-   **Page Transition Animations** – Seamless transitions between pages
-   **Hover Project Previews** – Interactive video previews on project hover
-   **3D Skills Sphere** – Interactive Three.js sphere showcasing technical skills
-   **Optimized Preloader** – Lightweight animated bars with synchronized text reveal for instant site visibility

### Project Showcase

-   **11+ Real Projects** – MERN, Shopify, WordPress, and more
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

---

## Tech Stack

| Category         | Technology                 | Purpose                              |
| ---------------- | -------------------------- | ------------------------------------ |
| **Framework**    | Next.js 15.2 (React 19 RC) | Server-side rendering & routing      |
| **Language**     | TypeScript 5.3             | Type-safe development                |
| **Localization** | next-intl 3.26             | Internationalization & middleware    |
| **Styling**      | Tailwind CSS 3.4           | Utility-first CSS framework          |
| **Animations**   | GSAP 3.12 + ScrollTrigger  | Advanced scroll-triggered animations |
| **3D Graphics**  | Three.js (CDN) 0.147       | Interactive 3D skills visualization  |
| **Scrolling**    | Lenis 1.1                  | Smooth scroll behavior               |
| **Icons**        | Lucide React 0.460         | Beautiful icon library               |
| **Analytics**    | Google Analytics 4         | User behavior tracking               |
| **Build Tool**   | Next.js Built-in           | Optimized bundling & compilation     |

---

## Project Structure

```
portfolio-2.0/
├── app/                          # Next.js App Router
│   ├── [locale]/                # Dynamic locale routes
│   │   ├── _components/         # Page-specific components
│   │   │   ├── Banner.tsx       # Hero section with animated intro
│   │   │   ├── AboutMe.tsx      # About section with scroll animations
│   │   │   ├── Skills.tsx       # 3D interactive skills sphere
│   │   │   ├── Project.tsx      # Individual project card component
│   │   │   └── ProjectList.tsx  # Projects grid with filtering
│   │   ├── projects/            # Project routes
│   │   │   ├── [slug]/          # Dynamic project detail pages
│   │   │   │   ├── _components/
│   │   │   │   │   └── ProjectDetails.tsx
│   │   │   │   └── page.tsx
│   │   │   └── allprojects/     # All projects listing page
│   │   ├── layout.tsx           # Root layout with providers
│   │   ├── page.tsx             # Home page
│   │   ├── template.tsx         # Page transition template
│   │   └── globals.css          # Global styles
│   └── sitemap.ts               # Dynamic sitemap generation
├── components/                   # Reusable UI components
│   ├── Navbar.tsx               # Animated navigation menu
│   ├── CustomCursor.tsx         # Custom cursor component
│   ├── ParticleBackground.tsx   # Particle system background
│   ├── Preloader.tsx            # Loading screen with progress
│   ├── ScrollProgressIndicator.tsx # Scroll progress bar
│   ├── SmoothScrollWrapper.tsx  # Lenis scroll wrapper
│   ├── TransitionLink.tsx       # Animated page transitions
│   ├── ErrorBoundary.tsx        # Error handling component
│   ├── Button.tsx               # Reusable button component
│   ├── SectionTitle.tsx         # Section heading component
│   ├── ShinyText.tsx            # Animated text effect
│   └── icons/                   # Custom SVG icons
├── lib/                          # Utilities & data
│   ├── data.ts                  # Projects, skills, and general info
│   ├── utils.ts                 # Helper functions
│   └── sleep.ts                 # Utility functions
├── types/                        # TypeScript type definitions
│   ├── index.ts                 # Project & skill types
│   └── three.d.ts               # Three.js type declarations
├── public/                       # Static assets
│   ├── logo/                    # Logo assets
│   ├── projects/                # Project video previews
│   │   ├── deskmoc/             # Desktop video previews
│   │   └── phonemoc/            # Mobile video previews
│   ├── manifest.json             # PWA manifest
│   └── robots.txt                # SEO robots file
├── next.config.ts                # Next.js configuration
├── tailwind.config.ts            # Tailwind CSS configuration
├── tsconfig.json                 # TypeScript configuration
└── package.json                  # Dependencies & scripts
```

### Key Components Overview

-   **Banner** – Hero section with animated text, statistics, and call-to-action buttons
-   **AboutMe** – Personal introduction with scroll-triggered animations
-   **Skills** – Interactive 3D sphere displaying 50+ technical skills with drag controls
-   **ProjectList** – Filterable grid of projects with video previews and hover effects
-   **Navbar** – Full-screen animated menu with social links and navigation
-   **CustomCursor** – Desktop-only animated cursor that follows mouse movement
-   **Preloader** – Optimized animated bars with synchronized text reveal, ensuring instant site visibility
-   **ParticleBackground** – Dynamic particle system for visual enhancement

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

-   **Delayed Loading:** Google Analytics/GTM loaded after 3s (improves FCP)
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

## Projects Included

### 1. **Tawazun** – MERN Habit Tracker

-   **Live:** [Tawazun](https://tawazun.bnramadan.com)
-   **Source:** [GitHub](https://github.com/BnRamadan/bn-p15-Tawazun-platform-MERN)
-   **Tech Stack:**
    [![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react)](https://react.dev) [![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)](https://www.typescriptlang.org) [![Node.js](https://img.shields.io/badge/Node.js-20-339933?logo=node.js)](https://nodejs.org) [![Express](https://img.shields.io/badge/Express-4.19-000000?logo=express)](https://expressjs.com) [![MongoDB](https://img.shields.io/badge/MongoDB-7-47A248?logo=mongodb)](https://www.mongodb.com) [![Socket.io](https://img.shields.io/badge/Socket.io-4.7-000000?logo=socket.io)](https://socket.io) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwind-css)](https://tailwindcss.com) [![Framer Motion](https://img.shields.io/badge/Framer_Motion-10-FF6B6B?logo=framer)](https://www.framer.com/motion) [![Zustand](https://img.shields.io/badge/Zustand-4-FF6B6B?logo=react)](https://zustand-demo.pmnd.rs) [![React Query](https://img.shields.io/badge/React_Query-4-FF4154?logo=react-query)](https://tanstack.com/query)
-   **Features:** Advanced habit tracking, community features, real-time chat, achievement system, Arabic RTL support

### 2. **Fall In Scent** – Shopify Perfume Store

-   **Live:** [fallin-eg.com](https://fallin-eg.com/)
-   **Tech Stack:**
    [![Shopify](https://img.shields.io/badge/Shopify-2025-95BF47?logo=shopify)](https://shopify.com) [![Liquid](https://img.shields.io/badge/Liquid-Templating-000000?logo=liquid)](https://shopify.github.io/liquid) [![Payment Gateways](https://img.shields.io/badge/Payment_Gateways-Fawry_&_Paymob-FF6B6B)](https://fawry.com) ![SEO](https://img.shields.io/badge/SEO-Optimized-4285F4?logo=google)
-   **Features:** Premium perfume collection, fast delivery, flexible policies, customer reviews, fully responsive

### 3. **Yoka Canvas** – Bilingual Designer Portfolio

-   **Live:** [yokacanvas.com](https://yokacanvas.com)
-   **Source:** [GitHub](https://github.com/BnRamadan/bn-p14-Creative_Designer_Portfolio)
-   **Tech Stack:**
    [![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react)](https://react.dev) [![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)](https://www.typescriptlang.org) [![Vite](https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite)](https://vitejs.dev) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwind-css)](https://tailwindcss.com) [![Framer Motion](https://img.shields.io/badge/Framer_Motion-10-FF6B6B?logo=framer)](https://www.framer.com/motion) [![PWA](https://img.shields.io/badge/PWA-Ready-5A5A5A?logo=pwa)](https://web.dev/progressive-web-apps) [![i18n](https://img.shields.io/badge/i18n-react--i18next-26A69A?logo=i18next)](https://react.i18next.com) ![SEO](https://img.shields.io/badge/SEO-Optimized-4285F4?logo=google)
-   **Features:** Bilingual support (EN/AR), dark/light theme, interactive portfolio, PWA capabilities, offline support

### 4. **Yoi Cosmetics** – WooCommerce Hair Care Store

-   **Live:** [yoi-cosmetics.com](https://yoi-cosmetics.com/)
-   **Tech Stack:**
    [![WordPress](https://img.shields.io/badge/WordPress-6.6-21759B?logo=wordpress)](https://wordpress.org) [![WooCommerce](https://img.shields.io/badge/WooCommerce-8-96588A?logo=woocommerce)](https://woocommerce.com) [![PHP](https://img.shields.io/badge/PHP-8.3-777BB4?logo=php)](https://php.net) ![Arabic RTL](https://img.shields.io/badge/Arabic_RTL-Supported-000000)![Bundle Offers](https://img.shields.io/badge/Bundle_Offers-Dynamic-FF6B6B)
-   **Features:** Premium hair care products, exclusive bundles, dynamic pricing, responsive design, Arabic RTL

### 5. **Baly Leather** – EasyOrders Leather Store

-   **Live:** [balyleather.net](https://balyleather.net/)
-   **Tech Stack:**
    ![EasyOrders](https://img.shields.io/badge/EasyOrders-Platform-FF6B6B)
    ![Responsive](https://img.shields.io/badge/Responsive-Design-4285F4?logo=css3)
    ![Arabic RTL](https://img.shields.io/badge/Arabic_RTL-Supported-000000)
    ![Secure Checkout](https://img.shields.io/badge/Secure_Checkout-SSL-4CAF50)
-   **Features:** Handcrafted leather goods, elegant design, secure transactions, mobile optimized

### 6. **BnRamadan Portfolio** – Creative Software Engineer Portfolio

-   **Live:** [bnramadan.com](https://bnramadan.com/en)
-   **Source:** [GitHub](https://github.com/BnRamadan/bn-p16-My-Portfolio)
-   **Tech Stack:**
    [![Next.js](https://img.shields.io/badge/Next.js-15.2-black?logo=next.js)](https://nextjs.org)
    [![React](https://img.shields.io/badge/React-19_RC-61DAFB?logo=react)](https://react.dev)
    [![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)](https://www.typescriptlang.org)
    [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwind-css)](https://tailwindcss.com)
    [![GSAP](https://img.shields.io/badge/GSAP-3.12-00D084?logo=greensock)](https://gsap.com)
    [![Three.js](https://img.shields.io/badge/Three.js_CDN-0.147-000000?logo=three.js)](https://threejs.org)
    [![i18n](https://img.shields.io/badge/i18n-react--i18next-26A69A?logo=i18next)](https://react.i18next.com)
    [![Lucide](https://img.shields.io/badge/Lucide_React-0.460-000000?logo=lucide)](https://lucide.dev)

-   **Features:** Modern, animated, high-performance personal portfolio available in +17 languages.

### 7. **Thermo Egypt** – Shopify Winter Wear Store

-   **Live:** [thermoegypt.com](https://thermoegypt.com)

-   **Tech Stack:**
    [![Shopify](https://img.shields.io/badge/Shopify-2025-95BF47?logo=shopify)](https://shopify.com) [![Liquid](https://img.shields.io/badge/Liquid-Templating-000000?logo=liquid)](https://shopify.github.io/liquid) ![WooCommerce Migration](https://img.shields.io/badge/WooCommerce→Shopify-Migration-FF6B6B)
    ![Arabic RTL](https://img.shields.io/badge/Arabic_RTL-Supported-000000)
-   **Features:** Thermal clothing collections, exclusive discounts, fast checkout, fully responsive

### 8. **Vllol** – Video Editing Portfolio

-   **Live:** [vllol.com](https://vllol.com)
-   **Source:** [GitHub](https://github.com/BnRamadan/bn-p13-Creative-Video_Editor_portfolio)
-   **Tech Stack:**
    [![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react)](https://react.dev) [![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)](https://www.typescriptlang.org) [![Vite](https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite)](https://vitejs.dev) [![Framer Motion](https://img.shields.io/badge/Framer_Motion-10-FF6B6B?logo=framer)](https://www.framer.com/motion) [![PWA](https://img.shields.io/badge/PWA-Ready-5A5A5A?logo=pwa)](https://web.dev/progressive-web-apps) [![i18n](https://img.shields.io/badge/i18n-react--i18next-26A69A?logo=i18next)](https://react.i18next.com) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwind-css)](https://tailwindcss.com) ![SEO](https://img.shields.io/badge/SEO-Optimized-4285F4?logo=google)
-   **Features:** Bilingual portfolio, interactive gallery, dark/light theme, PWA ready, smooth animations

### 9. **BnRamadan Store** – Full-Stack MERN E-commerce

-   **Live:** [bnramadanstore.vercel.app](https://bnramadanstore.vercel.app/)
-   **Source:** [GitHub](https://github.com/BnRamadan/bn-fs-mern2-e-commerce-all)
-   **Tech Stack:**
    [![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react)](https://react.dev) [![Node.js](https://img.shields.io/badge/Node.js-20-339933?logo=node.js)](https://nodejs.org) [![Express](https://img.shields.io/badge/Express-4.19-000000?logo=express)](https://expressjs.com) [![MongoDB](https://img.shields.io/badge/MongoDB-7-47A248?logo=mongodb)](https://www.mongodb.com) ![MERN](https://img.shields.io/badge/MERN-Stack-FF6B6B?logo=mongodb) [![JWT](https://img.shields.io/badge/JWT-Auth-000000?logo=jsonwebtokens)](https://jwt.io) [![Vercel](https://img.shields.io/badge/Vercel-Deployed-000000?logo=vercel)](https://vercel.com)
-   **Features:** Product browsing, shopping cart, user authentication, admin panel, fully responsive

### 10. **MS NFSA** – WordPress Food Safety Consultant

-   **Live:** [msnfsa.ifhive.com](https://msnfsa.ifhive.com)
-   **Tech Stack:**
    [![WordPress](https://img.shields.io/badge/WordPress-6.6-21759B?logo=wordpress)](https://wordpress.org) [![PHP](https://img.shields.io/badge/PHP-8.3-777BB4?logo=php)](https://php.net) ![Responsive](https://img.shields.io/badge/Responsive-Design-4285F4?logo=css3) ![Arabic RTL](https://img.shields.io/badge/Arabic_RTL-Supported-000000)![SEO](https://img.shields.io/badge/SEO-Optimized-4285F4?logo=google)
-   **Features:** Expert profile, NFSA compliance guidance, international standards, bilingual content

### 11. **SG SOC Analyst** – Cybersecurity Portfolio

-   **Live:** [sgsocanalyst.vercel.app](https://sgsocanalyst.vercel.app/)
-   **Source:** [GitHub](https://github.com/BnRamadan/bn-p12-sg_portfolio)
-   **Tech Stack:**
    [![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react)](https://react.dev) [![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)](https://www.typescriptlang.org) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwind-css)](https://tailwindcss.com) [![Framer Motion](https://img.shields.io/badge/Framer_Motion-10-FF6B6B?logo=framer)](https://www.framer.com/motion) [![Vercel](https://img.shields.io/badge/Vercel-Deployed-000000?logo=vercel)](https://vercel.com) [![i18n](https://img.shields.io/badge/i18n-react--i18next-26A69A?logo=i18next)](https://react.i18next.com)
-   **Features:** Professional showcase, interactive timeline, dark mode UI, fully responsive, performance-first

### 12. **One Piece Slider** – Vanilla JS Anime Slider

-   **Live:** [bn-fe-5-one-piece-slider.vercel.app](https://bn-fe-5-one-piece-slider.vercel.app/)
-   **Source:** [GitHub](https://github.com/BnRamadan/bn-fe-5-one-piece-slider)
-   **Tech Stack:**
    [![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) ![DOM](https://img.shields.io/badge/DOM-Manipulation-000000?logo=javascript)![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-Pure-FF6B6B)![Responsive](https://img.shields.io/badge/Responsive-Design-4285F4?logo=css3)
-   **Features:** Interactive bounty cards, smooth slider, pirate design, mobile responsive, lightweight

---

_Each project includes live demo, source code, video preview, and interactive tech badges._

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
-   **robots.txt** – Search engine crawling instructions

### Accessibility (WCAG 2.1 AA)

-   **ARIA Labels** – Proper ARIA attributes for screen readers
-   **Keyboard Navigation** – Full keyboard support with focus management
-   **Color Contrast** – Minimum 4.5:1 contrast ratio for text
-   **Focus Indicators** – Visible focus states for all interactive elements
-   **Screen Reader Support** – Semantic markup and descriptive labels
-   **Focus Trap** – Modal menus with proper focus trapping

---

## License

[MIT License](LICENSE) – Free to use, modify, and learn from.

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

**Last Updated:** November 2025
**Version:** 2.0.0
**Status:** Active Development

---

> **"Built with passion, animated with precision, deployed in seconds."**
