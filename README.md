# ABSO. WEBSITE — VERSION CONTROL & RELEASE PREPARATION

**Current release:** `v0.2_alpha`  
**Project:** ABSO. by ABSOLUTEARTT&reg;  
**Deployment target:** GitHub Pages  
**Framework:** Jekyll  

---

## Project Overview

- **Project name:** ABSO.
- **Parent brand:** ABSOLUTEARTT&reg;
- **Website purpose:** A curated destination for ABSO. games, with a focus on micro-games and individual game pages.
- **Current release:** `v0.2_alpha`
- **Project status:** Alpha
- **Deployment platform:** GitHub Pages
- **Static site framework:** Jekyll

---

## Design Principles

- **Minimal ABSO. visual identity:** Clean typography, minimalist elements, and structured use of whitespace.
- **Original artwork and assets:** Remain the source of truth.
- **Responsive, retina-quality presentation:** High fidelity on all displays.
- **Full-bleed top banner:** Spans edge-to-edge horizontally.
- **Centred main content:** Bounded within a maximum width wrapper with consistent responsive side margins.
- **Full-bleed global footer:** The footer stretches across the entire viewport.
- **Consistent footer:** The footer must remain visually identical across all pages.
- **Scoped CSS:** Page-specific CSS must not unintentionally affect global components.
- **Preserve original designs:** Game pages must preserve their approved designs and content accurately.
- **Multi-device QA:** Mobile and desktop layouts require visual verification for responsive edge cases.

---

## Technology Stack

- **Jekyll:** Static site generator.
- **Ruby & Bundler:** Dependency management and execution environment.
- **Theme and layout architecture:** Based on Oinam Jekyll remote theme.
- **CSS:** Plain CSS with variables and media queries.
- **Git and GitHub Pages:** Source control and deployment platform.

---

## Repository Structure

```
abso-absoluteartt/
├── .github/              # GitHub Actions or Workflows (if present)
├── _includes/            # Reusable HTML snippets (headers, footers, etc.)
│   ├── css/              # Core stylesheets including abso.css
│   ├── abso-header.html  # Global Header
│   └── abso-footer.html  # Global Footer
├── _layouts/             # Page layouts
├── assets/               # Static assets (images, icons, etc.)
│   └── images/abso/      # Shared ABSO images
│   └── images/mb-cow/    # MB-COW specific assets
├── design-files/         # Original design references and PSDs
├── _site/                # Auto-generated Jekyll build output (ignored in git)
├── index.md              # Homepage containing the ABSO games roster
├── mb-cow.md             # Mahabharata: Code of War game page
├── 404.md                # Custom 404 error page
├── Gemfile               # Ruby dependencies
├── _config.yml           # Jekyll global configuration
└── README.md             # Project documentation
```

---

## Local Development

To run the project locally, ensure you have Ruby and Bundler installed.

1. **Install dependencies:**
   ```bash
   bundle install
   ```
2. **Run local server:**
   ```bash
   bundle exec jekyll serve
   ```
3. **Preview:** Open `http://localhost:4000` in your browser.

---

## Deployment

The project is deployed automatically via **GitHub Pages**.

1. The `main` branch is the designated publishing source.
2. The custom domain `abso.absoluteartt.com` is configured via the `CNAME` file and `url` setting in `_config.yml`.
3. Before release, the site must build successfully locally and pass strict visual QA across multiple breakpoints (375px, 768px, 1440px).

---

## Design and Asset Governance

- Original design assets take precedence over approximations.
- Do not replace approved artwork without explicit authorisation.
- Do not flatten an entire page into a single screenshot. Use proper HTML/CSS implementation.
- Text, links, and controls should remain functional HTML elements wherever appropriate.
- Keep the global footer shared and consistent. Use `abso-footer.html`.
- Do not introduce page-specific changes that break the global layout (e.g. avoid global tag selectors).

---

## Versioning Policy

This project strictly follows semantic versioning with an explicit alpha-stage convention.

- **`v0.2_alpha`:** Current approved development baseline.
- **Patch increments:** Small fixes and refinements within the current development stage (e.g. `v0.2.1_alpha`).
- **Minor increments:** New backward-compatible pages or functionality (e.g. `v0.3_alpha`).
- **Major increments:** Significant architectural or product milestones (e.g. `v1.0`).
- **Beta and Stable:** Releases must be explicitly identified when reached.

Git tags are used to identify formal release milestones.

---

## Version History / Changelog

### **v0.2_alpha** (Current Release)
**Release Date:** October 9, 2026

- **Major additions:**
  - Added full implementation of the `mb-cow.md` (Mahabharata: Code of War) dedicated game page.
  - Implemented standalone, ultra-minimalist `404.md` error page with custom artwork.
  - Integrated a unified `abso-header.html` across the homepage and game pages.
- **Design and layout changes:**
  - Established a strict "Full Bleed Banner & Footer" global layout rule.
  - Updated homepage hero card to span edge-to-edge (100% viewport width) with 4 rounded corners.
  - Homepage logo sizing increased globally to match exact design scaling (`height: 32px`).
  - Anchor links updated to point to internal routes rather than external domains.
- **Fixes:**
  - Fixed mobile responsive clipping of the footer.
  - Fixed `.abso-walking-dots` sprite alignment to touch the footer perfectly.
  - Fixed CSS specificity bug causing stretched image proportions.
  - Removed arbitrary CSS cropping on hero images (`-3px` clipping bug fixed).
- **Deployment status:** Ready to be tagged and pushed to GitHub Pages `main` branch.

### **v0.1.2** 
- **Major additions:** Configure custom domain `abso.absoluteartt.com` via CNAME.

### **v0.1_alpha** 
- **Major additions:** Initial abso. website repository.

---

## Contribution and Change Control

1. **Inspect** the current repository state (`git status`, `git branch`, `git log`).
2. **Make changes** in the existing project structure.
3. **Test locally** (`bundle exec jekyll serve`).
4. **Run the Jekyll build** to ensure no compilation errors.
5. **Review visual changes** across all specified breakpoints.
6. **Update the changelog** in this README.
7. **Commit** approved changes with descriptive messages.
8. **Tag** formal releases.
9. **Push** to the configured remote.
10. **Verify** the deployed website on the live domain.

*Never commit credentials, API keys, private configuration, or unrelated personal files.*
