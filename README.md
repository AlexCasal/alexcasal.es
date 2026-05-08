# Alex Casal Lab

Personal website, portfolio, and experimental lab for me. The site is built with Astro and is designed as a curated personal internet space: part portfolio, part writing surface, part place for experiments.

## Overview

This project contains the source code for `alexcasal.es`. It presents selected projects, personal background, lab experiments, experience publications, and contact information in one cohesive site.

The site is intentionally small and static. Most content lives directly in Astro pages and component props, which makes it easy to edit without introducing a CMS or extra data layer too early.

## Tech Stack

- [Astro](https://astro.build/)
- [Tailwind CSS](https://tailwindcss.com/)
- TypeScript-friendly Astro components
- Static assets served from `public/`

## Requirements

- Node.js `>=22.12.0`
- npm

## Getting Started

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build the production site:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Project Structure

```text
.
├── public/
│   ├── experiences/        # Images used by experience publications
│   ├── favicon.ico
│   └── profile_01.jpg
├── src/
│   ├── components/         # Reusable Astro components
│   ├── layouts/            # Shared page layout
│   ├── pages/              # Site routes
│   └── styles/             # Global Tailwind entry
├── astro.config.mjs
├── package.json
└── README.md
```

## Main Pages

- `src/pages/index.astro` - homepage.
- `src/pages/about.astro` - personal background and context.
- `src/pages/projects.astro` - selected projects.
- `src/pages/lab.astro` - experiments and unfinished ideas.
- `src/pages/experiences.astro` - publication-style experience posts.
- `src/pages/contact.astro` - contact page.


## Status

This site is active and evolving. Content, layout, and sections may change as the portfolio and lab grow.
