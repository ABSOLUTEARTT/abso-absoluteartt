# ABSO. WEBSITE — PRODUCTION RELEASE DOCUMENTATION

**Release Version:** `v3.1.1_alpha`  
**Release Date:** 2026-10-11  
**Project:** ABSO. by ABSOLUTEARTT&reg;  
**Production URL:** [https://games.absoluteartt.com/](https://games.absoluteartt.com/)  
**Repository:** [ABSOLUTEARTT/abso-absoluteartt](https://github.com/ABSOLUTEARTT/abso-absoluteartt)  
**Default Branch:** `main`  
**Deployment Target:** GitHub Pages  
**Framework:** Jekyll (Static Site Generator)  

---

## A. Project Overview

**ABSO.** is the dedicated indie micro-games label and experimental game division of **ABSOLUTEARTT&reg;**.

The ABSO. website serves as the official digital showcase and game catalogue for ABSO. titles, designed with an intentional "mobile-first, centered, ultra-clean" aesthetic inspired by Apple design restraint, tactile indie game personality, and Pixar-style character animation principles.

- **Brand:** ABSO. / ABSOLUTEARTT&reg;
- **Current Version:** `v3.1.1_alpha`
- **Release Status:** Approved Production Release
- **Production Host:** GitHub Pages with Custom Domain (`games.absoluteartt.com`)
- **Canonical Domain:** `https://games.absoluteartt.com/` (with 301 redirects from `abso.absoluteartt.com` and `play.absoluteartt.com`)
- **SSL / HTTPS:** Enforced via GitHub Pages SSL

---

## B. Technology and Architecture

- **Static Site Generator:** Jekyll 3.9+ / 4.x.
- **Theme Architecture:** Lightweight static implementation based on the Oinam Jekyll layout structure, customized with custom headers, footers, layouts, and responsive stylesheets.
- **Ruby & Bundler:** Managed via `Gemfile` with `github-pages` and `jekyll` plugin dependencies (`jekyll-optional-front-matter`, `jekyll-titles-from-headings`).
- **Styling:** Modular CSS architecture consisting of:
  - `_includes/css/abso.css`: Core design system, responsive container geometry, typography clamping, card layouts, banner placement, and footer styling.
  - `_includes/css/styles.css`: Base theme variables and theme reset rules.
- **JavaScript & Interactions:** Pure Vanilla JavaScript (ES5/ES6 compatible) with zero external animation frameworks, keeping the website ultra-fast, lightweight, and battery-friendly.
  - `_includes/abso-scroll-motion.html`: Scroll-reactive card displacement and settle inertia.
  - `_includes/abso-overscroll.html`: Apple-inspired rubber-band overscroll resistance and settle physics.
  - `_includes/abso-fluid-interactions.html`: Fluid press-states and smooth navigation transitions for catalog cards and directional controls.
  - `_includes/abso-header.html`: Mobile hamburger menu toggle, staggered pop entrance, alive character idle animations, and tactile selection feedback.
- **Hosting & Deployment:** GitHub Pages serving static assets directly from the `main` branch upon push.

---

## C. Project Structure

The project structure contains only real, verified files:

```
abso-absoluteartt/
├── .github/                      # GitHub repository configuration and workflows
├── _includes/                    # Reusable HTML snippets and modular components
│   ├── abso-header.html          # Global header with logo, hamburger menu, overlay, and animation logic
│   ├── abso-footer.html          # Global footer with brand mark, credits, links, and version label
│   ├── abso-fluid-interactions.html # Fluid press states and route transition coordinator
│   ├── abso-overscroll.html      # Rubber-band overscroll resistance physics engine
│   ├── abso-scroll-motion.html   # Scroll-reactive card movement and follow-through observer
│   ├── footer-ext.html           # Footer extensions and global script injections
│   ├── head-custom.html          # Custom head tags, fonts, meta tags, and favicons
│   └── css/                      # Stylesheets
│       ├── abso.css              # Main ABSO design system stylesheet
│       └── styles.css            # Oinam base theme stylesheet
├── _layouts/                     # Jekyll layouts
│   ├── default.html              # Primary site layout
│   └── abso-legal.html           # Dedicated legal page layout (FAQs, Privacy, Terms)
├── assets/                       # Static media assets
│   └── images/
│       ├── abso/                 # ABSO brand artwork, game banners, icons, WebP assets
│       └── mb-cow/               # Mahabharata: Code of War game screenshots and artwork (WebP)
├── _site/                        # Generated static HTML output (ignored in git)
├── .gitignore                    # Git exclusion rules
├── CNAME                         # Custom domain pointer (games.absoluteartt.com)
├── Gemfile                       # Ruby dependencies
├── Gemfile.lock                  # Pinned Ruby gem versions
├── README.md                     # Comprehensive project documentation
├── _config.yml                   # Jekyll site configuration and version definition
├── 404.md                        # Custom 404 error page
├── index.md                      # ABSO Homepage (Hero, games roster, The Dot, Contact)
├── games.md                      # Games catalog page
├── the-dot.md                    # The Dot dedicated brand and character page
├── about.md                      # About ABSO. studio page
├── contact.md                    # Contact page
├── mb-cow.md                     # Mahabharata: Code of War game showcase
├── samosa-catcher.md             # Samosa Catcher game showcase
├── run-little-one.md             # Run, Little One game showcase
├── twosome.md                    # Twosome game showcase
├── duet.md                       # Duet game showcase
├── faqs.md                       # Frequently Asked Questions
├── privacy.md                    # Privacy Policy
└── terms.md                      # Terms of Service
```

---

## D. Pages and Navigation

### 1. Main Pages
- **Homepage (`/`):** Hero showcase (Mahabharata: Code of War), catalogue games roster (Samosa Catcher, Run, Little One, Twosome, Duet), "small games. strange ideas." manifesto banner, The Dot spotlight banner, and Contact section.
- **Games (`/games/`):** Full playable game catalogue roster with dedicated game cards.
- **The Dot (`/the-dot/`):** Story, gallery, and lore of the studio mascot "The Dot" across multiple lives and character poses.
- **About (`/about/`):** Studio philosophy, background, and vision of ABSO. / ABSOLUTEARTT&reg;.
- **Contact (`/contact/`):** Direct collaboration and studio contact channels.

### 2. Game Showcase Pages
- **Mahabharata: Code of War (`/mb-cow/`):** Epic mythological action-strategy game page with base artwork, in-game screens, and lore.
- **Samosa Catcher (`/samosa-catcher/`):** Quirky arcade catcher game page with full screenshots, info banners, and download links.
- **Run, Little One (`/run-little-one/`):** Atmospheric runner game page with typographic balance, gallery, and specs.
- **Twosome (`/twosome/`):** Minimalist co-op puzzle game page.
- **Duet (`/duet/`):** Synchronized reflex game page.

### 3. Legal and Utility Pages
- **FAQs (`/faqs`):** Frequently asked questions.
- **Privacy Policy (`/privacy`):** User privacy statement.
- **Terms of Service (`/terms`):** Terms of website use.
- **404 Not Found (`/404`):** Custom illustrated error page.

### 4. Global Navigation
- **Header:** Features the official ABSO. wordmark with dot and an interactive animated hamburger toggle.
- **Hamburger Overlay:** Full mobile-responsive modal overlay featuring 4 illustrated 3D character badges (`home`, `games`, `the dot`, `contact`).
- **Directional Navigation:** Previous, Home, and Next navigation controls present on individual game pages.

---

## E. Design System

- **Brand Typography:** Modern clean sans-serif stack (`system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif`) with explicit font weight hierarchy (Bold 700 / Black 900 for headings, Medium 500 for captions, Regular 400 for copy).
- **Responsive Clamping:** Dynamic typographic scaling utilizing CSS `clamp()` to guarantee identical visual hierarchy across 320px mobile displays through 4K desktop screens without text overflow.
- **Color Palette:**
  - Background: Pristine Studio White (`#ffffff`)
  - Primary Text: Deep Charcoal (`#1a1a1a`)
  - Secondary Text / Subtitles: Refined Slate (`#666666`, `#777777`)
  - Studio Accent: ABSO Dot Red (`#e62429` / `#ff2a2a`)
  - Dark Surface / Footer: Void Black (`#111012`) with white secondary metadata (`rgba(255, 255, 255, 0.72)`)
- **Card Geometry:**
  - Hero Card: `border-radius: 36px` (mobile) to `42px` (desktop), aspect ratio `1 / 1.50`.
  - Game Catalog Cards: `border-radius: 28px` to `32px`.
  - Content Boundaries: Centered container capped at `660px` with dynamic gutter padding (`min(calc(100% - 24px), 660px)` on mobile, `32px` on tablets).
- **Asset Optimization:** Next-generation WebP formats across all major graphic artboards, reducing asset payload from over 35MB to under 2.5MB total while preserving 2x Retina clarity.

---

## F. Responsive Behaviour

- **Mobile View (Viewport < 521px):**
  - Layout is centered with comfortable 12px horizontal edge margins.
  - Hamburger menu spans `width: calc(100% - 40px)` with 20px edge insets.
  - Banner text copy auto-scales smoothly using `clamp()` formulas, keeping text strictly inside illustrated badge pills (such as The Dot blue pill banner).
  - Footer rests flush at the viewport bottom with `20px` snug padding.
- **Desktop View (Viewport >= 521px):**
  - Content maintains a mobile-first, centered column format capped at `660px` maximum width.
  - Hamburger menu renders as a dropdown pill (`width: 240px`) positioned beneath the header toggle.
  - Directional navigation items and cards maintain generous breathing room.
- **Tap Highlight Elimination:**
  - Site-wide elimination of all default browser translucent blue focus/tap highlight bounding boxes (`-webkit-tap-highlight-color: transparent !important; outline: none !important`).

---

## G. Animation System

The animation system adheres to the creative direction: **Apple-Style Restraint × Pixar Character Principles × Indie Game Personality**.

### 1. Scroll-Reactive Card Movement (`_includes/abso-scroll-motion.html`)
- Cards respond naturally to visitor scroll with tiny vertical displacements (`4px–8px`) and settle into place with gentle follow-through inertia (`cubic-bezier(0.16, 1, 0.3, 1)`).
- Multiple cards entering simultaneously cascade with a micro-stagger (`40ms–80ms`).

### 2. Apple-Style Rubber-Band Overscroll (`_includes/abso-overscroll.html`)
- When dragging or swiping past document scroll boundaries, the container responds with soft physical spring resistance (max 6px–12px displacement).
- Backed by zero-layout-cost `box-shadow: 0 100px 0 0 #111012` on the footer to prevent white background exposure during bottom rubber-banding.
- Smoothly snaps back without sudden jumps or layout shifts.

### 3. Hamburger Menu Animation Suite (`_includes/abso-header.html`)
- **Staggered Pop Entrance:** The 4 character badges (`Home`, `Games`, `The Dot`, `Contact`) cascade in with spring inertia (`translateY(22px) scale(0.88)` -> `translateY(0) scale(1)`) with staggered delays (60ms, 120ms, 180ms, 240ms).
- **Quietly Alive Idle Floating:** While the menu rests open, each character badge has subtle, gentle breathing/floating animations (displacements 2.5px–3.5px, periods 3.1s–4.0s):
  - *Home:* Gentle cottage breathing bob (`absoHomeBob`, 3.6s)
  - *Games:* Playful controller float with tiny 0.8° tilt (`absoGamesFloat`, 3.1s)
  - *The Dot:* Relaxed lounging float (`absoDotLounge`, 4.0s)
  - *Contact:* Friendly mail carrier hover (`absoContactBob`, 3.4s)
- **Tactile Tap / Selection Response:** Pressing an item squashes it (`scale(0.92)`), releasing triggers an expressive spring pulse (`absoMenuSelectedPulse`), and navigation executes smoothly after a 160ms visual feedback window.

### 4. Fluid Navigation & Card Press (`_includes/abso-fluid-interactions.html`)
- Tapping catalog cards or directional controls (Home, Previous, Next) compresses them with a tactile game-feel before executing smooth page navigation.

### 5. Reduced-Motion Guardrail
- Every animation and transition immediately disables when `prefers-reduced-motion: reduce` is detected, instantly snapping elements to resting positions with zero movement.

---

## H. Development and Build

### Prerequisites
- Ruby 3.1+ (or 2.7+)
- Bundler (`gem install bundler`)

### Local Setup & Preview
```bash
# 1. Install dependencies
bundle install

# 2. Build the static site
bundle exec jekyll build

# 3. Serve locally on all interfaces
bundle exec jekyll serve --host 0.0.0.0 --port 4000
```

### Stopping the Local Server
In terminal / command prompt: Press `Ctrl + C` or terminate the running background process.

---

## I. Quality Assurance (QA)

### 1. Automated Verification
- Headless browser verification using Chromium/Edge via Chrome DevTools Protocol (CDP).
- Full page layout geometry inspection across viewports:
  - Mobile: `360x640`, `375x667`, `390x844`, `430x932`
  - Desktop: `1440x900`
- Zero-error Jekyll build validation.

### 2. Manual & Device Verification
- Physical mobile phone testing over local network (`http://192.168.1.10:4000/`) and tunnel.
- Verification of link destinations, touch highlights, typography wrapping, and overscroll elasticity.

---

## J. Security & Production Readiness

- **No Secrets / Credentials:** The repository is strictly static HTML/CSS/JS and contains no API keys, secrets, or private environment files.
- **Localhost Elimination:** All production links use relative URLs (`{{ site.baseurl }}`) or verified absolute canonical domains.
- **Dependency Isolation:** Only approved GitHub Pages gems are loaded in `Gemfile`.
- **Target Exclusions:** Heavy design files (`design-files/`, `*.psd`), build caches (`.jekyll-cache/`, `.sass-cache/`), and test scratch scripts (`scratch/`) are fully excluded via `.gitignore` and `_config.yml`.

---

## K. Git and Release Workflow

- **Branch Strategy:** `main` serves as the single source of truth and production deployment branch.
- **Commit Convention:** Descriptive commit messages documenting release version and major modifications.
- **Tagging:** Annotated Git tags with semver naming: `v0.3_alpha`, `v0.3.1.1`, `v3.1.1_alpha`.
- **Deployment:** Automatically triggers GitHub Pages build upon pushing to `main`.

---

## L. Detailed Release Changelogs

### Release v3.1.1_alpha — Samosa Catcher Banner Replacement & Twosome Banner Edge Refinement (2026-10-11)

- **Samosa Catcher Banner:** Replaced artwork on homepage (`/`) and games catalogue (`/games/`) with the official claymation banner asset (`samosa-catcher.webp`, 98.2 KB), featuring character holding samosa tray with centered "SAMOSA CATCHER" 3D title.
- **Twosome Main Banner Edge Crop:** Fixed thin line artifact on the right edge of Twosome showcase banner (`https://games.absoluteartt.com/twosome/`). Cropped 4px stray solid-blue pixel column from `twosome-header.png` (1316x1052) and converted to WebP (`twosome-header.webp`, 61.5 KB, down from 2.26 MB PNG).
- **Website Display Version:** Updated version string to `v3.1.1_alpha` in `_config.yml` and footer across all pages.

### Release v0.3.1.1 — WebP Performance Optimization & Asset Payload Reduction (2026-10-11)

- **Homepage Browser Title:** Updated homepage title to `abso. — small games. strange ideas.` to match canonical brand identity.
- **Site Version:** Bumped version to `v0.3.1.1` in `_config.yml` and footer (`abso-footer.html`).
- **WebP Asset Optimization & Payload Reduction:**
  - Samosa Catcher: Replaced 1.67 MB PNG (`samosa-catcher-combined.png`) with 115.3 KB WebP (`samosa-catcher.webp`) on Homepage and `/games/` showcase.
  - About Banner: Converted 928 KB `about-banner.png` to 73.5 KB `about-banner.webp` (92.1% reduction).
  - Navigation Menu Icons: Converted 6 oversized PNG icons (1.66 MB total) to right-sized 2× retina WebP icons (`menu-open.webp`, `menu-close.webp`, `menu-home.webp`, `menu-games.webp`, `menu-the-dot.webp`, `menu-contact-icon.webp`) totaling 43.3 KB (97.4% reduction).
  - Game Showcase Controls: Converted `home-icon.png` (133 KB) to `home-icon.webp` (4.8 KB), `icon-left.png` (13 KB) to `icon-left.webp` (4.5 KB), and `icon-right.png` (13 KB) to `icon-right.webp` (4.5 KB) across all game showcase pages.
- **Delivery Strategy:**
  - Preserved eager loading (`fetchpriority="high" decoding="async"`) on the primary above-the-fold hero banner (`mahabharata-code-of-war.webp`).
  - Added explicit `loading="lazy"` and `decoding="async"` across all below-the-fold cards, showcase screenshots, and off-screen menu assets.
- **Measured Results:**
  - Total homepage live asset payload reduced from 4.49 MB to 0.56 MB (87.5% reduction).
  - Cumulative transfer duration dropped from >170s to ~18s.
  - Zero missing assets (verified 183 image paths across all 14 rendered pages).
  - All visual fidelity, mobile-first responsiveness, rubber-band inertia, and menu micro-animations preserved intact.

### Release v0.3_alpha — Initial Production Release (2026-10-11)

### 1. Typography and Visual Consistency
- Fixed text wrapping and line breaks across all game showcase pages.
- Corrected orphaned single-word line ("of") on Run, Little One header.
- Scaled Samosa Catcher header text to fit comfortably within artboard proportions without excessive zoom.
- Centered The Dot banner copy inside the navy blue pill graphic (`top: 48%; transform: translateY(-50%)`) with proportional line heights and font clamping.

### 2. Spacing, Alignment, Formatting, and Aesthetics
- Tightened footer negative space from excessive 100px+ void down to a balanced, grounded 20px mobile / 24px desktop resting padding.
- Replaced spacer layout elements (`.abso-footer-extend`) with zero-layout-cost `box-shadow` to ensure clean resting scroll height.
- Eliminated browser default translucent blue tap highlight bounding boxes across all interactive buttons, links, cards, and menu items.

### 3. Responsive Refinements Across Mobile, Tablet, and Desktop
- Tuned hero card aspect ratio to `1 / 1.50` on desktop with `border-radius: 42px`.
- Fixed mobile banner boundaries and gutters across 360px, 375px, 390px, and 430px screens.
- Verified Mahabharata: Code of War, Samosa Catcher, Run, Little One, Twosome, and Duet layouts.

### 4. Mobile/Desktop View-Switch Verification
- Verified centered mobile-first container wrapper (`.abso-container`) at 660px maximum width.
- Preserved responsive media queries and full-bleed header/footer rules.

### 5. Link and Interaction Fixes
- Added missing routes for `/games/`, `/the-dot/`, `/about/`, and `/contact/`.
- Verified internal navigation continuity between game pages via Previous, Home, and Next controls.

### 6. Subtle Micro-Animations
- Added staggered pop entrance cascade to hamburger menu badges (Home, Games, The Dot, Contact).
- Implemented gentle, "quietly alive" character floating/breathing micro-animations for menu badges.
- Implemented tactile tap feedback squash and spring pulse on menu item selection.

### 7. Scroll-Reactive Card Movement
- Integrated `abso-scroll-motion.html` providing subtle vertical displacement and settling follow-through on scroll.
- Staggered card entrance rhythm with natural ease-out physics.

### 8. Overscroll and Rubber-Band Behaviour
- Integrated `abso-overscroll.html` with Apple-inspired elastic resistance when pulling past viewport boundaries.
- Backed bottom overscroll with `box-shadow: 0 100px 0 0 #111012` to prevent white voids.

### 9. Footer Version Update
- Updated site version configuration in `_config.yml` to `v0.3_alpha`.
- Verified footer version label across all rendered HTML pages displays `v0.3_alpha`.

### 10. Security and Production-Readiness Checks
- Added `scratch/` to `.gitignore`.
- Verified absence of hardcoded localhost URLs and API keys.
- Completed clean Jekyll production build (`0 errors, 0 warnings`).

### 11. Documentation and Version Control
- Authored comprehensive release documentation in `README.md`.
- Prepared Git release commit and annotated tag `v0.3_alpha`.

### 12. GitHub Pages Deployment
- Pushed release commit and `v0.3_alpha` tag to `origin/main`.
- Verified GitHub Pages live deployment at `https://games.absoluteartt.com/`.

### 13. Canonical Domain Migration
- Primary domain migrated to `https://games.absoluteartt.com/`.
- Repository `CNAME` updated to `games.absoluteartt.com`.
- Site base URL updated in `_config.yml` and `404.md`.
- Cloudflare DNS configured with CNAME `games.absoluteartt.com` pointing to `absoluteartt.github.io`.
- Cloudflare Dynamic Redirect Rules configured:
  - `abso.absoluteartt.com/*` HTTP 301 redirects to `https://games.absoluteartt.com/$1` (preserving path and query string).
  - `play.absoluteartt.com/*` updated to HTTP 301 direct redirect to `https://games.absoluteartt.com/$1` (preserving path and query string).

## M. Known Limitations

- **Browser Rubber-Band Variations:** Native overscroll bouncing in mobile Safari (iOS) operates at the browser compositor level and will naturally blend with the custom rubber-band script.
- **Pointer Accuracy on Touch:** Hover animations are strictly conditioned on `@media (hover: hover) and (pointer: fine)` to prevent stuck hover states on touchscreens.
- **Static Hosting Architecture:** Contact forms rely on standard `mailto:` links rather than server-side endpoints, consistent with GitHub Pages static hosting.

---

## N. Rollback Information

If a rollback is ever required:
- **Previous Known-Good Commit:** `9be82ae` (*Release abso. website v0.3_alpha*)
- **Previous Tag:** `v0.3_alpha`
- **Revert Command:**
  ```bash
  git revert <release-commit-hash>
  git push origin main
  ```
