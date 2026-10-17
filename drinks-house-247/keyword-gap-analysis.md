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
   ✅ Done 16 Oct 2026: Christmas → `Christmas Gifts Delivered in London | Drinks House 247`; Corporate → `Corporate Gifts London | Same Day | Drinks House 247`. The landing page is also created as an unpublished draft in Shopify.
3. **Consolidate the "near me / 24 hour" pages.** Pick one winner per phrase and 301-redirect the rest
   (start with `alcohol-delivery-24-hours-1` → `alcohol-delivery-24-hours` and
   `wine-and-champagne-delivery-in-london-1` → `wine-and-champagne-delivery-in-london`).
4. **Fix or retire the unpublished duplicates:** `champagne-same-day`, `champagne-delivery`, `alcohol-delivery-areas` and others.
   Either publish `alcohol-delivery-areas` as the hyper-local hub (cluster 11) or remove it.
5. **Restore the Search Console data feed** (Supermetrics subscription, or connect Search Console directly) and re-run this analysis with real query data in about 4 weeks to measure the new page.

## 5. Change log: 16 Oct 2026 (live in Shopify)

| Change | Detail |
|---|---|
| Page published | `/pages/gifts-delivered-london`. Added free gift message, 4pm business cut-off, area-page links and a "More gift ideas & guides" block |
| Main menu | Gifts & Hampers → Send a Gift: "Same-Day Gift Delivery London" (was → `/collections/alcohol-gift-sets`) is now **"Gifts Delivered in London" → new page**. Every other item is unchanged and verified |
| Footer "Gift by Occasion" | New first item "Gifts Delivered in London"; "Christmas Gifts " renamed to "Christmas Gifts London" |
| Collection descriptions (link to page appended, existing text kept) | christmas-gifts, corporate-gifts, alcohol-gift-sets, birthday-gifts, champagne-gifts (link inside the "every occasion" paragraph), gifts-hampers |
| Page links re-pointed | `send-gift-uk` ("Same-Day Gift Delivery London" section) and `alcohol-delivery-as-a-gift` ("Send a Gift Same Day in London" H2 and a new in-text link) |
| SEO titles | Christmas: `Christmas Gifts Delivered in London \| Drinks House 247`; Corporate: `Corporate Gifts London \| Same Day \| Drinks House 247`; Birthday: `Birthday Gifts Delivered in London \| Drinks House 247`; Gift Hampers: `Luxury Gift Hampers London \| Same Day \| Drinks House 247` |

### Issue found, not yet fixed
`/pages/alcohol-delivery-areas` is **unpublished**, but the main menu (twice) and the footer link to it,
so those site-wide links probably show a 404. Fix: review and publish it, or re-point those three menu items.

## 6. Change log: Caymus 2022 → 2023 (16 Oct 2026)

| Change | Detail |
|---|---|
| Caymus 2022 | Both variants set to "Deny" overselling and stock 0, so the product shows as sold out. The page stays live to keep its rankings |
| Caymus 2023 (draft) | Duplicated from the 2022 at the same prices (£139 bottle; £750.60 case of 6, compare-at £834) with the 2022 photo for now. New description (`caymus-2023-product-description.html`), handle `caymus-vineyards-cabernet-sauvignon-2023`, SEO title and description, and SKUs `CAYMUS-CABSAUV2023-75CL` / `-CASE6` |
| Caymus 2023 live | Stock: 48 bottles and 8 cases of 6. Set Active and published to Online Store, Google & YouTube, Facebook & Instagram and Pinterest |
| Cross-links | Caymus hub page: 2023 replaces 2022 in the hero, stats, timeline, carousel, charts, chooser, FAQ, JSON-LD and SEO title/description ("Vintages 1993–2023"). 1993/1995/2003 product pages: "More Caymus Vintages" now links to the 2023. 2022 product page: case banner replaced with a "Sold out, the 2023 is now available" banner and link. Collections cabernet-sauvignon, napa-valley and wines-from-usa now say 1993 to 2023 |

## 7. Change log: Viña Tondonia Reserva 2011 → 2014 (16 Oct 2026)

| Change | Detail |
|---|---|
| Tondonia Reserva 2011 75cl (`/products/vinos-finos-de-rioja`) | Stock set from 1 to 0, with overselling off, so it shows as sold out. The page stays live |
| Tondonia Reserva 2014 75cl (draft) | Duplicated from the 2011 with the 2011 photo. Price £138, SKU `TONDONIA-RESERVA14-75CL`, handle `lopez-de-heredia-vina-tondonia-tinto-reserva-2014-75cl`. New description (`tondonia-reserva-2014-product-description.html`: 95 pts Wine Advocate, 2014 tasting notes and blend, a 2011 comparison question, and links to Cubillo 2014 and the Rioja collection) plus a new SEO title and description |
| Tondonia 2014 live | Stock: 12. Set Active and published to Online Store, Google & YouTube, Facebook & Instagram and Pinterest. It now sits in the Fine Wine £100+ collection instead of the under-£100 collections |

## 8. Caviar hampers hub, merged into /pages/caviar-hampers (17 Oct 2026)

The new hub was first published at `/pages/caviar-champagne-hampers-london`. Then we found the existing live page `/pages/caviar-hampers`, which the main menu and footer already link to and which targets the same searches. The two were merged into the established URL (`caviar-hampers.html`).

| Element | Value |
|---|---|
| Page | `/pages/caviar-hampers` (old body backed up before the replacement) |
| SEO title | `Caviar Hampers London \| Champagne & Caviar Same Day \| Drinks House 247` |
| Sections | Hero; stats; Champagne & caviar hamper carousel (9) and vodka/tequila carousel (3), all with Add to Cart; comparison table (12); gift box colours (kept from the old page); caviar species guide; 30g starting-price chart; caviar tin carousel (14); chooser; serving guide; corporate & event orders (kept from the old page); About plus area links; 8 FAQs |
| Links out | Beluga, Oscietra and how-to-serve guides; same-day caviar delivery; caviar delivery collections; Mayfair, Knightsbridge, Chelsea and Canary Wharf caviar pages; corporate caviar gifts |
| Duplicate | `/pages/caviar-champagne-hampers-london` unpublished, with a 301 redirect to `/pages/caviar-hampers` |
| Collection SEO | caviar-champagne-gift-in-uk is now `Caviar & Champagne Gifts London \| Same Day Delivery \| Drinks House 247`, and its description links to the hub |
| Cross-links | Collections gifts-hampers, corporate-gifts and caviar-champagne-gift-in-uk; Dom Pérignon x Damien Hirst page; the 12 hamper product pages. The main menu, footer and gifts-delivered-london already linked to /pages/caviar-hampers |
| Left out | Cipriani Bellini Hamper (out of stock), Croe Sevruga (draft) |

## 9. "Gifts under £X" collection rules (17 Oct 2026)

Correction: `wines-under-100` is **"Gifts under £100"**, not a wine collection, so caviar and chocolate rightly belong there. The real problem was non-gift products leaking into the four budget gift collections. Every collection kept its existing price rules and gained the same type exclusions: beers, Mixers, Cigarettes, Extras (lighters, crisps, ice, painkillers), tablets (supplements), Soft Drink, cider, mw_hidden_cart_fee (service fee). "Gifts under £200" had no minimum price, so it got a £90 minimum to match the overlapping-band pattern of the others.

| Collection | Price rule | Products before | After |
|---|---|---|---|
| Gifts under £50 (`wines-under-50`) | £26–£50 | 274 | 254 |
| Gifts under £100 (`wines-under-100`) | £45–£100 | 455 | 453 |
| Gifts under £200 (`wine-under-200`) | was <£200, now £90–£200 | 1,069 | 425 |
| Gifts under £500 (`wine-under-500`) | £68–£500 | 650 | 650 |

**Handle rename (17 Oct 2026):** `wines-under-100` is now `gifts-under-100`, with a Shopify 301 redirect `/collections/wines-under-100` → `/collections/gifts-under-100`. The "Shop by budget" links in the five sister collections (wines-under-50, wine-under-200, wine-under-500, gifts-under-1000, gifts-over-1000) now point to the new URL. No menu linked to the old one. The other budget collections still have wine-style handles (`wines-under-50`, `wine-under-200`, `wine-under-500`).

**More handle renames (17 Oct 2026):** `wines-under-50` → `gifts-under-50`, `wine-under-200` → `gifts-under-200`, `wine-under-500` → `gifts-under-500`, each with a Shopify 301 redirect. All four budget collections now use `gifts-under-*` handles. "Shop by budget" links in the budget collections and the "Gifts by Budget" grid on `/pages/gifts-delivered-london` now point to the new URLs.

**Caviar Gifts & Hampers collection (17 Oct 2026):** the SEO title changed from `Caviar Gifts & Hampers | London & UK | Drinks House 247` to `Caviar Gift Sets | Delivered Same Day in London | Drinks House 247`, with a new meta description. The visible name and existing description are unchanged, and a link to `/pages/caviar-hampers` was added. Search roles in the caviar cluster:

| URL | Targets |
|---|---|
| /pages/caviar-hampers | "caviar hampers London", comparison and caviar guide |
| /collections/caviar-gifts-hampers | "caviar gift sets" (shop grid) |
| /collections/caviar-champagne-gift-in-uk | "caviar & Champagne gifts London" |
| /collections/caviar-delivery-london | "caviar delivery London" (tins) |
Links to the old `wines-under-*`/`wine-under-*` paths were also updated in `alcohol-gift-sets` ("Shopping to a budget?" paragraph). A scan of all 215 collections and the gifts-delivered-london page found no old paths left; the redirects cover any other links.
