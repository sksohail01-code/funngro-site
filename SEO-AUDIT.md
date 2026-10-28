# Funngro SEO Audit Report

**Scope:** funngro.com (Teens page and Companies page) and the redesigned 2-page site.
**Important limitation:** I could not load funngro.com's live HTML in this session, so the "current site" column is a *verification checklist*, not measured results. Run each check with the tool named. Findings about the new site are verified from its source.

## 1. Positioning and keyword strategy (from public sources)
Funngro describes itself as India's first freelancing platform for teenagers; users are called "teenlancers"; it was featured on Shark Tank India. Two audiences means two intents, so two pages:

| Page | Primary keyword | Secondary keywords |
|---|---|---|
| Teens (`/`) | freelancing platform for teens | earn money as a teenager, teenager freelance jobs India, teenlancer |
| Companies (`/companies.html`) | hire teen freelancers | teen talent for startups, Gen Z content creators, freelance designers for small business |

## 2. Audit checklist: current funngro.com (verify each)
| Area | What to check | Tool |
|---|---|---|
| Titles | Unique, 50-60 chars, keyword first, one per page | Screaming Frog / view-source |
| Meta descriptions | Unique, 140-160 chars, with a call to action | Search Console |
| Headings | Exactly one H1 per page, logical H2/H3 | Browser dev tools |
| Rendering | Is content visible without JavaScript? (app-style sites often fail) | "View source" vs "Inspect" |
| Core Web Vitals | LCP < 2.5s, CLS < 0.1, INP < 200ms | PageSpeed Insights |
| Mobile | Viewport tag, tap targets, readable fonts | Lighthouse |
| Indexing | robots.txt, sitemap.xml, canonical tags, no accidental noindex | Search Console |
| Structured data | Organization, FAQPage, JobPosting where relevant | Rich Results Test |
| Images | Descriptive alt text, WebP, width/height set | Lighthouse |
| Internal links | Teens and Companies pages cross-linked with descriptive anchors | Crawl |
| Brand SERP | Knowledge panel, app store links, social profiles | Google search "Funngro" |
| Duplicate brand content | Third-party pages and old blog copies competing for "Funngro" | Search "site:" and brand queries |

## 3. Implemented on the new site (verified in source)
- Unique `<title>` and meta description per page, keyword-led
- One H1 per page, H2 sections, H3 cards
- Canonical, Open Graph and Twitter Card tags, `lang="en-IN"`
- JSON-LD: Organization (with founders) and FAQPage per page
- Static HTML, no JavaScript needed to read content, tiny inline CSS (no render-blocking requests)
- Responsive viewport, dark-mode support, visible focus states, ARIA-labelled nav
- `robots.txt` and `sitemap.xml` included
- Descriptive internal links between both pages

## 4. Priority recommendations for Funngro
1. **High:** Make sure both audience pages render full text in raw HTML (server-side rendering or static output).
2. **High:** One unique title/description per page; target the keywords in section 1.
3. **High:** Submit sitemap in Google Search Console; fix any coverage errors.
4. **Medium:** Add FAQ and Organization schema; add JobPosting/Offer schema for live projects where eligible.
5. **Medium:** Publish a blog hub (how to start freelancing as a teen, first-job guides for parents, hiring Gen Z); internally link to the two money pages.
6. **Medium:** Earn backlinks from Shark Tank India coverage, school and college partnerships, and press (Entrackr etc.).
7. **Low:** Image compression, lazy loading, preconnect to fonts if used.

## 5. Compliance note
The audience includes minors. Keep parental-approval language visible, avoid collecting unnecessary personal data in forms, and keep the privacy policy and terms linked in the footer.

## 6. Facts used on the new site (and sources)
Earning/learning/certificate positioning (App Store listing), age 14+ with parental approval (Entrackr), project categories (Entrackr, HDFC page), investors Namita Thapar and Amit Jain (Women's Web, CB Insights). Age ranges differ across sources (14-22 vs 14-25); confirm the official one before launch.
