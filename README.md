# Senior Advisors Website

![Status](https://img.shields.io/badge/status-production--ready-brightgreen)
![Version](https://img.shields.io/badge/version-3.2-blue)
![Pages](https://img.shields.io/badge/pages-18-orange)
![Languages](https://img.shields.io/badge/languages-2-green)

Professional bilingual consulting company website for Senior Advisors - a leading M&A advisory and strategic consulting firm.

## 🌐 Live Website

**The website is now live on GitHub Pages!**

- **Russian version**: https://vadimbatkin.github.io/senior-advisors-website/index-ru.html
- **English version**: https://vadimbatkin.github.io/senior-advisors-website/index-en.html

Use the language switcher (RU/EN) to toggle between languages on any page.

## 📋 Project Overview

This is a complete, multi-page, **bilingual website** (Russian & English) showcasing Senior Advisors' consulting services, portfolio, team, and client relationships. The site features modern design, responsive layouts, professional presentation, and seamless language switching suitable for a premium international consulting firm.

### Key Statistics
- **18 HTML Pages** - 9 pages in Russian + 9 pages in English (complete bilingual coverage)
- **2 Languages** - Full Russian and English versions with language switcher
- **69+ Clients** - Across 10 industry categories
- **62+ Projects** - Detailed case studies with tombstone-style presentation
- **9 Team Members** - Partners and consultants with detailed profiles
- **5 Service Areas** - Market research, strategy, investment, fundraising, acquisitions

## 🚀 Quick Start

### Option 1: View Live Website (Easiest)
Visit the live website hosted on GitHub Pages:
- **Russian**: https://vadimbatkin.github.io/senior-advisors-website/index-ru.html
- **English**: https://vadimbatkin.github.io/senior-advisors-website/index-en.html

### Option 2: Open Directly in Browser (Local)
1. Navigate to the `SA website` folder
2. **Russian version:** Double-click `index-ru.html`
3. **English version:** Double-click `index-en.html`
4. Use the **RU/EN** language switcher in the navigation menu to switch between languages
5. Navigate through all pages using the menu

### Option 3: Local Web Server (Recommended for development)
```bash
# Navigate to the project folder
cd "path/to/SA website"

# Start a local server (Python 3.x required)
python -m http.server 8000

# Open in browser
# Russian: http://localhost:8000/index-ru.html
# English: http://localhost:8000/index-en.html
```

**Note:** Using a local server is recommended for proper logo loading via Clearbit API.

### Option 4: Share with Colleagues
1. Share the GitHub Pages URL (see Option 1 above)
2. Or extract the ZIP file (`Senior_Advisors_Website.zip`)
3. Follow instructions in `ИНСТРУКЦИЯ.txt` (included)
4. Can be accessed locally or via network (192.168.x.x:8000)

## 📁 Project Structure

```
SA website/
├── RUSSIAN PAGES (9 files)
│   ├── index-ru.html                    # Main homepage (Russian)
│   ├── portfolio.html                   # Portfolio with 62+ projects (Russian)
│   ├── clients.html                     # Client showcase (Russian)
│   ├── team.html                        # Team page (Russian)
│   ├── service-market-research.html     # Market Research service (Russian)
│   ├── service-strategy.html            # Strategy Development (Russian)
│   ├── service-investment.html          # Investment Consulting (Russian)
│   ├── service-fundraising.html         # Fundraising & M&A (Russian)
│   └── service-acquisition.html         # Asset Acquisition (Russian)
│
├── ENGLISH PAGES (9 files)
│   ├── index-en.html                    # Main homepage (English)
│   ├── portfolio-en.html                # Portfolio with 62+ projects (English)
│   ├── clients-en.html                  # Client showcase (English)
│   ├── team-en.html                     # Team page (English)
│   ├── service-market-research-en.html  # Market Research service (English)
│   ├── service-strategy-en.html         # Strategy Development (English)
│   ├── service-investment-en.html       # Investment Consulting (English)
│   ├── service-fundraising-en.html      # Fundraising & M&A (English)
│   └── service-acquisition-en.html      # Asset Acquisition (English)
│
├── STYLES & SCRIPTS
│   ├── styles-ru.css                    # Main stylesheet (homepage, navigation, footer)
│   ├── styles-portfolio.css             # Portfolio page styles (tombstone cards, filtering)
│   ├── styles-service-modern.css        # Modern service page styles (results cards, benefits)
│   ├── styles-service.css               # Service page base styles
│   └── script.js                        # JavaScript (filtering, navigation, animations)
│
├── ASSETS
│   ├── logos/                           # Company logos (42 files)
│   │   ├── Senior Advisors.png         # SA logo
│   │   ├── skai.svg                    # Client logos
│   │   ├── ivi.svg
│   │   └── ... (39+ more)
│   │
│   └── ФОТО/                            # Team member photos (9 files)
│       ├── Вадим Баткин.jpg
│       ├── Владислав Сероштан.jpg
│       └── ... (7+ more)
│
├── DOCUMENTATION
│   ├── README.md                        # This file (project documentation)
│   ├── README-PORTFOLIO.md              # Detailed development log
│   └── ИНСТРУКЦИЯ.txt                   # Instructions (Russian)
│
└── Senior_Advisors_Website.zip          # Ready-to-share archive
```

## 🌐 Website Pages

**All pages are available in both Russian and English versions with seamless language switching.**

### Language Switcher
- **Navigation Toggle:** Every page includes a RU/EN language switcher in the navigation menu
- **Consistent Experience:** Users can switch languages at any point while maintaining their position in the site structure
- **Professional Translation:** All content professionally translated to maintain business tone

### Main Pages

#### 1. **Homepage** (`index-ru.html`)
Professional consulting company homepage with:
- Hero section with statistics (100+ clients, 150+ projects, 20+ industries)
- 4 main service cards with modern design
- Innovative split service buttons in M&A card (dual navigation to Fundraising and Acquisition pages)
- About section highlighting company values
- Centered contact form (streamlined design)
- Full navigation with dropdown menu for services

#### 2. **Portfolio** (`portfolio.html`)
Investment banking style portfolio showcase:
- 62+ projects in tombstone card format
- Category filtering: All Projects, M&A (26 projects), Strategy (36+ projects)
- Professional project cards with industry tags, deal types, and results
- Responsive 3-column grid layout

#### 3. **Clients** (`clients.html`)
Comprehensive client showcase:
- 67+ clients across 10 industry categories
- Real company logos with automatic loading
- Industry categories: Technology, E-commerce, HealthTech, Logistics, HoReCa, FinTech, PropTech, Production, Media, Consulting
- Stats strip: 100+ clients, 150+ projects, 20+ industries, 10+ years

#### 4. **Team** (`team.html`)
Team presentation:
- 3 Partners with detailed bios, education, contact info
- 6 Consultants & Analysts with expertise areas
- Professional grayscale photos
- Contact information for partners (phone & email)

### Service Pages (5 Main + 4 Variants)

#### Modern Design Service Pages:
1. **Market Research** (`service-market-research.html`)
   - 150+ studies completed
   - 6 approach methodologies
   - Results-focused presentation

2. **Strategy Development** (`service-strategy.html`)
   - 50+ strategic projects
   - 6-step approach
   - Financial models and KPIs

3. **Investment Consulting** (`service-investment.html`)
   - 200+ projects across 20+ industries
   - Business plans, financial models, valuations
   - IT/Internet startup expertise

4. **Fundraising & M&A** (`service-fundraising.html`)
   - $50M+ deal volume
   - 9-step transaction process
   - Full deal support from preparation to closing

5. **Asset Acquisition** (`service-acquisition.html`)
   - M&A buy-side services
   - Target search and due diligence
   - 8-step acquisition process

## 🎨 Design Features

### Brand Identity
- **Primary Brand Color**: #F47720 (Orange) - Used consistently across all interactive elements
- **Gradient Palette**: #F47720 → #FF8A3D for buttons, icons, and accents
- **Typography**: Modern sans-serif with clear hierarchy (700 weight for headings, 400-600 for body)
- **Logo System**: Image logo (Senior Advisors.png) + brand text with 1px spacing
- **Color Philosophy**: Professional blue-grays with energetic orange accents

### Visual Design
- **Modern gradient backgrounds** - Professional color schemes with subtle transitions
- **Consistent orange branding** (#F47720) - Standardized across all 18 pages (both languages)
- **Grayscale team photos** - Professional, cohesive look with 100% grayscale filter
- **Real company logos** - 67+ client logos with automatic loading and intelligent fallback system
  - 42 local logos stored in `/logos` folder
  - 25+ logos loaded via Clearbit Logo API
  - Smart fallback: Company initials displayed in branded orange circles when logos fail to load
- **Circular gradient icons** - Service page visual elements with hover animations
- **Investment banking tombstones** - Portfolio project cards with professional styling
- **Peach gradient cards** - Results sections with #FFF5F0 → #FFE8DC backgrounds

### Interactive Elements
- **Language switcher** - RU/EN toggle on all pages for instant language switching
- **Dropdown navigation menu** - Smooth animations, hover effects
- **Category filtering** - Portfolio project filtering (M&A / Strategy)
- **Hover animations** - Cards lift and enhance shadows
- **Responsive design** - Mobile-first approach
- **Contact form** - Functional with validation

### Technical Features
- **Bilingual architecture** - Complete Russian and English versions with language switcher
- **Responsive grid layouts** - Auto-fit columns (3/2/1) with flexible minmax sizing
- **CSS custom properties** - Consistent brand colors (#F47720) and spacing system
- **Advanced CSS techniques** - Flexbox + Grid combinations for equal-height cards
- **Gradient animations** - Slide-in effects on service buttons with ::before pseudo-elements
- **JavaScript filtering** - Portfolio category system with smooth transitions
- **Intelligent logo loading** - Local logos + Clearbit API with company initials fallback system
- **Smooth scrolling** - Anchor link navigation throughout site
- **Mobile hamburger menu** - Touch-friendly responsive navigation
- **Image optimization** - Grayscale filters and object-fit for consistent team photos
- **SEO optimization** - Meta tags and descriptions in both Russian and English

## 🔧 Technical Stack

### Technologies
- **HTML5** - Semantic markup
- **CSS3** - Modern layouts (Flexbox, Grid)
- **JavaScript (Vanilla)** - No frameworks, lightweight
- **Python HTTP Server** - Development server (optional)

### Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

### Requirements
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Python 3.x (for local server option)
- No database or backend required
- No build process or dependencies

### Performance
- **Static HTML**: No server-side processing required
- **Lightweight**: ~29 MB total (including all assets)
- **Fast Loading**: Minimal JavaScript, optimized CSS
- **No External Dependencies**: All assets self-contained
- **SEO Friendly**: Semantic HTML markup

## 📱 Responsive Breakpoints

```css
/* Desktop - Default */
.portfolio-grid {
    grid-template-columns: repeat(3, 1fr);
}

/* Tablet - 768px and below */
@media (max-width: 768px) {
    grid-template-columns: repeat(2, 1fr);
}

/* Mobile - 480px and below */
@media (max-width: 480px) {
    grid-template-columns: 1fr;
}
```

## 💡 Technical Innovations

### CSS Architecture
- **CSS Custom Properties**: Centralized color system using CSS variables for easy theming
- **Flexbox + Grid Hybrid**: Combined layout systems for equal-height cards and responsive grids
- **Pseudo-element Animations**: `::before` elements for slide-in gradient effects without JavaScript
- **Auto-fit Grids**: Dynamic column layouts that adapt from 3 → 2 → 1 columns based on viewport

### Component Design
- **Split Service Buttons**: Innovative dual-button card design with independent hover states
- **Gradient Result Cards**: Unified design system with peach gradients and centered icons
- **Tombstone Portfolio Cards**: Investment banking-style project cards with flexible heights
- **Logo Fallback System**: Automatic logo loading with gradient placeholder generation

### Performance Optimizations
- **Image Rendering**: CSS filters (grayscale) applied without pre-processing
- **Minimal JavaScript**: Vanilla JS for filtering, no framework overhead
- **Static Assets**: All resources bundled, no CDN dependencies
- **Responsive Images**: object-fit and object-position for optimal photo display

## 🎯 Key Features

### Navigation System
- ✅ Dropdown menu for services (5 service pages)
- ✅ Active page highlighting
- ✅ Smooth scroll for anchor links
- ✅ External navigation for pages
- ✅ Mobile hamburger menu
- ✅ Consistent header/footer across all pages

### Portfolio System
- ✅ Professional tombstone cards
- ✅ JavaScript-powered filtering
- ✅ Flexible card heights (auto-adjusting)
- ✅ Color-coded categories (Orange for M&A, Blue for Strategy)
- ✅ Industry tags and deal types
- ✅ Actual business results in footers

### Client Showcase
- ✅ 67+ company logos with automatic loading
- ✅ Clearbit Logo API integration for fallback
- ✅ Gradient placeholder circles with initials
- ✅ 10 organized industry categories
- ✅ Modern card design with hover effects

### Service Pages
- ✅ Consistent structure across all pages
- ✅ Circular gradient icons with animations
- ✅ "В результате" sections with gradient cards
- ✅ Numbered "Why trust us" sections
- ✅ Portfolio CTA sections with metrics

## 🚀 Deployment

### Current Deployment: GitHub Pages ✅

**The website is currently live on GitHub Pages:**

- **Russian**: https://vadimbatkin.github.io/senior-advisors-website/index-ru.html
- **English**: https://vadimbatkin.github.io/senior-advisors-website/index-en.html
- **Repository**: https://github.com/VadimBatkin/senior-advisors-website

To update the live website:
```bash
cd "C:\Users\User\SA website"
git add .
git commit -m "Your update message"
git push origin main
```

Changes will be live on GitHub Pages within 1-2 minutes.

### Alternative Deployment Options

**Netlify** (Free, Easy):
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
cd "SA website"
netlify deploy --prod
```

**Vercel** (Free, Fast):
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
cd "SA website"
vercel --prod
```

### 2. Cloud Hosting
- **AWS S3 + CloudFront**
- **Azure Static Web Apps**
- **Google Cloud Storage**
- **DigitalOcean Spaces**

### 3. Traditional Web Hosting
- Upload via FTP to any web host
- Works with shared hosting, VPS, or dedicated servers
- No server-side requirements (static HTML/CSS/JS)

## 📊 Project Statistics

### Content
- **Total Pages**: 18 (9 Russian + 9 English)
- **Languages**: 2 (Russian & English with full bilingual support)
- **Total Projects**: 62+ (same across both languages)
- **Total Clients**: 67+ (same across both languages)
- **Team Members**: 9
- **Service Areas**: 5 main services

### Files
- **HTML Files**: 18 (9 Russian pages + 9 English pages)
- **CSS Files**: 4 (main styles, portfolio styles, service styles, modern service styles)
- **JavaScript Files**: 1 (filtering, navigation, form validation)
- **Logos**: 42 local files + 25+ via Clearbit API
- **Photos**: 9 files (team member photos, all grayscale)
- **Total Size**: ~30 MB (zipped with all assets)

### Development
- **Lines of Code**: 22,000+ (HTML, CSS, JS across both languages)
- **Development Time**: 4+ months
- **Last Updated**: February 19, 2026
- **Status**: Live on GitHub Pages (Production)

## 🔄 Recent Updates

### February 19, 2026 - **LOCAL LOGOS & NEW CLIENTS**
- ✅ **New Clients Added**:
  - Ондулин (Ondulin) - Building materials manufacturer (Производство section)
  - Rimi - Baltic supermarket chain (E-commerce и Ритейл section)
- ✅ **Logo System Migration**: Replaced all Clearbit API URLs with local logo files
  - Updated clients.html and clients-en.html (~20 logos)
  - Updated portfolio.html and portfolio-en.html (~17 logos)
  - All logos now load from local `/logos` folder
  - Improved offline viewing and faster page loads
- ✅ **New Logo Files Added**:
  - Ондулин.png, Rimi.png

### January 29, 2026 - **GITHUB PAGES DEPLOYMENT 🚀**
- ✅ **Live Website**: Deployed to GitHub Pages
  - Russian: https://vadimbatkin.github.io/senior-advisors-website/index-ru.html
  - English: https://vadimbatkin.github.io/senior-advisors-website/index-en.html
- ✅ **Git Repository**: Initialized and pushed to GitHub
  - Repository: https://github.com/VadimBatkin/senior-advisors-website
  - 96 files committed with full version control
- ✅ **Public Access**: Website now accessible globally
  - Share URLs with colleagues and clients
  - No local server required for viewing
  - All logos and assets loading properly

### December 22, 2025 - **BILINGUAL VERSION LAUNCH 🌍**
- ✅ **Complete English Translation**: Created full English versions of all 9 pages
  - index-en.html, portfolio-en.html, clients-en.html, team-en.html
  - 5 English service pages (market research, strategy, investment, fundraising, acquisition)
- ✅ **Language Switcher Integration**: Added RU/EN toggle to all 18 pages
  - Seamless language switching maintaining navigation context
  - Consistent placement across all pages
  - Professional bilingual user experience
- ✅ **Content Translation**: Professional English translation
  - Business consulting tone maintained
  - All technical content accurately translated
  - SEO-friendly English meta tags and descriptions
- ✅ **Logo Fallback Enhancement**: Improved logo display system
  - Company initials displayed for failed Clearbit API logos
  - Branded orange circular fallbacks (#F47720)
  - Responsive font sizing (1.5rem for 3 letters, 2rem for 2 letters)
  - Better local viewing experience
- ✅ **Documentation Updates**:
  - Updated README.md to reflect bilingual website (Version 3.0)
  - Updated project statistics (18 pages, 2 languages)
  - Added bilingual Quick Start instructions

### December 2, 2025
- ✅ **Logo System Overhaul**: Replaced text-based logo with image logo (Senior Advisors.png) + brand text
- ✅ **Logo Positioning**: Fine-tuned spacing (1px gap) and sizing (40px height, 20px text) for perfect alignment
- ✅ **Brand Color Standardization**: Updated all orange colors from #FF6B35 to #F47720 (30+ references across 5 CSS files)
- ✅ **Split Service Buttons**: Added innovative dual-button design in M&A service card with gradient hover animations
  - Left button: "Фандрейзинг, продажа бизнеса" → service-fundraising.html
  - Right button: "Приобретение активов" → service-acquisition.html
- ✅ **Contact Section Simplification**: Removed partner contact details, kept only centered contact form
- ✅ **Footer Cleanup**: Removed SA icon boxes from all 13 pages, kept text-only branding
- ✅ **Results Section Redesign**: Unified "В результате" design across 4 service pages
  - Gradient card design (#FFF5F0 → #FFE8DC backgrounds)
  - Centered checkmark icons with orange gradient (56px)
  - Equal height cards using CSS Grid + Flexbox
  - Consistent typography and spacing
- ✅ **Team Page Updates**:
  - Added Виталий Лабецкий photo with optimal positioning
  - Fixed image rendering artifacts on Вадим Баткин photo
  - Applied grayscale filter to all team member photos
  - Fixed card alignment and spacing issues
- ✅ **Documentation & Deployment**:
  - Created ИНСТРУКЦИЯ.txt with Russian instructions
  - Generated Senior_Advisors_Website.zip archive (~29 MB)
  - Set up localhost server (http://localhost:8000)
  - Wrote comprehensive README.md with deployment guides

### November 2025
- ✅ Created team page with 9 team members
- ✅ Integrated 67+ client logos
- ✅ Split M&A page into Fundraising and Acquisition
- ✅ Implemented dropdown navigation menu
- ✅ Unified footer structure (4 columns)
- ✅ Optimized homepage (4 service cards)
- ✅ Added real team member photos (grayscale)

## 🛠️ Development Commands

### Start Local Server
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000

# Node.js (http-server)
npx http-server -p 8000
```

### Create Archive for Sharing
```powershell
# Windows PowerShell
Compress-Archive -Path 'SA website' -DestinationPath 'Senior_Advisors_Website.zip' -Force
```

```bash
# Linux/Mac
zip -r Senior_Advisors_Website.zip "SA website"
```

## 📝 Maintenance & Updates

### Adding New Projects to Portfolio
1. Open `portfolio.html`
2. Find the appropriate category section
3. Copy existing portfolio card structure
4. Update content (title, description, industry, deal type, results)
5. Set `data-type` attribute: "ma" or "strategy"

### Adding New Clients
1. Add logo file to `logos/` folder
2. Open `clients.html`
3. Find appropriate industry section
4. Add new client card with logo path

### Adding Team Members
1. Add photo to `ФОТО/` folder
2. Open `team.html`
3. Copy existing team card structure
4. Update with new member information

### Updating Service Content
1. Open relevant `service-*.html` file
2. Update content sections
3. Maintain existing structure for consistency

## 🌍 Browser Testing Checklist

### Bilingual Features
- [ ] **Language switcher** works on all pages (RU ↔ EN)
- [ ] Russian homepage (index-ru.html) loads correctly
- [ ] English homepage (index-en.html) loads correctly
- [ ] Language toggle maintains navigation context

### Core Functionality
- [ ] Homepage loads correctly with split service buttons
- [ ] Navigation menu works (all links functional)
- [ ] Dropdown menu displays and functions smoothly
- [ ] Portfolio filtering works (All/M&A/Strategy)
- [ ] Mobile responsive (test at 768px, 480px breakpoints)
- [ ] All images load correctly (logos + team photos)
- [ ] Contact form displays properly (centered layout)
- [ ] Footer links work on all pages (no SA icon box)
- [ ] Team photos display in grayscale (100% filter)
- [ ] Client logos load (with initials fallbacks for Clearbit logos)
- [ ] Service pages display correctly (unified results sections)
- [ ] Hover effects work smoothly (gradient animations)
- [ ] Brand colors consistent (#F47720 orange)
- [ ] Logo displays correctly (image + text, 1px gap)

## 🔧 Troubleshooting

### Common Issues

**Images not loading:**
- Ensure you're running from a local server (not file:// protocol) for best experience
- Check that `logos/` and `ФОТО/` folders are in the same directory
- Verify file paths are relative (not absolute)
- **Clearbit logos:** Some client logos use Clearbit API and may show company initials when viewed locally (file://) - this is normal and will work perfectly when deployed online

**Styles not applying:**
- Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
- Check that all CSS files are in the root directory
- Ensure no ad blockers are interfering

**Portfolio filtering not working:**
- Verify `script.js` is loading correctly
- Check browser console for JavaScript errors
- Ensure buttons have correct `data-type` attributes

**Localhost not accessible on network:**
- Check firewall settings (allow Python on port 8000)
- Verify correct IP address (use `ipconfig` on Windows)
- Ensure devices are on the same network

**Split service buttons not working:**
- Check that service-fundraising.html and service-acquisition.html exist
- Verify links in index-ru.html are correct
- Clear cache and reload page

## 📞 Contact & Support

**Senior Advisors**
- **Website**: www.s-advisors.com
- **Email**: info@s-advisors.com
- **Phone**: +7 (921) 646-47-20
- **Location**: Санкт-Петербург, Россия

## 📄 License

© 2026 Senior Advisors. All rights reserved.

---

**Project Status**: ✅ Live on GitHub Pages
**Live URLs**:
- Russian: https://vadimbatkin.github.io/senior-advisors-website/index-ru.html
- English: https://vadimbatkin.github.io/senior-advisors-website/index-en.html

**Last Updated**: February 19, 2026
**Version**: 3.2
**Languages**: Russian & English
**Total Pages**: 18 (9 per language)
**Developed with**: Claude Code

For detailed development history, see [README-PORTFOLIO.md](README-PORTFOLIO.md)
