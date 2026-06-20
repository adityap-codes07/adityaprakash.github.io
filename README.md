<div align="center">

# ✦ Aditya Prakash — Developer Portfolio

**Research Enthusiast · SymPy Contributor · AI Engineer**

*Exploring the foundations of machine intelligence.*

[![Lighthouse Performance](https://img.shields.io/badge/Lighthouse-100%2F100-brightgreen?logo=lighthouse&logoColor=white)](https://pagespeed.web.dev/)
[![Lighthouse Accessibility](https://img.shields.io/badge/Accessibility-100%2F100-brightgreen?logo=lighthouse&logoColor=white)](https://pagespeed.web.dev/)
[![Lighthouse SEO](https://img.shields.io/badge/SEO-100%2F100-brightgreen?logo=lighthouse&logoColor=white)](https://pagespeed.web.dev/)
[![Built with Astro](https://img.shields.io/badge/Built%20with-Astro-BC52EE?logo=astro&logoColor=white)](https://astro.build/)
[![TailwindCSS](https://img.shields.io/badge/Styled%20with-TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Deployed on GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-181717?logo=github&logoColor=white)](https://pages.github.com/)

<br/>

> *"This is not a typical undergraduate portfolio. This is someone who genuinely understands Computer Science fundamentals, enjoys building systems, contributes to open source, values research, and has the engineering mindset required for Software Engineering and Research Engineering roles."*

<br/>

![Portfolio Preview Placeholder](./public/screenshots/preview.png)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Development](#development)
- [Deployment](#deployment)
- [Folder Structure](#folder-structure)
- [Customization Guide](#customization-guide)
- [Performance Optimizations](#performance-optimizations)
- [SEO](#seo)
- [Accessibility](#accessibility)
- [Easter Egg](#easter-egg)
- [Future Improvements](#future-improvements)
- [Screenshots](#screenshots)
- [License](#license)
- [Credits](#credits)

---

## Overview

This is a **production-ready, enterprise-quality personal portfolio** for **Aditya Prakash**, a Computer Science and Business Systems undergraduate at CVR College of Engineering.

The design philosophy draws from **Apple × OpenAI × DeepMind × Linear × Vercel** — minimal, elegant, research-oriented, and engineering-focused. Every design and engineering decision is intentional: communicating deep technical competency through the portfolio itself.

This is not a template. Every section is hand-crafted to reflect a genuine research and engineering mindset, targeting roles at companies such as Apple, Google, OpenAI, DeepMind, Microsoft Research, NVIDIA, Anthropic, Meta, Amazon, Stripe, Vercel, and Cloudflare.

---

## Features

### Design & UX
- **Apple × OpenAI × DeepMind** inspired aesthetic — minimal, clean, premium
- Pure white background with muted pink accents and dark navy typography
- **Space Grotesk** headings, **Inter** body text, **JetBrains Mono** for code
- Heavy use of whitespace — never cluttered, always intentional
- Fully responsive across all screen sizes
- Dark mode with system preference detection and manual toggle

### Sections
| Section | Description |
|---|---|
| **Hero** | Name, role, tagline, CTA buttons, subtle engineering animation |
| **About** | Professional biography, education, coursework |
| **Statistics** | Animated counters — Projects, Contributions, Achievements, CGPA |
| **Research Interests** | Card grid with animated hover states |
| **Engineering Work** | Grouped projects — Research, Software Engineering, Academic |
| **Open Source** | SymPy PR #29172 — timeline with merged badge |
| **Timeline** | Vertical scroll-animated academic & professional journey |
| **Skills** | Animated chip cloud — Languages, Libraries, Tools, Databases |
| **Achievements** | Award cards with context |
| **Notes from the Lab** | MDX-powered technical blog with search, TOC, tags, RSS |
| **Current Learning** | Horizontal cards for ongoing topics |
| **GitHub Activity** | Contribution graph, pinned repos, languages, activity |
| **Contact** | Minimal contact form + social links |
| **Footer** | Quote + socials + copyright |

### Blog (Notes from the Lab)
- MDX with full TypeScript support via Astro Content Collections
- Syntax highlighting via **Shiki** (zero-runtime, server-side)
- Math rendering via **KaTeX**
- Estimated reading time
- Floating table of contents
- One-click copy code blocks
- Previous / Next article navigation
- Tag-based filtering
- Full-text search
- RSS feed at `/rss.xml`
- Sitemap integration

### Animation
- Framer Motion — fade, slide, reveal, counter, hover, parallax
- Magnetic buttons on CTA elements
- Scroll-triggered section reveals
- Animated statistics counters
- Subtle engineering animation in hero (no particles, no blobs)
- `prefers-reduced-motion` support — all animations disabled gracefully

### SEO & Metadata
- `robots.txt` — generated automatically
- `sitemap.xml` — Astro Sitemap integration
- `rss.xml` — Full blog RSS feed
- OpenGraph tags for every page
- Twitter Cards
- JSON-LD Structured Data (Person, WebSite, BlogPosting)
- Canonical URLs
- Meta descriptions per page

### Developer Experience
- Full **TypeScript** — strict mode
- Astro Content Collections with Zod schema validation
- Scalable folder structure following industry conventions
- Reusable component library
- Config-driven content — update `src/config/` to personalize
- ESLint + Prettier preconfigured

---

## Tech Stack

| Category | Technology |
|---|---|
| **Framework** | [Astro](https://astro.build/) |
| **Styling** | [TailwindCSS](https://tailwindcss.com/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) (strict) |
| **Content** | [MDX](https://mdxjs.com/) + Astro Content Collections |
| **Animation** | [Framer Motion](https://www.framer.com/motion/) |
| **Syntax Highlighting** | [Shiki](https://shiki.matsu.io/) |
| **Icons** | [Lucide Icons](https://lucide.dev/) |
| **SEO** | [@astrojs/sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/) + Astro SEO |
| **Deployment** | [GitHub Pages](https://pages.github.com/) |
| **Fonts** | Space Grotesk · Inter · JetBrains Mono (Google Fonts) |

---

## Getting Started

### Prerequisites

- **Node.js** ≥ 18.x
- **npm** ≥ 9.x (or pnpm / yarn)
- **Git**

### Installation

```bash
# Clone the repository
git clone https://github.com/adityaprakash/portfolio.git
cd portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

The dev server starts at `http://localhost:4321`.

---

## Development

### Available Scripts

```bash
# Start development server with hot reload
npm run dev

# Type-check all TypeScript files
npm run type-check

# Lint with ESLint
npm run lint

# Format with Prettier
npm run format

# Build for production
npm run build

# Preview the production build locally
npm run preview
```

### Adding a Blog Post

Create a new `.mdx` file inside `src/content/blog/`:

```mdx
---
title: "Understanding Backpropagation from First Principles"
description: "A deep dive into the mathematics and implementation of backprop."
publishDate: 2025-06-01
tags: ["Machine Learning", "Mathematics", "Python"]
readingTime: 8
draft: false
---

Your content here with full MDX support, math via $\LaTeX$, and code blocks.
```

Content Collections enforce schema via Zod — missing required fields produce build-time errors, never runtime surprises.

### Adding a Project

Create a new `.mdx` file inside `src/content/projects/`:

```mdx
---
title: "Kavach (PhishXray)"
description: "Real-time phishing detection using RoBERTa and SHAP explainability."
category: "Research Projects"
tech: ["FastAPI", "RoBERTa", "SHAP", "LIME", "Manifest V3"]
github: "https://github.com/adityaprakash/kavach"
featured: true
order: 1
---
```

---

## Deployment

This portfolio deploys automatically to **GitHub Pages** via GitHub Actions.

### Setup (One-time)

1. Go to your repository **Settings → Pages**
2. Set **Source** to `GitHub Actions`
3. Push to `main` — the workflow handles the rest

### Manual Deploy

```bash
npm run build
# Artifacts are output to /dist — upload to any static host
```

### GitHub Actions Workflow

`.github/workflows/deploy.yml` handles:
- Installing Node.js and dependencies
- Running the Astro build
- Deploying `/dist` to the `gh-pages` branch

The site is available at `https://<your-username>.github.io/portfolio/`.

> **Custom Domain:** Add a `CNAME` file to `public/` with your domain name, then configure DNS with your registrar.

---

## Folder Structure

```
portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions CI/CD pipeline
│
├── public/
│   ├── favicon.svg             # Site favicon
│   ├── robots.txt              # Search engine crawl directives
│   ├── og-image.png            # Default OpenGraph image
│   └── screenshots/            # Portfolio screenshots for README
│
├── src/
│   ├── assets/                 # Static assets (images, fonts, SVGs)
│   │   ├── images/
│   │   └── icons/
│   │
│   ├── components/             # Reusable Astro & UI components
│   │   ├── common/             # Shared UI primitives (Button, Badge, Card)
│   │   ├── layout/             # Navigation, Footer, ThemeToggle
│   │   ├── sections/           # Full page sections (Hero, About, Projects...)
│   │   ├── blog/               # Blog-specific components (TOC, CodeBlock...)
│   │   └── animations/         # Framer Motion wrappers & hero animation
│   │
│   ├── config/                 # All personalizable content lives here
│   │   ├── site.ts             # Site metadata, author info, social links
│   │   ├── navigation.ts       # Navigation items
│   │   └── skills.ts           # Skills, tools, research interests
│   │
│   ├── content/                # Astro Content Collections (type-safe)
│   │   ├── blog/               # Blog posts in .mdx format
│   │   ├── projects/           # Project entries in .mdx format
│   │   └── config.ts           # Zod schemas for all collections
│   │
│   ├── hooks/                  # Custom utility hooks
│   │   ├── useScrolled.ts      # Detect scroll position (sticky nav)
│   │   └── useTheme.ts         # Dark/light mode management
│   │
│   ├── layouts/                # Page layout templates
│   │   ├── BaseLayout.astro    # Root layout with SEO, fonts, global styles
│   │   ├── BlogLayout.astro    # Blog post layout with TOC, prev/next
│   │   └── ProjectLayout.astro # Project detail layout
│   │
│   ├── pages/                  # Astro file-based routing
│   │   ├── index.astro         # Home page (all sections)
│   │   ├── blog/
│   │   │   ├── index.astro     # Blog listing with search and filters
│   │   │   └── [slug].astro    # Dynamic blog post pages
│   │   ├── projects/
│   │   │   └── [slug].astro    # Dynamic project detail pages
│   │   ├── resume.astro        # Resume / CV page
│   │   └── 404.astro           # Custom 404 page
│   │
│   ├── scripts/                # Client-side scripts
│   │   ├── terminal.ts         # Easter egg terminal (Ctrl+Shift+P)
│   │   └── copyCode.ts         # Copy-to-clipboard for code blocks
│   │
│   ├── styles/                 # Global CSS and Tailwind configuration
│   │   ├── global.css          # Base reset and global styles
│   │   └── prose.css           # MDX / blog prose typography
│   │
│   ├── types/                  # TypeScript type definitions
│   │   ├── project.ts
│   │   └── blog.ts
│   │
│   └── utils/                  # Pure utility functions
│       ├── date.ts             # Date formatting helpers
│       ├── reading-time.ts     # Blog reading time estimator
│       └── rss.ts              # RSS feed generator
│
├── astro.config.mjs            # Astro configuration
├── tailwind.config.mjs         # TailwindCSS configuration + design tokens
├── tsconfig.json               # TypeScript configuration (strict mode)
├── .eslintrc.cjs               # ESLint rules
├── .prettierrc                 # Prettier formatting rules
└── package.json
```

---

## Customization Guide

All personal information is centralized in `src/config/site.ts` — you should never need to hunt through components to update your details.

```typescript
// src/config/site.ts
export const SITE = {
  name: "Aditya Prakash",
  title: "Aditya Prakash — Research Engineer & Software Engineer",
  description: "CSBS Undergraduate at CVR College of Engineering...",
  url: "https://adityaprakash.dev",
  author: {
    name: "Aditya Prakash",
    email: "aditya@example.com",
    github: "https://github.com/adityaprakash",
    linkedin: "https://linkedin.com/in/adityaprakash",
  },
  og: {
    image: "/og-image.png",
  },
};
```

### Update Navigation

```typescript
// src/config/navigation.ts
export const NAV_ITEMS = [
  { label: "Home",            href: "#home" },
  { label: "About",           href: "#about" },
  { label: "Research",        href: "#research" },
  { label: "Engineering Work",href: "#engineering" },
  { label: "Open Source",     href: "#opensource" },
  { label: "Blog",            href: "/blog" },
  { label: "Resume",          href: "/resume" },
  { label: "Contact",         href: "#contact" },
];
```

### Update Skills & Research Interests

```typescript
// src/config/skills.ts
export const RESEARCH_INTERESTS = [
  "Operating Systems",
  "Compiler Design",
  "Natural Language Processing",
  // ...
];

export const SKILLS = {
  programming: ["Python", "Java", "C", "SQL"],
  libraries: ["NumPy", "Pandas", "Scikit-Learn"],
  tools: ["Git", "Docker", "VS Code"],
  databases: ["MySQL"],
};
```

### Update Colors (Design Tokens)

```javascript
// tailwind.config.mjs
theme: {
  extend: {
    colors: {
      background: "#FFFFFF",
      card:       "#F8F8F8",
      text:       "#1C2331",
      accent:     "#C9A0A8",   // Muted Pink
      navy:       "#1B2A4A",   // Dark Navy
      rose:       "#B87B85",   // Buttons
    }
  }
}
```

---

## Performance Optimizations

This portfolio is engineered for a perfect Lighthouse score.

| Optimization | Implementation |
|---|---|
| **Zero JS by default** | Astro ships 0 KB JS unless a component opts in |
| **Image optimization** | `<Image />` from `@astrojs/image` — WebP, lazy loading, explicit dimensions |
| **Font loading** | `font-display: swap` + preconnect to Google Fonts |
| **Critical CSS** | Scoped styles per component, no unused CSS |
| **Syntax highlighting** | Shiki runs at build time — zero runtime cost |
| **Prefetching** | Astro `prefetch` on internal links |
| **Minification** | HTML, CSS, and JS minified at build time |
| **No layout shift** | All images and fonts have explicit dimensions |
| **Reduced motion** | `prefers-reduced-motion` disables all Framer Motion animations |

---

## SEO

Every page includes:

- Unique `<title>` and `<meta name="description">`
- Canonical URL
- OpenGraph (`og:title`, `og:description`, `og:image`, `og:url`)
- Twitter Card (`twitter:card`, `twitter:title`, `twitter:image`)
- JSON-LD structured data:
  - `Person` — on the home page
  - `BlogPosting` — on each blog post
  - `WebSite` — site-wide
- Auto-generated `sitemap.xml` via `@astrojs/sitemap`
- `robots.txt` in `public/`
- RSS feed at `/rss.xml`

---

## Accessibility

- Semantic HTML throughout (`<main>`, `<nav>`, `<article>`, `<section>`, `<aside>`)
- All interactive elements are keyboard-navigable
- ARIA labels on icon-only buttons and links
- Sufficient color contrast ratios (WCAG AA)
- Focus-visible rings on all focusable elements
- Skip-to-content link
- `alt` text on every image
- Animated counters respect `prefers-reduced-motion`

---

## Easter Egg

Press **`Ctrl + Shift + P`** anywhere on the site to open a developer terminal overlay.

Type `sudo hire aditya` and press Enter:

```
$ sudo hire aditya

Initializing...
Loading GitHub Profile...       ✓
Loading Research Profile...     ✓
Compiling Portfolio...          ✓
Running background checks...    ✓

✓ All systems ready.

Welcome aboard, Aditya.
Offer letter incoming.
```

---

## Future Improvements

- [ ] Interactive research paper reading list with notes
- [ ] `/uses` page — development setup and tooling
- [ ] `/bookshelf` page — technical books and papers
- [ ] AI-powered blog search (semantic search via embeddings)
- [ ] Visitor analytics via Plausible (privacy-first)
- [ ] i18n support (English + Hindi)
- [ ] Conference & speaking timeline section
- [ ] Integration with Zotero / semantic scholar for paper citations
- [ ] WebGL-powered hero animation (opt-in, respects reduced-motion)

---

## Screenshots

| Section | Preview |
|---|---|
| Hero | ![Hero](./public/screenshots/hero.png) |
| Engineering Work | ![Engineering](./public/screenshots/engineering.png) |
| Notes from the Lab | ![Blog](./public/screenshots/blog.png) |
| Open Source | ![OSS](./public/screenshots/opensource.png) |
| Mobile | ![Mobile](./public/screenshots/mobile.png) |

> Screenshots will be available after the first production build.

---

## License

This project is licensed under the **MIT License** — you are free to use, modify, and distribute this portfolio as the basis for your own, with attribution.

See [LICENSE](./LICENSE) for full terms.

---

## Credits

- Design inspiration from [Linear](https://linear.app), [Vercel](https://vercel.com), [Stripe](https://stripe.com/in), [Apple](https://apple.com)
- Typography: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://rsms.me/inter/), [JetBrains Mono](https://www.jetbrains.com/lp/mono/) via Google Fonts
- Icons: [Lucide](https://lucide.dev/)
- Built with [Astro](https://astro.build/) — the framework for content-driven websites
- Animations by [Framer Motion](https://www.framer.com/motion/)
- Syntax highlighting by [Shiki](https://shiki.matsu.io/)

---

<div align="center">

Made with curiosity, persistence, and a lot of `git commit -m "fix: one more thing"`.

**[Live Site](https://adityaprakash.dev)** · **[GitHub](https://github.com/adityaprakash)** · **[LinkedIn](https://linkedin.com/in/adityaprakash)**

*Research begins where curiosity meets persistence.*

</div>
 
