# Senior Advisors Website

![Status](https://img.shields.io/badge/status-production--ready-brightgreen)
![Version](https://img.shields.io/badge/version-4.2-blue)
![Pages](https://img.shields.io/badge/pages-25-orange)
![Languages](https://img.shields.io/badge/languages-2-green)

Professional bilingual consulting company website for Senior Advisors - a leading M&A advisory and strategic consulting firm.

## Live Website

**https://s-advisors.com**

- **Russian version**: https://s-advisors.com (root, no suffix needed)
- **English version**: https://s-advisors.com/index-en.html

Use the language switcher (RU/EN) to toggle between languages on any page.

## Project Overview

Complete, multi-page, **bilingual website** (Russian & English) showcasing Senior Advisors' consulting services, portfolio, team, and client relationships. Features modern design, responsive layouts, professional presentation, and seamless language switching.

### Key Statistics
- **25 HTML Pages** — 10 core pages × 2 languages + privacy (RU/EN) + 404 + index-ru.html redirect
- **2 Languages** — Full Russian and English versions with language switcher
- **69+ Clients** — Across 10 industry categories
- **62+ Projects** — Detailed case studies with tombstone-style presentation
- **9 Team Members** — Partners and consultants with detailed profiles
- **6 Service Areas** — Market research, strategy, investment, fundraising, acquisitions + Стратсовет

## Quick Start

### View Live Website
Visit **https://s-advisors.com**

### Local Development
```bash
cd "path/to/SA website"
python -m http.server 8000
# Open http://localhost:8000
```

## URL Structure

All pages use clean URLs via subfolder `index.html` architecture. Old `.html` URLs auto-redirect.

| Page | Clean URL |
|------|-----------|
| Homepage (RU) | `/` (root) |
| Homepage (EN) | `/index-en.html` |
| Portfolio | `/portfolio` |
| Clients | `/clients` |
| Team | `/team` |
| Market Research | `/service-market-research` |
| Strategy | `/service-strategy` |
| Investment | `/service-investment` |
| Fundraising | `/service-fundraising` |
| Acquisition | `/service-acquisition` |
| Стратсовет | `/stratsovet` |
| + EN versions | `/portfolio-en`, `/team-en`, etc. |
| Privacy Policy (RU) | `/privacy` |
| Privacy Policy (EN) | `/privacy-en` |
| 404 | `/404.html` |

## Project Structure

```
SA website/
├── index.html                           # Homepage (Russian) — served at /
├── index-ru.html                        # Redirects to /
├── index-en.html                        # Homepage (English)
│
├── portfolio/index.html                 # Portfolio — 62+ projects
├── clients/index.html                   # Client showcase — 69+ clients
├── team/index.html                      # Team — 9 members
├── stratsovet/index.html                # Стратсовет landing page (RU)
├── stratsovet-en/index.html             # StratCouncil landing page (EN)
│
├── service-market-research/index.html   # Market Research service
├── service-strategy/index.html          # Strategy Development
├── service-investment/index.html        # Investment Consulting
├── service-fundraising/index.html       # Fundraising & M&A
├── service-acquisition/index.html       # Asset Acquisition
│
├── (+ -en/ variants for all above)
│
├── privacy/index.html                   # Privacy Policy (Russian, 152-ФЗ)
├── privacy-en/index.html                # Privacy Policy (English, GDPR-friendly)
├── 404.html                             # Custom 404 page
│
├── STYLES & SCRIPTS
│   ├── styles-ru.css                    # Main stylesheet
│   ├── styles-portfolio.css             # Portfolio page styles
│   ├── styles-service-modern.css        # Service page styles
│   └── script.js                        # Navigation, filtering, animations
│
└── ASSETS
    ├── logos/                           # Company and client logos
    │   └── Senior Advisors.png          # Transparent PNG logo
    ├── ФОТО/                            # Team member photos (grayscale, max 900px)
    ├── favicon.ico                      # Favicon (orange, SA logo)
    ├── favicon-32x32.png
    ├── favicon-16x16.png
    ├── apple-touch-icon.png
    ├── og-image.png                     # Open Graph image (1200×630)
    ├── sitemap.xml                      # XML sitemap (25 pages)
    ├── robots.txt                       # Allow all, points to sitemap
    └── llms.txt                         # AI crawler context
```

## Website Pages

### Main Pages

**Homepage** (`/`)
- Hero section with statistics (100+ clients, 150+ projects, 20+ industries)
- 5 service cards with modern design
- Split M&A button (Fundraising / Acquisition)
- Contact section

**Portfolio** (`/portfolio`)
- 62+ projects in tombstone card format
- Category filtering: All / M&A / Strategy
- Responsive 3-column grid

**Clients** (`/clients`)
- 69+ clients across 10 industry categories
- Real company logos with JS-powered loading and initials fallback
- Industry categories: Technology, E-commerce, HealthTech, Logistics, HoReCa, FinTech, PropTech, Production, Media, Consulting
- Clients without logos show **NDA** placeholder instead of initials

**Team** (`/team`)
- 3 Partners with bios, education, contact info
- 6 Consultants & Analysts
- Professional grayscale photos

**Стратсовет** (`/stratsovet`)
- Standalone landing page for the closed strategic advisory club
- Scope of 5 areas, team profiles, demo workshop CTA
- AI enabler section explaining the subscription model
- Team section with 4 grayscale photos (Denis, Vadim, Vladislav ×2)

### Service Pages

| Page | URL | Key Stats |
|------|-----|-----------|
| Market Research | `/service-market-research` | 150+ studies |
| Strategy | `/service-strategy` | 50+ projects |
| Investment | `/service-investment` | 200+ projects |
| Fundraising | `/service-fundraising` | $50M+ volume |
| Acquisition | `/service-acquisition` | Buy-side M&A |

## Design Features

### Brand Identity
- **Primary Color**: `#F47720` (Orange)
- **Typography**: Inter — 700 headings, 400–600 body
- **Logo**: Transparent PNG + brand text
- **Dark accent**: `#2C3E50`

### Technical Features
- Clean URL architecture (subfolder `index.html` pattern)
- Responsive breakpoints: 960px / 768px / 640px / 480px
- CSS custom properties for consistent theming
- Vanilla JavaScript — no frameworks
- Mobile hamburger menu with click-based dropdowns
- GitHub Pages deployment with custom domain `s-advisors.com`

## Technical Stack

- **HTML5** — Semantic markup
- **CSS3** — Flexbox + Grid, custom properties
- **JavaScript (Vanilla)** — Filtering, navigation, logo loading
- **Hosting** — GitHub Pages + custom domain

### Browser Support
Chrome 90+, Firefox 88+, Safari 14+, Edge 90+, iOS Safari, Chrome Mobile

## Deployment

**Live on GitHub Pages with custom domain `s-advisors.com`**

Repository: https://github.com/VadimBatkin/senior-advisors-website

To deploy updates:
```bash
cd "C:\Users\User\SA website"
git add .
git commit -m "Your update message"
git push origin main
```

Changes go live within 1–2 minutes.

## Recent Updates

### May 2026 — SEO, Analytics, Privacy & UX

- **Yandex Metrika**: Counter (ID 109118609) added to all 25 pages — webvisor, clickmap, accurate bounce tracking.
- **SEO — hreflang**: `ru`/`en`/`x-default` alternate tags on all 20 core pages.
- **SEO — Organization schema**: `schema.org/Organization` JSON-LD on RU and EN homepages.
- **SEO — FAQPage schema**: 3–4 Q&A pairs on all 22 content pages.
- **SEO — Open Graph + Twitter Card**: Full OG tags and `summary_large_image` on all pages.
- **Favicon**: Orange `#F47720` background with SA logo — `.ico`, `32×32`, `16×16`, `apple-touch-icon`.
- **og-image.png**: 1200×630 branded image for social sharing.
- **sitemap.xml + robots.txt + llms.txt**: Search engine and AI crawler support.
- **Privacy Policy**: `/privacy` (152-ФЗ, RU) and `/privacy-en` (GDPR-friendly). Linked in footer of all pages. Updated to include Yandex Metrika and Google Fonts disclosure.
- **Custom 404**: Branded `/404.html` with navigation links, auto-served by GitHub Pages.
- **Phone updated**: +7 952 370 7111 across all 39 HTML files.
- **Legal name**: ООО "Синьор Эдвайзорс" in privacy policy.
- **Client testimonials slider**: Dark-background slider with 6 featured reviews + expand button showing all 29 Facebook reviews (temporarily removed, CSS preserved).
- **Стратсовет photo fixes**: Denis — `object-position: center top` to prevent head crop on mobile; Афанасьев — `object-position: center 25%`; mobile photo bleed corrected for 640px breakpoint.

### May 2026 — Root Homepage, Team Photos & Photo Optimization

- **Root homepage**: Created `index.html` at root so `s-advisors.com/` works without any suffix. `index-ru.html` now redirects to `/`.
- **Стратсовет team photos**: Added grayscale photos for all 4 team members (Denis, Vadim, Vladislav ×2). Fixed photo not appearing due to file never being committed to git.
- **Photo optimization**: Resized team photos from 4000–5000px originals to max 900px using LANCZOS resampling. Eliminated Moiré/dot artifacts from extreme downscaling. File sizes: 3–5 MB → 62–102 KB each.
- **Badge position**: Moved "Автор формата" badge to bottom of photo area on Denis's card so it no longer overlaps his head.
- **Portfolio additions**: Added Chat2Desk (стратегия развития) and Ондулин (поиск новых стратегических направлений) to portfolio (RU + EN).
- **Clients NDA fallback**: Clients without logos now show "NDA" in the placeholder circle instead of company initials.

### May 2026 — Clean URLs & Mobile Overhaul

- **Clean URL architecture**: All pages moved to subfolder `index.html` pattern
  (`/portfolio`, `/team`, `/stratsovet`, etc.). Old `.html` URLs redirect automatically.
- **Стратсовет landing page**: New `/stratsovet` page for the strategic advisory club subscription product. EN version at `/stratsovet-en`.
- **Mobile layout fixes**: Comprehensive audit and fixes across all pages:
  - Dropdown menu: switched from `visibility:hidden` to `display:none` to eliminate blank gaps in mobile nav
  - Service pages: fixed `numbered-item h3` and `results-grid` at 768px breakpoint
  - Index pages: fixed team section grid `minmax(350px→280px)` overflow on 375px phones
  - Stratsovet: fixed CSS cascade bug where scope and AI section base styles were placed after media queries, overriding responsive rules
- **Logo PNG**: Removed opaque white background from `Senior Advisors.png` via pixel-level alpha editing
- **Header**: Changed to solid white background (removed `backdrop-filter: blur`)
- **Footer**: Removed city/country from all pages
- **Copyright**: Updated to 2026 across all pages

### February 2026 — Local Logos & Custom Domain

- Migrated from `vadimbatkin.github.io/senior-advisors-website/` to `s-advisors.com`
- Replaced all Clearbit API logo URLs with local files in `/logos`
- Added new clients: Ондулин, Rimi

### January 2026 — GitHub Pages Launch

- Initial deployment to GitHub Pages
- Repository: https://github.com/VadimBatkin/senior-advisors-website

### December 2025 — Bilingual Launch

- Complete English translation of all 9 pages
- Language switcher on all pages
- Brand color standardized to `#F47720`

## Maintenance

### Adding Projects
1. Open `portfolio/index.html`
2. Copy an existing card structure
3. Set `data-type="ma"` or `data-type="strategy"`

### Adding Clients
1. Add logo to `logos/` folder
2. Open `clients/index.html`
3. Add entry to the `companyLogos` JS object and HTML card

### Adding Team Members
1. Add photo to `ФОТО/` folder
2. Open `team/index.html`
3. Copy existing team card structure

## Contact

**Senior Advisors**
- **Website**: https://s-advisors.com
- **Email**: info@s-advisors.com
- **Phone**: +7 952 370 7111

## License

© 2026 Senior Advisors. All rights reserved.

---

**Version**: 4.2 | **Last Updated**: May 2026 | **Status**: Live at s-advisors.com
