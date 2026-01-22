# Repository Guidelines

## Project Structure & Module Organization
- `index.html` contains the entire static site (HTML, CSS, and JavaScript in one file).
- No separate source, build, or test directories are present; assets are inlined (fonts are loaded from Google Fonts).

## Build, Test, and Development Commands
- This repository is a static page; no build step or package manager is configured.
- Local preview: open `index.html` in a browser or run a simple server, e.g. `python3 -m http.server` and visit `http://localhost:8000`.

## Coding Style & Naming Conventions
- HTML/CSS/JS live together; keep changes minimal and readable.
- Use 2-space indentation and preserve the existing formatting.
- Use kebab-case for CSS classes (e.g., `.program-item`, `.fade-up`).
- Keep CSS variables in `:root` and reuse them instead of hard-coded colors.

## Testing Guidelines
- No automated tests or test framework are configured.
- Manually verify changes by loading `index.html` in a browser and checking layout on mobile and desktop widths.

## Commit & Pull Request Guidelines
- Git history currently has a single commit (`init`), so no established convention is visible.
- Prefer short, imperative commit messages (e.g., "Add FAQ content").
- PRs should include a brief summary and, for visual changes, a screenshot or short description of the UI impact.

## Configuration & Content Tips
- External dependencies are limited to Google Fonts and a few external links; keep them minimal.
- If adding new sections, match existing typography and spacing for consistency.
