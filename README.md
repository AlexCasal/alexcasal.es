# Alex Casal Portfolio

[![Built with Astro](https://img.shields.io/badge/Astro-6.x-ff5d01?style=flat-square&logo=astro&logoColor=white)](https://astro.build/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.x-38bdf8?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Package manager: pnpm](https://img.shields.io/badge/package_manager-pnpm-f69220?style=flat-square&logo=pnpm&logoColor=white)](https://pnpm.io/)

Personal portfolio for [alexcasal.es](https://alexcasal.es): a focused developer portfolio, project archive, and small creative lab built with Astro.

The site presents my profile as a junior full-stack software developer based in Berlin, with selected projects, experience, contact links, and experiments in one fast static website.

## What This Site Does

- Introduces my developer profile clearly for recruiters and hiring teams.
- Highlights selected projects with problem, build details, stack, learnings, and links.
- Shows my experience, background, tech stack, and availability.
- Keeps a small lab area for ideas and experiments that grow over time.
- Stays lightweight, static, and easy to maintain without a CMS.

## Tech Stack

| Area | Tools |
| --- | --- |
| Framework | Astro |
| Styling | Tailwind CSS |
| Language | JavaScript, TypeScript-friendly Astro components |
| Package manager | pnpm |
| Deployment | Static build ready for Vercel or similar platforms |

## Requirements

- Node.js `>=22.12.0`
- pnpm `11.7.0`

If pnpm is not installed, enable it through Corepack:

```bash
corepack enable
```

## Getting Started

Install dependencies:

```bash
pnpm install
```

Start the development server:

```bash
pnpm dev
```

Build the production site:

```bash
pnpm build
```

Preview the production build locally:

```bash
pnpm preview
```

## Project Structure

```text
.
|-- public/
|   |-- experiences/        # Images used by experience pages
|   |-- favicon.ico
|   `-- profile_01.jpg
|-- src/
|   |-- components/         # Reusable Astro components
|   |-- layouts/            # Shared page layout
|   |-- pages/              # Site routes
|   `-- styles/             # Global Tailwind entry
|-- astro.config.mjs
|-- package.json
|-- pnpm-lock.yaml
|-- pnpm-workspace.yaml
`-- README.md
```

## Main Routes

| Route | Purpose |
| --- | --- |
| `/` | Homepage, hero, open-to-work section, featured content |
| `/about` | Professional summary, background, stack, Berlin context |
| `/projects` | Selected finished projects and case-study style details |
| `/lab` | Experiments, notes, and ideas in progress |
| `/experiences` | Experience posts and community involvement |
| `/contact` | Email, LinkedIn, GitHub, CV, and hiring details |

## Content Notes

Most content currently lives directly inside Astro pages and component props. That keeps the project simple and quick to update while the portfolio evolves.

When updating content, the most relevant files are:

- `src/pages/index.astro`
- `src/pages/about.astro`
- `src/pages/projects.astro`
- `src/pages/experiences.astro`
- `src/pages/contact.astro`
- `src/components/Navigation.astro`
- `src/components/Footer.astro`

## Useful Commands

```bash
pnpm dev       # Start local development
pnpm build     # Build the static site
pnpm preview   # Preview the production build
pnpm astro     # Run Astro CLI commands
```

## Status

Active and evolving. The goal is to keep the site personal and creative while making it clear, useful, and easy to scan for recruiters and hiring teams.
