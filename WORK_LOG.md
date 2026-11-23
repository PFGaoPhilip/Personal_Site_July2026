# Work Log

## 2026-10-23 — Research, manuscripts, and CV refresh

- Updated the biography, contact email, research experience, online CV, and news from the approved October 2026 CV revisions.
- Added graduation-design work with Prof. L. Jay Guo and the expected December 2026 Michigan arrival. Updated the Linghu appointment to July-October 2026.
- Retained the broader website record, including all three course projects and existing additional awards and service details.
- Corrected the laser-droplet manuscript title and seven-author order, and listed it under review at Advanced Functional Materials.
- Added the Michigan and confined-adhesion manuscripts. Kept the Michigan entry first among the four manuscripts in preparation, all dated 2026 with expected submission in 2027.
- Added a downloadable PDF CV named Pengfei_Gao_CV.pdf.
- Rendered explicit manuscript-status sections and notes, and retained searchable/exportable BibTeX entries.
- Improved manuscript contrast in dark mode and kept date badges on one line on mobile.
- Production build, lint, and TypeScript validation passed. Browser checks passed across desktop/mobile layouts, light/dark themes, navigation, manuscript search, and the PDF download, with no browser page errors or failed asset requests.
- Tested the static export from a separate delivery folder with external asset requests blocked. The existing GitHub Pages workflow publishes the validated source when main is updated.

## 2026-10-23 — Public CV download

- Published the current CV at the neutral path `cv/Pengfei_Gao_CV.pdf`.
- Labeled the public link `Download CV (PDF)`.
- Updated the biography and repository documentation to describe the public download.

## 2026-11-24 — Public CV replaced with the current application CV

- Replaced `public/cv/Pengfei_Gao_CV.pdf` with the generic application CV of 2026-11-23 (SHA-256 prefix a3280fd6bc4c9bb6, 2 pages). It describes the droplet-transfer work as setting the process-parameter window for a successful release that leaves enough water on the stamp for the next cycle. It also carries the transcript GPA 3.89/4.3 and the current research and manuscript entries.
- The previous site PDF (2026-11-17) is kept in `C:\PhD2027Fall\Intermediates\CV_ReleaseWindow_20261123\before\website\`.
- `npm run build` passed; the exported `out/cv/Pengfei_Gao_CV.pdf` is byte-identical to the application CV, and the CV page still links to `/Personal_Site_July2026/cv/Pengfei_Gao_CV.pdf`.
