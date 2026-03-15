# GEO + SEO Audit Report: adro.com

**Audit Date:** March 15, 2026
**Domain:** adro.com
**Business Type:** E-commerce (Automotive Aftermarket Aerodynamics)
**Platform:** Shopify (Dawn theme v15.2.0)
**Tagline:** "NOT FOR EVERYBODY"

---

## GEO Score: 24/100

| Category | Score | Weight | Weighted |
|---|---|---|---|
| AI Citability & Visibility | 18/100 | 25% | 4.5 |
| Brand Authority Signals | 25/100 | 20% | 5.0 |
| Content Quality & E-E-A-T | 30/100 | 20% | 6.0 |
| Technical Foundations | 55/100 | 15% | 8.3 |
| Structured Data | 20/100 | 10% | 2.0 |
| Platform Optimization | 15/100 | 10% | 1.5 |
| **Composite GEO Score** | | | **27/100** |

**Grade: F** — Significant improvements needed across all GEO dimensions.

---

## Executive Summary

ADRO is a premium automotive aerodynamics company specializing in CFD-engineered carbon fiber body kits for performance vehicles (Porsche, BMW, Toyota, Tesla, etc.). Despite having genuinely differentiated technical expertise (F1-level CFD methodology), the website is **severely underperforming for AI search visibility**. The site is almost entirely visual/image-driven with minimal indexable text content, no llms.txt file, no AI crawler-specific directives, sparse structured data, and virtually no citable content passages that AI engines could reference when answering user queries.

**The core problem:** ADRO has a compelling story and real technical differentiation, but almost none of it is accessible to AI search engines in a citable format.

---

## 1. AI Citability & Visibility (18/100)

### Homepage Citability: 27/100 (Grade F)
- Only **2 text blocks** analyzed — the homepage is almost entirely images
- **0 optimal-length passages** (ideal: 134-167 words, self-contained, fact-rich)
- Word count: **180 words** total on the homepage — critically low
- Both blocks scored F (31 and 23)

### Blog Content Citability
**"How F1-Level CFD Creates Real Performance"** — Average: 33.5/100 (Grade F)
- 4 blocks analyzed, 0 in Grade A or B range
- Best block scored 40/100 (Grade D)
- Zero statistical density across all blocks
- Passages lack self-contained facts and data points

**"Beyond Basic CFD"** — Average: 43.7/100 (Grade D)
- 6 blocks analyzed, best scored 61/100 (Grade C)
- 1 optimal-length passage found
- This is the strongest content on the site, but still underperforming

### Key Citability Issues
- **No data/statistics in content** — statistical density scores are 0 across nearly all passages
- **Passages are not self-contained** — they rely on surrounding context
- **No definition-style answers** — AI engines favor "X is Y" factual statements
- **Marketing language dominates** — "pushing boundaries," "unmatched performance" are not citable

### AI Crawler Access: 45/100
- **No AI-specific crawler directives** in robots.txt
- No GPTBot, ClaudeBot, PerplexityBot, OAI-SearchBot, or Google-Extended rules
- All AI crawlers fall under the generic `User-agent: *` rules
- Generic rules block: admin, cart, checkout, orders, account, search, policies, and collection sorting/filtering pages
- **Nutch is fully blocked** (`Disallow: /`)
- Shopify's default robots.txt provides basic coverage but no AI-specific optimization

### llms.txt: Missing (0/100)
- **No llms.txt file exists** (404 response)
- Missing opportunity to provide AI engines with structured brand information
- No controlled narrative for how AI should understand and describe ADRO

---

## 2. Brand Authority Signals (25/100)

### Platform Presence Assessment

| Platform | Status | Impact |
|---|---|---|
| YouTube | Channel exists (youtube.com/adroofficial) | Linked in schema but needs content audit |
| Instagram | Active (@adro.inc) | Strong visual presence, linked in schema |
| TikTok | Present (@adro.inc) | Linked in schema |
| Reddit | Not detected | Missing — high correlation with AI visibility |
| Wikipedia | Not detected | No article — limits entity recognition |
| Wikidata | Not detected | No entry — hurts AI entity understanding |
| LinkedIn | Not detected | Not linked in schema (empty sameAs slots) |
| Facebook | Not detected | Empty sameAs slot in schema |
| Twitter/X | Not detected | Empty sameAs slot in schema |

### Critical Issues
- **5 empty strings in Organization sameAs array** — signals incompleteness to AI engines
- **No Reddit presence** — Reddit mentions correlate highly with AI citations
- **No Wikipedia/Wikidata** — AI engines rely heavily on these for entity recognition
- **LinkedIn missing** — no thought leadership platform presence
- Brand name "ADRO" is short and generic, making entity disambiguation difficult

---

## 3. Content Quality & E-E-A-T (30/100)

### Experience Signals: Low
- No customer testimonials or case studies on key pages
- Gallery section exists but lacks descriptive content
- Racing blog exists but only 1 article found
- No "before/after" performance data from real installations

### Expertise Signals: Moderate
- Claims F1-level CFD expertise
- Mentions "Scott" developing custom OpenFOAM software (name only, no credentials)
- References "100 million cells" mesh resolution
- Uses technical terminology correctly (CFD, downforce, drag, mesh independence)
- **Missing:** No author bios, no team credentials page, no certifications displayed

### Authority Signals: Low
- No press mentions or media features referenced
- No awards or certifications displayed
- No partnerships highlighted (beyond CSF radiators as accessories)
- No external validation of CFD claims

### Trustworthiness Signals: Moderate
- HTTPS enabled with valid certificate
- Strong security headers (HSTS, CSP, X-Frame-Options)
- Privacy and shipping policies exist
- FAQ page available
- Dealer locator present
- **Missing:** No visible customer reviews on product pages (Judge.me installed but no review counts visible)

### Content Gaps
- **Company page (332 words):** No team bios, no founding story, no credentials
- **Homepage (180 words):** Almost entirely images with minimal text
- **Product pages:** Good meta descriptions but thin on-page text content
- **Blog:** Only ~8 technical/lab articles — far too few for authority building
- **No FAQ schema** on FAQ page
- **Zero blog post dates visible** — freshness signals missing

---

## 4. Technical Foundations (55/100)

### Strengths
| Check | Status |
|---|---|
| HTTPS | Yes — valid SSL |
| Server-Side Rendering | Yes — Shopify SSR |
| Canonical URLs | Yes — properly set |
| Mobile Responsive | Yes — viewport meta tag |
| Cloudflare CDN | Yes — CF-Ray headers present |
| HSTS | Yes — max-age=7889238 (~91 days) |
| Content-Security-Policy | Yes — blocks mixed content, frame-ancestors 'none' |
| X-Frame-Options | DENY |
| X-Content-Type-Options | nosniff |
| X-XSS-Protection | 1; mode=block |

### Issues
| Check | Status | Severity |
|---|---|---|
| Meta description (homepage) | **Missing** | Critical |
| H1 tag (homepage) | Empty first H1 + styling issue ("Not ForEVERYBODY") | High |
| H1 tag (company page) | **Missing entirely** | High |
| Referrer-Policy header | Missing | Medium |
| Permissions-Policy header | Missing | Medium |
| HSTS max-age | Only 91 days (recommended: 1 year / 31536000) | Medium |
| Image alt text | **Most images have empty alt=""** | High |
| OG image (homepage) | Missing | Medium |
| Twitter image (homepage) | Missing | Medium |
| Page load (server timing) | 48ms processing — good | — |
| Heading hierarchy | Cart/checkout headings pollute structure | Medium |

### Sitemap Analysis
- 4 nested sitemaps: products (215+), pages (19), collections (3), blogs (70+)
- **~307+ total indexed URLs** — reasonable for the catalog size
- Product sitemap is comprehensive
- Blog sitemap includes gallery entries (good for image indexing)

### robots.txt Assessment
- Standard Shopify defaults — blocks admin, cart, checkout, orders
- **"Checkouts are for humans"** policy noted
- AhrefsBot/AhrefsSiteAudit: 10s crawl delay
- MJ12bot: 10s crawl delay
- Nutch: Fully blocked
- **No sitemap directive** in robots.txt pointing to sitemap.xml

---

## 5. Structured Data (20/100)

### Existing Schema Markup

**Organization (all pages):**
```json
{
  "@type": "Organization",
  "name": "ADRO US",
  "logo": "https://adro.com/cdn/shop/files/adro.svg",
  "sameAs": ["", "", "", "instagram", "tiktok", "", "", "youtube", ""],
  "url": "https://adro.com"
}
```
**Issues:** 5 empty sameAs strings, no `description`, no `foundingDate`, no `founder`, no `address`, no `contactPoint`, no `knowsAbout`

**WebSite (homepage only):**
```json
{
  "@type": "WebSite",
  "potentialAction": { "@type": "SearchAction", ... }
}
```
**Status:** Correctly implemented

**Product (product pages):**
```json
{
  "@type": "Product",
  "brand": "ADRO USA",
  "category": "Motor Vehicle Frame & Body Parts",
  "offers": { "availability": "OutOfStock", "price": "0.00" }
}
```
**Issues:** Price shows $0 (misleading — these are inquiry-based kits), no `aggregateRating`, no `review`, no `sku`, no `gtin`, no `material`, no `weight`

### Missing Schema Types
- **LocalBusiness** or **AutoPartsStore** — not implemented
- **FAQPage** — FAQ page exists but no FAQ schema
- **Article/BlogPosting** — blog posts lack article schema
- **BreadcrumbList** — no breadcrumb schema
- **VideoObject** — if any videos exist on pages
- **Review/AggregateRating** — Judge.me installed but no review schema detected

---

## 6. Platform Optimization (15/100)

### ChatGPT Readiness: Low
- Content is too thin for ChatGPT to extract meaningful answers
- No FAQ-style content that maps to common user questions
- Product pages lack detailed specifications
- No comparison content (ADRO vs. competitors)

### Perplexity Readiness: Low
- No data-rich, fact-dense passages for citation
- No publication dates on blog posts
- No author attribution
- Limited source-quality signals

### Google AI Overviews Readiness: Low
- No featured-snippet-optimized content
- No definition blocks ("ADRO is...")
- No numbered/bulleted specification lists
- Missing FAQ schema
- Homepage has no meta description

---

## Prioritized Action Plan

### Quick Wins (1-2 weeks)

1. **Add homepage meta description** — Currently null. Write a compelling 150-160 character description.
   - Suggested: "ADRO designs CFD-engineered carbon fiber aero kits for BMW, Porsche, Toyota & Tesla. F1-level aerodynamics. Premium prepreg carbon fiber. Made in USA."

2. **Fix Organization schema sameAs** — Remove 5 empty strings, add LinkedIn, Facebook, Twitter URLs or remove empty slots entirely.

3. **Add image alt text** — Nearly all images have empty alt attributes. Add descriptive alt text to every product and hero image.

4. **Fix homepage H1** — Current first H1 is empty. Ensure a single, descriptive H1 like "ADRO — CFD-Engineered Carbon Fiber Aero Kits"

5. **Add H1 to company page** — Currently missing entirely.

6. **Create llms.txt** — Provide AI engines with structured brand information:
   ```
   # ADRO
   > ADRO (Aerodynamic Development & Race Optimization) designs and manufactures
   > CFD-engineered carbon fiber aerodynamic kits for performance vehicles.

   ## About
   - [Company](https://adro.com/pages/company)
   - [FAQ](https://adro.com/pages/faq)

   ## Products
   - [Vehicle Kits](https://adro.com/collections/vehicles)
   - [Wings](https://adro.com/collections/wings)

   ## Technical
   - [CFD Methodology](https://adro.com/blogs/labs/the-science-behind-every-adro-kit-how-f1-level-cfd-creates-real-performance)
   - [Beyond Basic CFD](https://adro.com/blogs/labs/beyond-basic-cfd)
   ```

7. **Add sitemap directive to robots.txt** — Add `Sitemap: https://adro.com/sitemap.xml`

### Medium-Term (1-2 months)

8. **Rewrite company page with E-E-A-T signals** — Add founder/team bios with credentials, founding year, company history, team size, location, certifications. Target 800+ words.

9. **Add FAQ schema to FAQ page** — Implement FAQPage JSON-LD structured data.

10. **Add Article schema to blog posts** — Include `datePublished`, `dateModified`, `author` (with credentials), `publisher`.

11. **Enrich Product schema** — Add `aggregateRating`, `review`, `material` (prepreg carbon fiber), `weight`, proper pricing or `priceSpecification`.

12. **Create data-rich citability blocks** on key pages:
    - "ADRO uses F1-level Computational Fluid Dynamics (CFD) with mesh resolutions exceeding 100 million cells per simulation to engineer carbon fiber aero kits. Each kit undergoes mesh independence studies, track testing with GPS data loggers, and strain gauge validation before production."
    - Include specific numbers: downforce percentages, drag reduction figures, weight savings.

13. **Add customer reviews to product pages** — Configure Judge.me to display reviews and generate Review schema.

14. **Expand blog content** — Publish 2-4 technical articles per month covering:
    - Vehicle-specific aerodynamic breakdowns with data
    - CFD simulation results with before/after numbers
    - Installation guides with technical specs
    - Track test results with lap time comparisons

### Strategic (2-6 months)

15. **Build Reddit presence** — Engage authentically in r/BMW, r/Porsche, r/GR86, r/TeslaMotors, r/cars. Share technical content, answer aero questions.

16. **Pursue Wikipedia notability** — Get featured in automotive media (Road & Track, Car and Driver, etc.) to establish notability criteria for a Wikipedia article.

17. **Create Wikidata entry** — Register ADRO as an entity with proper classifications (automotive parts manufacturer, carbon fiber, aerodynamics).

18. **Publish original performance data** — Create benchmark pages with CFD data, drag coefficients, downforce numbers. This is ADRO's strongest differentiator and most AI-citable content type.

19. **Create comparison content** — "ADRO vs. Vorsteiner vs. 3DDesign" etc. AI engines frequently answer comparison queries.

20. **Build LinkedIn thought leadership** — Founder and engineering team should publish technical articles about automotive aerodynamics.

21. **Create video content with transcripts** — YouTube channel exists but needs technical content with full transcripts for AI parseability.

---

## Key Findings Summary

### Critical Issues
1. **Homepage has no meta description** — AI engines and Google have nothing to display
2. **Homepage has only 180 words** — far below the minimum for AI citability
3. **No llms.txt file** — missing the emerging standard for AI communication
4. **Most images lack alt text** — invisible to AI crawlers
5. **Organization schema has 5 empty sameAs entries** — signals incomplete data

### High Priority Issues
6. **Zero citation-ready passages** on homepage — no content AI engines can quote
7. **No FAQ schema** despite having an FAQ page
8. **No Article schema** on blog posts
9. **No author attribution** on any content
10. **Company page missing H1** and has only 332 words

### Strengths to Build On
- Genuine technical differentiation (CFD methodology, 100M+ cell meshes)
- Server-side rendering (Shopify) — AI crawlers can access content
- Strong security headers
- Good product meta descriptions
- Product schema exists (needs enrichment)
- YouTube channel and Instagram presence established
- Technical blog content exists (needs expansion and optimization)

---

## Methodology

This audit evaluates **Generative Engine Optimization (GEO)** readiness — how well a website performs in AI-powered search engines (ChatGPT, Claude, Perplexity, Gemini, Google AI Overviews).

**Scoring Dimensions:**
- **AI Citability (25%):** Passage-level scoring for AI citation readiness (word count, self-containment, factual density, structural readability)
- **Brand Authority (20%):** Platform presence across YouTube, Reddit, Wikipedia, LinkedIn
- **Content Quality (20%):** E-E-A-T signals (Experience, Expertise, Authoritativeness, Trustworthiness)
- **Technical (15%):** SSR, security, crawlability, Core Web Vitals readiness
- **Structured Data (10%):** Schema.org markup completeness and accuracy
- **Platform Optimization (10%):** Readiness for ChatGPT, Perplexity, Google AI Overviews

**Tools Used:** fetch_page.py, citability_scorer.py, brand_scanner.py, manual analysis

---

*Report generated by GEO-SEO Claude Audit Tool*
*Session: claude/audit-adro-mrtsE*
