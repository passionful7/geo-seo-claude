# GEO + SEO Audit Report: reclop.com

**Audit Date:** March 15, 2026
**Domain:** reclop.com
**Business Type:** E-commerce (Women's Fashion & Clothing)
**Platform:** Shopify (roovello.myshopify.com)
**Tagline:** None identified

---

## GEO Score: 12/100

| Category | Score | Weight | Weighted |
|---|---|---|---|
| AI Citability & Visibility | 8/100 | 25% | 2.0 |
| Brand Authority Signals | 8/100 | 20% | 1.6 |
| Content Quality & E-E-A-T | 10/100 | 20% | 2.0 |
| Technical Foundations | 40/100 | 15% | 6.0 |
| Structured Data | 10/100 | 10% | 1.0 |
| Platform Optimization | 5/100 | 10% | 0.5 |
| **Composite GEO Score** | | | **13/100** |

**Grade: F** — Critically low across all GEO dimensions. The site is essentially invisible to AI search engines.

---

## Executive Summary

RECLOP is a women's fashion e-commerce store selling dresses, tops, bottoms, outerwear, jumpsuits, and accessories at low price points (~$33 USD). The site runs on Shopify but has **virtually no indexable text content** — pages render almost entirely via JavaScript with minimal server-side content. There is no llms.txt file, no blog content, no about page content, no customer reviews on third-party platforms, and only ~9 pages indexed by Google. The brand has zero editorial coverage, no Wikipedia/Wikidata presence, and no detectable Reddit mentions.

**The core problem:** RECLOP has no content, no brand story, no authority signals, and no differentiation that AI engines can discover, cite, or reference. The site is a generic Shopify storefront with no discoverability layer.

---

## 1. AI Citability & Visibility (8/100)

### Homepage Citability: ~5/100 (Grade F)
- Homepage content is **almost entirely JavaScript-rendered** — minimal server-side text
- Navigation labels ("Shop All Clothing", "Dresses", "Tops") are the only indexable text
- **0 citable passages** — no descriptive content, no brand messaging, no product copy
- Estimated word count: **<50 words** of meaningful indexable text on homepage

### Content Page Citability
- **About Us page:** Exists at `/pages/about-us` but **contains no extractable text content** — page body is empty or JS-rendered
- **Help Center:** Exists at `/pages/help-center` but no FAQ content extractable from HTML
- **Shipping Policy:** Page exists but policy text is not in server-rendered HTML
- **Blog:** Returns **404** — no blog exists at all
- **FAQ page:** Returns **404** — does not exist
- **Return/Exchange policy page:** Returns **404**

### Key Citability Issues
- **Zero content pages with extractable text** — every page is either empty, 404, or JS-only
- **No blog content whatsoever** — zero articles, zero thought leadership
- **No product descriptions visible** in server-rendered HTML
- **No brand story, mission, or values** anywhere on the site
- **Nothing for AI engines to quote, cite, or reference**

### AI Crawler Access: 30/100
- **No AI-specific crawler directives** in robots.txt
- No GPTBot, ClaudeBot, PerplexityBot, OAI-SearchBot, or Google-Extended rules
- All AI crawlers fall under the generic `User-agent: *` rules
- Generic rules block: admin, cart, checkout, orders, account, search, and filtered/sorted pages
- **Nutch** is not mentioned (unlike many Shopify stores)
- AhrefsBot and AhrefsSiteAudit blocked with crawl delay
- MJ12bot blocked with crawl delay
- Contains policy: "Automated scraping, 'buy-for-me' agents, or any end-to-end flow that completes payment without a final human review step is not permitted."

### llms.txt: Missing (0/100)
- **No llms.txt file exists** (404 response)
- No controlled narrative for AI engines
- No structured brand information for LLM consumption

---

## 2. Brand Authority Signals (8/100)

### Platform Presence Assessment

| Platform | Status | Impact |
|---|---|---|
| Instagram | Claimed (link placeholder "#") | Unverified — social links are placeholder URLs |
| TikTok | Claimed (link placeholder "#") | Unverified — social links are placeholder URLs |
| Facebook | Claimed (link placeholder "#") | Unverified — social links are placeholder URLs |
| Pinterest | Claimed (link placeholder "#") | Unverified — social links are placeholder URLs |
| YouTube | Not detected | Missing |
| Reddit | Not detected | Missing — high correlation with AI visibility |
| Wikipedia | Not detected | No article — limits entity recognition |
| Wikidata | Not detected | No entry — hurts AI entity understanding |
| LinkedIn | Not detected | No company page |
| Twitter/X | Not detected | No presence |

### Critical Issues
- **All social media links are placeholder "#" URLs** — not linked to actual profiles
- **Zero third-party reviews** — no Trustpilot, Sitejabber, BBB, or Google reviews found
- **Zero press/media mentions** found anywhere online
- **Zero editorial coverage** — no fashion blog mentions, no influencer features
- **Only ~9 pages indexed by Google** — extremely small footprint for an e-commerce site
- **Brand confusion risk** — "RE:CLO" and "Reclo" are similar brands in the same fashion space
- **No external backlinks from authoritative sources** detected
- **Myshopify subdomain visible** (roovello.myshopify.com) — suggests early-stage or template store

---

## 3. Content Quality & E-E-A-T (10/100)

### Experience Signals: None
- No customer testimonials anywhere on the site
- No customer photos or UGC (user-generated content)
- No styling guides or outfit inspiration content
- No "real customer" social proof
- Judge.me reviews app installed but no visible review counts

### Expertise Signals: None
- No fashion expertise demonstrated
- No styling advice or trend analysis
- No size guides with detailed measurements
- No fabric/material educational content
- No "how to style" or "how to care for" content

### Authority Signals: None
- Zero press mentions or media features
- No awards or recognitions
- No designer or brand partnerships highlighted
- No fashion credentials or background shared
- No industry affiliations

### Trustworthiness Signals: Very Low
- HTTPS enabled (Shopify default)
- No visible customer reviews on any product page
- Privacy policy page returns 404
- Return/exchange policy page returns 404
- Terms of service page content not server-rendered
- **No physical address** found anywhere
- **No contact email** visible
- **No phone number** visible
- Company legal identity unclear (myshopify handle: "roovello")

### Content Gaps
- **No About Us content** — page exists but body is empty
- **No blog at all** — 404 on /blogs
- **No FAQ page** — 404
- **No size guide** — critical for fashion e-commerce
- **No product descriptions** in server-rendered HTML
- **No collection descriptions** — category pages have zero descriptive text
- **No brand story or mission statement**
- **No team or founder information**

---

## 4. Technical Foundations (40/100)

### Strengths
| Check | Status |
|---|---|
| HTTPS | Yes — Shopify SSL |
| Server-Side Rendering | Partial — Shopify SSR but content is JS-dependent |
| Mobile Responsive | Yes — viewport meta tag present |
| Sitemap | Yes — includes products, pages, collections, blogs |
| Multi-language | Yes — English + Spanish sitemaps |
| Shopify CDN | Yes — standard Shopify infrastructure |

### Issues
| Check | Status | Severity |
|---|---|---|
| Meta description (homepage) | **Not detected** | Critical |
| About page content | **Empty body** | Critical |
| Blog section | **404 — does not exist** | Critical |
| FAQ page | **404 — does not exist** | Critical |
| Return policy page | **404 — does not exist** | High |
| Privacy policy page | **404 — does not exist** | High |
| Social media links | **All placeholder "#" URLs** | High |
| Image alt text | Not verifiable (JS-rendered) | Likely High |
| Collection descriptions | **Missing on all collection pages** | High |
| Product page content | **Not server-rendered** | Medium |
| OG image (homepage) | Not detected | Medium |

### Sitemap Analysis
- 8 sub-sitemaps: 4 English + 4 Spanish (products, pages, collections, blogs)
- Product sitemap references product range from ID 8735632851122 to 8763696251058
- Pages, collections, and blogs sitemaps included
- Blog sitemap exists in sitemap but `/blogs` returns 404 — **sitemap/reality mismatch**

### robots.txt Assessment
- Standard Shopify defaults — blocks admin, cart, checkout, orders
- Blocks sorted and heavily filtered collection pages (good)
- AhrefsBot/AhrefsSiteAudit: blocked
- MJ12bot: blocked
- Pinterest: specific rules
- Sitemap directive present: `https://reclop.com/sitemap.xml`
- Anti-bot policy stated in robots.txt

---

## 5. Structured Data (10/100)

### Existing Schema Markup
- **Shopify merchant configuration** detected with shop ID 65792082098
- Currency: USD, Country: US
- **No Organization schema detected** in server-rendered HTML
- **No Product schema detected** in server-rendered HTML (likely JS-injected)
- **No WebSite schema** with SearchAction detected

### Missing Schema Types
- **Organization** — no company schema with name, logo, sameAs, description
- **LocalBusiness** — no business type schema
- **Product** — not in server-rendered HTML (AI crawlers may miss JS-injected schema)
- **FAQPage** — FAQ page doesn't exist
- **Article/BlogPosting** — blog doesn't exist
- **BreadcrumbList** — no breadcrumb schema
- **Review/AggregateRating** — no reviews to markup
- **CollectionPage** — no collection schema
- **WebSite** — no site-level schema with search action

---

## 6. Platform Optimization (5/100)

### ChatGPT Readiness: None
- Zero extractable content for ChatGPT to reference
- No FAQ content that maps to user questions
- No product descriptions AI can summarize
- No brand story to communicate
- No comparison or recommendation-style content

### Perplexity Readiness: None
- No fact-dense passages for citation
- No publication dates (no blog exists)
- No author attribution
- No source-quality signals whatsoever
- Zero domain authority

### Google AI Overviews Readiness: None
- No featured-snippet-optimized content
- No definition blocks
- No specification lists
- No FAQ schema
- No meta description on homepage
- Minimal indexed pages (~9)

---

## Prioritized Action Plan

### Critical / Immediate (Week 1)

1. **Build a real About Us page** — Write 500+ words covering: who RECLOP is, founding story, mission, what makes the brand different, target customer, values. This is the #1 priority — the brand currently has zero identity online.

2. **Add homepage meta description** — Write 150-160 characters describing what RECLOP sells and its value proposition.
   - Suggested: "RECLOP offers trendy women's clothing including dresses, tops, bottoms, and outerwear. Shop affordable fashion with free US shipping."

3. **Fix social media links** — Replace all "#" placeholder URLs with actual social media profile URLs, or remove the links entirely.

4. **Create collection descriptions** — Write 100-200 word descriptions for each collection page (Dresses, Tops, Bottoms, Outerwear, etc.) explaining what the collection offers.

5. **Create shipping policy content** — Ensure the shipping policy page has actual rendered text content.

6. **Create return/exchange policy page** — Currently returns 404. This is a basic trust requirement.

7. **Create privacy policy page** — Currently returns 404. This is a legal requirement in most jurisdictions.

### Quick Wins (Weeks 2-3)

8. **Create llms.txt** — Provide AI engines with structured brand information:
   ```
   # RECLOP
   > RECLOP is an online women's fashion retailer offering affordable dresses,
   > tops, bottoms, outerwear, and accessories with free US shipping.

   ## Shop
   - [All Clothing](https://reclop.com/collections/all)
   - [Dresses](https://reclop.com/collections/dresses)
   - [New Arrivals](https://reclop.com/collections/new-in)
   - [Best Sellers](https://reclop.com/collections/best-sellers)

   ## Customer Service
   - [Help Center](https://reclop.com/pages/help-center)
   - [Contact Us](https://reclop.com/pages/contact-us)
   ```

9. **Add product descriptions** — Every product page needs at minimum 100 words of descriptive, server-rendered content covering: fabric, fit, occasions, care instructions, sizing.

10. **Create a FAQ page** — Cover common questions: shipping times, returns process, sizing, payment methods, order tracking. Implement FAQPage JSON-LD schema.

11. **Add Organization schema** — Implement JSON-LD with name, logo, description, sameAs (actual social URLs), url, contactPoint.

12. **Add image alt text** — Every product image needs descriptive alt text (e.g., "Women's black midi dress with mesh overlay" not "IMG_4532").

13. **Create a size guide page** — Essential for fashion e-commerce. Include measurements for each size across product categories.

### Medium-Term (1-2 months)

14. **Launch a blog** — Blog currently returns 404. Start publishing 2-4 posts per month:
    - Styling guides ("5 Ways to Style a Midi Dress")
    - Trend reports ("Spring 2026 Fashion Trends")
    - Fabric care guides
    - Outfit of the week features

15. **Add Product schema to product pages** — Ensure JSON-LD Product schema is server-rendered, not JS-injected. Include: name, description, image, price, availability, brand, material, aggregateRating.

16. **Build real social media presence** — The placeholder links suggest no active social accounts. Create and actively maintain Instagram, TikTok, and Pinterest accounts with regular posting.

17. **Collect and display customer reviews** — Configure Judge.me to actively collect reviews. Display them on product pages with Review schema markup.

18. **Add contact information** — Display a physical address (or at minimum city/country), email address, and response time on the Contact Us page.

### Strategic (2-6 months)

19. **Build third-party review presence** — Encourage customers to leave reviews on Google, Trustpilot, or Sitejabber. Zero external reviews is a major trust red flag.

20. **Earn editorial mentions** — Reach out to fashion bloggers, submit to "affordable fashion" roundups, pursue micro-influencer partnerships for backlink building.

21. **Create comparison/recommendation content** — "Best Dresses Under $50", "What to Wear to a Summer Wedding" — these are high-intent queries AI engines frequently answer.

22. **Resolve brand identity** — The myshopify handle is "roovello" but the brand is "RECLOP". Ensure consistent branding across all touchpoints. Consider whether this creates confusion for AI entity recognition.

23. **Expand Google index** — With only ~9 pages indexed, submit individual product page URLs via Google Search Console. Ensure product pages are crawlable and have unique content.

24. **Consider Wikidata entry** — Once the brand has sufficient external citations, create a Wikidata entry for entity recognition by AI systems.

---

## Key Findings Summary

### Critical Issues
1. **Zero extractable text content on any page** — pages are JS-rendered shells
2. **No blog exists** — /blogs returns 404
3. **No About Us content** — page body is empty
4. **No llms.txt file** — no AI-readable brand information
5. **All social media links are placeholder "#" URLs** — no real social presence linked
6. **Multiple policy pages return 404** (privacy, returns, FAQ)

### High Priority Issues
7. **Only ~9 pages indexed by Google** — almost invisible in search
8. **Zero third-party reviews anywhere online**
9. **Zero press or editorial mentions**
10. **No Organization or Product schema in server-rendered HTML**
11. **No collection descriptions** — category pages are content-free
12. **No meta description on homepage**
13. **Brand identity confusion** — "roovello" myshopify handle vs. "RECLOP" brand name

### Strengths to Build On
- Shopify infrastructure provides solid technical foundation
- Multi-language support (English + Spanish) via sitemap
- Judge.me reviews integration installed (needs activation/promotion)
- Comprehensive product category structure
- Sitemap properly configured with sub-sitemaps
- SSL/HTTPS enabled
- Free US shipping (competitive advantage worth promoting)
- Low price points (~$33) — affordable fashion angle for content marketing

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

**Tools Used:** WebFetch analysis, brand visibility research, manual technical audit

---

*Report generated by GEO-SEO Claude Audit Tool*
*Session: claude/audit-adro-mrtsE*
