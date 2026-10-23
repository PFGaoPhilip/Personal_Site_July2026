# Pengfei Gao — Personal Site

Academic portfolio built with PRISM and statically exported with Next.js.

Live site: https://pfgaophilip.github.io/Personal_Site_July2026/

## Content

- `content/config.toml`: identity, contact email, navigation, and update date.
- `content/bio.md` and `content/research.toml`: biography and detailed research experience.
- `content/projects.toml`: the broader course-project record.
- `content/publications.bib`: manuscript authorship, status, year, and descriptions.
- `content/cv.md`: detailed online CV.
- `public/cv/Pengfei_Gao_CV.pdf`: downloadable PDF CV.

The website retains project, award, and service details beyond the compact PDF CVs. The Michigan manuscript is first within Manuscripts in Preparation.

## Build

Use Node.js 22 or newer. Install with `npm ci`, then run `npm run build`. The static website is generated in `out/`. The configured base path is `/Personal_Site_July2026`.

For development, run `npm run dev` and open the configured base path on the local server. The site includes responsive navigation and a light/dark theme control.

## Deployment

Pushing to `main` runs the existing GitHub Actions build and GitHub Pages deployment workflow. The workflow builds the source and publishes `out/`.
