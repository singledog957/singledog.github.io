# Yuxin Xie — Academic Homepage

Based on HugoBlox Academic CV, with a customized academic layout and bilingual content. English is the default; Chinese is available at `/zh/`.

## Content
- `data/portfolio_en.json` and `data/portfolio_zh.json`: localized profile, publications, research, engineering projects, demos, and awards.
- `paper_url`: set to an actual paper URL when available. Empty URLs render as disabled gray labels. `paper_state` distinguishes `review`, `forthcoming`, and `no_paper`.
- No separately maintained research detail pages.
- `static/images/personal_page.jpg`: original photograph, displayed with a CSS crop. The source image is unchanged.

## Local preview
Hugo Extended 0.162.0 and Go are required. `pnpm dev` starts the preview; `pnpm build` generates `dist/`. The customized layouts use plain CSS and do not need Tailwind compilation.

## GitHub Pages
Target: https://github.com/singledog957/singledog957.github.io
Expected URL: https://singledog957.github.io/

Under repository Settings → Pages, select GitHub Actions. The workflow is restricted to the exact target repository and publishes pushes to `main`. No Sites service is used by this version.

Publication status and results follow the user-provided materials. Full coauthor lists, unpublished PDFs, DOIs, and missing paper URLs have not been invented. CNKD’s descriptive title is not a verified final publication title.

Upstream MIT license and HugoBlox attribution are preserved.
