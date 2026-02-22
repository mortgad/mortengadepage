# Project: mortengadepage

Personal website for **Morten Ravnsgård Gade**.

## Tech Stack
- **Framework**: Astro (v5) with static output
- **Styling**: Tailwind CSS v4
- **Hosting**: Cloudflare Pages (not set up yet)
- **Repo**: github.com/mortgad/mortengadepage (private SSH alias: `github-privat`)
- **Git identity**: Morten Ravnsgård Gade <mortengade7400@hotmail.com>

## Branching
- `main` = production (auto-deploys to Cloudflare Pages)
- Feature branches / PRs get preview deploys

## Site Type
Data scientist personal site: portfolio, blog, resume/CV.

## About Morten
- Twenty-something data scientist from Aarhus, lives with girlfriend Karoline
- Interests: IT, pop philosophy, games, short books, movies, padel, running, food
- Mom: Irene ("the world's greatest"), nieces: Kaia and Asta
- **Work**: Data Scientist at Knowit Experience Aarhus (current); previously student worker at Knowit, Det Kgl. Bibliotek, Jysk; intern at Matchware (London)
- **Education**: MSc Business Intelligence, BSc Cognitive Science, BSc Business Administration — all Aarhus University
- **Skills**: Python, SQL, Google Cloud, Microsoft Azure, R
- **Tone**: Clean, minimal, humorous, dark mode

## Site Structure
- `/` — Single-page: hero, about, work, education, skills, contact
- `/blog` — Blog index with placeholder posts (content TBD)
- `/404` — Custom 404 page
- `src/layouts/Base.astro` — Shared layout with nav + footer
- `src/styles/global.css` — Dark theme via Tailwind v4 @theme

## Commands
- `npm run dev` — start dev server
- `npm run build` — production build
- `npm run preview` — preview production build locally
