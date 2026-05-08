# Senior Advisors Website

![Status](https://img.shields.io/badge/status-production--ready-brightgreen)
![Version](https://img.shields.io/badge/version-4.1-blue)
![Pages](https://img.shields.io/badge/pages-20-orange)
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
- **20 HTML Pages** — 10 pages in Russian + 10 pages in English (complete bilingual coverage)
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
├── STYLES & SCRIPTS
│   ├── styles-ru.css                    # Main stylesheet
│   ├── styles-portfolio.css             # Portfolio page styles
│   ├── styles-service-modern.css        # Service page styles
│   └── script.js                        # Navigation, filtering, animations
│
└── ASSETS
    ├── logos/                           # Company and client logos
    │   └── Senior Advisors.png          # Transparent PNG logo
    └── ФОТО/                            # Team member photos (grayscale)
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
- **Phone**: +7 (921) 646-47-20

## License

© 2026 Senior Advisors. All rights reserved.

---

**Version**: 4.1 | **Last Updated**: May 2026 | **Status**: Live at s-advisors.com
