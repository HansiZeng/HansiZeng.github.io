# CLAUDE.md — HansiZeng.github.io

## About the Owner
- **Name**: Hansi Zeng (曾翰偲)
- **Role**: Final-year CS PhD student at UMass Amherst, advised by Hamed Zamani
- **Research**: Information Retrieval, Large Language Models, Reinforcement Learning
- **Goal**: Seeking research scientist roles at frontier labs (starting Summer/Fall 2026)
- **Email**: hzeng@umass.edu / hanszenghappy@gmail.com
- **Google Scholar**: https://scholar.google.com/citations?user=a7O1D6oAAAAJ&hl=en
- **GitHub**: https://github.com/HansiZeng

## Education
- PhD in Computer Science, UMass Amherst (2021–present)
- MS in Computer Science, University of Utah (2019–2021)
- MS in Mathematics, University of Wisconsin–Madison (2017–2019)
- BS in Mathematics, Nankai University (2014–2018)

## Industry Experience
- Snapchat — Part-time Research Intern (Sep 2025–present)
- Amazon — Applied Scientist Intern (May–Aug 2025)
- Google DeepMind — Student Research Intern (May 2024–Mar 2025)
- Amazon — Applied Scientist Intern (May–Dec 2023)
- Lowe's — Data Science Graduate Intern (May–Aug 2022)

## Project Purpose
This is Hansi's academic personal website, hosted via GitHub Pages. It serves as a professional homepage for job applications and academic visibility.

## Project Structure
- `index.html` — single-page site (HTML + inline CSS/JS)
- `files/hzeng_CV.pdf` — CV PDF (source at `/Users/hzeng/resume/hzeng_CV/cv_update.tex`)
- `images/` — headshot and company logos
- CV source is managed in `/Users/hzeng/resume/` with Overleaf as remote

## Key Conventions
- The site is a single `index.html` file with inline styles — no build system
- CV PDF filename must stay `files/hzeng_CV.pdf` (linked from the page)
- Publications use `<li class="pub" id="pub-{slug}-{year}">` format
- Experience uses the `exp-item` / `exp-logo` card layout with company logos
- The site supports light/dark mode toggle
- Links use `target="_blank" rel="noopener"`

## Workflow: Updating the Site
1. Edit `index.html` directly
2. If CV changed: compile tex at `/Users/hzeng/resume/hzeng_CV/cv_update.tex`, copy PDF to `files/hzeng_CV.pdf`, push resume repo to overleaf (`git push origin master`)
3. Commit and push this repo to deploy via GitHub Pages
