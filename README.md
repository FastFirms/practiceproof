# Practice Proof — Site for Review

15 self-contained HTML pages, single design system, ready to review.

## How to review

1. Unzip the file anywhere.
2. Open `index.html` in any modern browser (no server required).
3. Navigate the site as a visitor would — all internal links work locally.

Fonts load from Google Fonts (Newsreader + Hanken Grotesk).

## Design system

**Palette**
- `#BAD6FD` light blue — header section (top of page through the scrolling logo strip)
- `#FAF9F6` warm off-white — main content sections
- `#FFFFFF` pure white — alternating sections and raised card surfaces
- `#FE5429` orange — every button, with black text
- Text colour: **black** on every surface

**Typography**
- Newsreader serif — headlines (h1–h4, blockquotes, big stats)
- Hanken Grotesk sans — body, navigation, buttons

**Visual rhythm**
- Every other section in `<main>` flips between off-white and pure white so long pages have natural rest points
- The blue header section is preserved across this rhythm

## Site map

| Page | Purpose |
|---|---|
| `index.html` | Homepage |
| `resources.html` | Hub for guides, tools, the audit offer |
| `blog.html` | Blog index |
| `website-first-impressions.html` | Blog post |
| `seo-vs-ai-search.html` | Blog post |
| `storybrand-for-practices.html` | Blog post |
| `law-firm-marketing.html` | Legal industry landing page |
| `healthcare-marketing.html` | Healthcare industry landing page |
| `financial-services-marketing.html` | Financial services landing page |
| `strategy-brand.html` | Service pillar — strategy, brand, positioning |
| `website-design.html` | Service pillar — websites (deepest, ~2,600 words with cited stats) |
| `content-creative.html` | Service pillar — content, writing, design, video |
| `advertising-demand.html` | Service pillar — paid media, email, social, referral |
| `ai-technology.html` | Service pillar — AI, automation, chatbots |
| `software-tracking.html` | Service pillar — CRM, payments, tracking |

## Technical foundations

- Semantic HTML5; one `<h1>` per page
- JSON-LD structured data on every page (`Service`, `BreadcrumbList`, `FAQPage`, `BlogPosting`, etc.)
- Unique title, meta description, canonical URL, Open Graph and Twitter tags per page
- WCAG 2.2 AA — every contrast pair verified (black on light blue 14:1, black on off-white 19:1, black on orange 6.5:1)
- Mobile-first responsive, tested to 380px
- No frameworks — vanilla JS, deferred, minimal
- `prefers-reduced-motion` respected
- Keyboard-accessible industry tabs and FAQ accordions

## What's still a placeholder

- All images are labelled dashed-border placeholders — ready for real photography
- The PracticeRanker URL on `software-tracking.html` is currently `https://practiceranker.com` placeholder
- Proof / results sections on service pages have marked placeholder lines pending real client data
- Three blog post stubs are shown as "Coming soon" on the blog index
- Cited statistics only exist on `website-design.html` so far; the other five service pages can be brought to the same standard

