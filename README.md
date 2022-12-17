## Description

[![CI](https://github.com/GV79/portfolio-astro/actions/workflows/main.yml/badge.svg)](https://github.com/GV79/portfolio-astro/actions/workflows/main.yml)

This is the third iteration of my portfolio website now built using [Astro](https://astro.build/). The legacy Next.js version of my portfolio website is hosted in the following GitHub Repo: https://github.com/GV79/portfolio-new. Originally this repo was created just to play around with this new technology but there are also many benefits to this HTML-first approach such as better performance for end-users (smaller bundle size + less JS for the browser to parse & process). Any components with more interactivity were built with [Svelte](https://svelte.dev/);

## Getting Started

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run lint`         | Lint project with ESLint                         |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## In progress

1. 100% feature parity with existing Next.js portfolio site

## Todos

1. Integrate Headless CMS to easily add new projects (i.e. Contentful, Prismic, DatoCMS...)
2. Add GitHub actions (lint, type check, build, and run e2e tests)
3. Add Playwright e2e tests https://docs.astro.build/en/guides/testing/
4. Light/Dark Mode toggle + defaults via `prefers-color-scheme` setting
5. Add old chat, socsreynolds, mrflatbeds, and form builder projects + fix image sizes
6. Disabled buttons on featured projects page for mobile navs
7. Filter (fixed icon for filtering projects by technology)
8. Add simple animations/transitions?
9. Small date badges beside projects (top right of title)
10. Progressive web app for offline availability?
