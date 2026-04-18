# artcitypta.github.io

Art City Elementary PTA website.

## Stack recommendation and tradeoffs

This site uses **plain HTML + Tailwind CSS (CDN)** for a GitHub Pages-friendly setup.

- **Why this is recommended here:**
  - Fastest path to launch on GitHub Pages (no build pipeline required)
  - Very easy for novice contributors to edit content directly in HTML
  - Tailwind provides modern, professional styling without complex tooling
- **Tradeoff:**
  - Repeated layout markup across pages instead of shared components from frameworks like Astro
  - If content grows significantly, moving to Astro + Tailwind would improve maintainability

## Hosting on GitHub Pages

Because this is a static site, no GitHub Actions workflow is required. Enable GitHub Pages to serve from the repository root (or default branch setting in Pages).

## Future PTA website recommendations

- Add a simple form workflow (Google Form embed or Formspree) for volunteer signups.
- Add a “Quick Links” section (school calendar, lunch menu, district alerts).
- Add downloadable meeting minutes and budget snapshots for transparency.
- Add an accessibility review pass (color contrast, keyboard navigation, alt text checks).
