# Drinks House 247: Keyword Gap Analysis (London Gifts)

_Prepared 16 Oct 2026. Sources: live Shopify store (49 pages, ~150 collections, 180-day sales), web SERP checks._

> **Data limitation:** The Search Console connection (via Supermetrics) returned
> `TRIAL_EXPIRED` (trial ended 20 Aug 2026), so this analysis has **no real
> impression, click or position data**. Priorities below come from search intent,
> what the store already has, and sales. They are not search-volume estimates.
> Re-run with Search Console data once the connection is restored.

## 1. What the site targets today

**Pages (Shopify `/pages/`)** are almost all one theme: *"alcohol / wine delivery near me / 24 hour"*.

- About 20 published pages target overlapping "near me", "24 hour" and "same day" phrases, for example
  `alcohol-24-hour-delivery`, `alcohol-delivery-24-hours`, `alcohol-delivery-24-hours-1`,
  `24-hour-alcohol-delivery-service`, `alcohol-24-hour-near-me`, `alcohol-shop-near-me` and
  `your-search-for-alcohol-shop-near-me-ends-here`. These pages compete with each other for the same
  searches, which splits ranking signals between them.
- Two near-identical pages: `wine-and-champagne-delivery-in-london` and `wine-and-champagne-delivery-in-london-1`.
- Gift pages are **UK-wide or generic**: `send-gift-uk`, `send-a-champagne-gift`,
  `alcohol-delivery-as-a-gift` and `uk-champagne-delivery`. `champagne-same-day` ("Send Champagne Gift to Someone") is **unpublished**.

**Collections:** product-type collections are well localised ("Wine Delivery in London",
"Gin Delivery London" and so on). The **gift and occasion collections are not localised**:
`birthday-gifts`, `christmas-gifts`, `corporate-gifts`, `anniversary-gifts`, `thank-you-gifts`,
`congratulations-gifts`, `wedding-gifts`, `retirement-gifts-l`, `whisky-gifts`, `champagne-flute-gift-sets` and others.
The only localised gift collection is `gifts-hampers` ("Same-Day London Delivery: Luxury Wine & Champagne Gift Hampers").

**Sales (last 180 days):** of £20.7k net across the top 25 products, nearly all is **gift-led**:
Veuve Clicquot, Moët, Dom Pérignon in gift boxes, caviar gift sets, Clase Azul, Hibiki and Macallan.
Buyers are already using the store for gifts, but there is no London gift hub to capture that search demand.

## 2. Keyword gaps

| # | Keyword cluster (example phrases) | Intent | Current coverage | Gap | Priority |
|---|---|---|---|---|---|
| 1 | **gifts delivered London**, gift delivery London, send a gift London, same day gift delivery London | Transactional, local | None. Gift pages say "UK" | **No page owns this.** Highest-value gap | **P1** |
| 2 | alcohol gifts delivered London, alcohol gift delivery London, drinks gifts London | Transactional | `alcohol-delivery-as-a-gift` (generic, no London) | Weak or partial | **P1** |
| 3 | champagne gift delivery London, send champagne London same day | Transactional | Collection `champagne-gifts` (has "London" in title); `champagne-same-day` page unpublished | Partial; needs a page and internal links | P1 |
| 4 | **Christmas gifts delivered London**, corporate Christmas gifts London | Seasonal, now peaking (Oct to Dec) | `christmas-gifts` collection, no London term or copy | **Time-critical** | **P1** |
| 5 | corporate gifts London, business gifts delivered London, client gifts London | B2B, high order value | `corporate-gifts` collection, not localised | Missing London term and B2B copy | P1 |
| 6 | birthday gifts delivered London, same day birthday gift London | Transactional | `birthday-gifts`, not localised | Missing | P2 |
| 7 | gift hampers London, luxury hampers delivered London, champagne hamper London | Transactional | `gifts-hampers` (good title) | Needs supporting links and FAQ | P2 |
| 8 | late night / 24 hour gift delivery London, last minute gifts London | Urgent | None | **Unique angle** (24/7, 30 to 45 min) that hamper retailers can't match | P2 |
| 9 | whisky gifts London, tequila gift London, caviar gift London | Transactional | `whisky-gifts`, `caviar-champagne-gift-in-uk` (says "UK") | Missing London term | P3 |
| 10 | anniversary / congratulations / thank you / new job / retirement gifts London | Long tail | Collections exist, not localised | Missing | P3 |
| 11 | gifts delivered Mayfair / Chelsea / Kensington / Canary Wharf / City of London | Hyper-local | `alcohol-delivery-areas` page is **unpublished** | Missing | P3 |

### Competitor read (SERP spot-checks)
- **The Finest Bubble** owns "same day champagne delivery London" with a 2-hour window.
- **Hampers.com, John Lewis and Fortnum's** win "gift hampers" with next-day or named-day delivery, not same-hour.
- Third-party articles (e-architect, signalscv) already describe Drinks House 247 as a same-day London champagne gift option, so the site has some brand authority to build on.
- **Drinks House 247's edge:** 24/7 and 30 to 45 minute delivery. Gift competitors can't offer "last-minute" or "late-night" gift delivery, so the page leans on that.

## 3. What was built

`gifts-delivered-london.html` is a landing page for **`/pages/gifts-delivered-london`** targeting clusters 1, 2, 4, 5, 6, 7 and 8, with internal links to every existing gift and occasion collection (clusters 3, 9 and 10).

| Element | Value |
|---|---|
| URL handle | `gifts-delivered-london` |
| SEO title (60 chars) | `Gifts Delivered in London \| Same-Day 24/7 \| Drinks House 247` |
| Meta description | `Send alcohol gifts across London in 30–45 minutes, 24/7. Champagne, hampers, whisky, caviar & chocolate gifts for birthdays, Christmas & corporate clients.` |
| H1 | Gifts Delivered in London: Same Day, Day or Night |
| Schema | `FAQPage` and `BreadcrumbList` JSON-LD |

## 4. Next steps (in order)

1. **Publish the page** and add it to the main menu ("Gifts") and footer. Link to it from the homepage, `send-gift-uk`, `alcohol-delivery-as-a-gift` and `gifts-hampers`, using anchor text such as "gifts delivered in London".
2. **Localise the occasion collection SEO titles** (title tag only; visible names can stay), for example
   `Christmas Gifts Delivered in London | Drinks House 247` and `Corporate Gifts London | Drinks House 247`.
   Do Christmas and Corporate this week, before the seasonal peak.
3. **Consolidate the "near me / 24 hour" pages.** Pick one winner per phrase and 301-redirect the rest
   (start with `alcohol-delivery-24-hours-1` → `alcohol-delivery-24-hours` and
   `wine-and-champagne-delivery-in-london-1` → `wine-and-champagne-delivery-in-london`).
4. **Fix or retire the unpublished duplicates:** `champagne-same-day`, `champagne-delivery`, `alcohol-delivery-areas` and others.
   Either publish `alcohol-delivery-areas` as the hyper-local hub (cluster 11) or remove it.
5. **Restore the Search Console data feed** (Supermetrics subscription, or connect Search Console directly) and re-run this analysis with real query data in about 4 weeks to measure the new page.
