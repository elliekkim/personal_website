# Project log

## 2025-11-08

- Summary: Customized Jekyll theme with minimalist layout, hero driven by Markdown/front matter, and new Films page content with embedded Vimeo reels to prep site for GitHub Pages publish.
- Files: `_layouts/default.html`, `_layouts/home.html`, `assets/main.scss`, `index.markdown`, `_config.yml`, `cv.md`, `films.md`, `research-projects.md`.
- Decisions: Keep hero copy in Markdown for easy editing; reuse `.content-card` styling and new `.video-embed` helper for consistent film sections.
- TODO: Install Bundler 2.6.2 then run `bundle exec jekyll serve`; swap placeholder photo and Vimeo links with final assets.
## 2025-11-08 (later)

- Summary: Switched hero heading to "Hi, I'm Ellie!", moved hero copy into Markdown/front matter, expanded Films page with bio and three Vimeo embeds, and added responsive video styling.
- Files: `_layouts/home.html`, `index.markdown`, `films.md`, `assets/main.scss`.
- Decisions: Drive hero text via `hero_title` front matter; standardize video layout with `.video-embed` for all reels.
- Next Actions: Install Bundler 2.6.2 and preview; replace placeholder portrait and Vimeo URLs with final assets.
