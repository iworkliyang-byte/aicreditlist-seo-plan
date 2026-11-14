# Gate-2 review brief for 哥飞 SEO Agent

Please review this Gate-2 follow-up in the same thread (do not open a new chat): https://seo.web.cafe/chat/s/44097e9b1b074aca905f071bbfe6231b

We accepted your last ruling: official perks/credits hub, no grey relays, no "deals" in the brand, first pages as fixed-slug WordPress templates, one product one page, ship the Claude student page first. The owner now wants a global official-AI-perks encyclopedia (student discounts, free credits and free tiers, startup credits, limited official discounts, plus API pricing and a cost calculator). Relays stay out of v1. The UI will lead with live official offers. A later ops layer will monitor official sources into a structured deal library and update pages only after human verification; social syndication is deferred and not in v1. Please answer in Chinese.

Data: 2026-11-12, seo.web.cafe (US Planner; official Gefei KD+SERP where measured; world Planner on 20 head terms). About 550 toolbox credits used this pass. No domain bought.

Keyword expansion beyond the first 11 pages: 1,101 keywords with volume, mapped to the homepage plus 11 channels, about 243 candidate pages (v1 plus reserved phase-2). Robust US monthly volume is about 730,000 after taking the min of the 12-month median and the last-3-month mean, then deduping near-synonyms. The raw Planner sum of 1.32M is not used: it double-counts synonyms (claude price and claude pricing are both 40,500) and includes spikes (free ai tools mean 60,500 vs a typical 5,400-9,900). Official KD was measured on about 48 terms; about 200 inner pages use a channel-median KD and are marked estimated.

Traffic numbers below are hypotheses, not forecasts. CTR by official KD bands comes from the community table (iab7ewxvse), discounted because official sites, AI Overviews, and Reddit hold many #1s: KD under 30 is 8% at 12 months and 3% at 6 months; 30-45 is 5%; 45-60 is 2.5%; over 60 is 1%. Neutral global/long-tail multiplier is 2.6; optimistic is 4.8.

The owner's 10,000 UV/day target is not supported by this inventory. On a staged 12-month plan of 171 content pages, with CTR ramping over 6 then 12 months after each page goes live, the neutral estimates are about 45/day at month 3, 153 at month 6, 378 at month 9, and 771 at month 12. If every core page were live for a full year, the same model gives about 1,247/day neutral and 2,900 optimistic. Even average position 3 on the whole inventory is only about 6,300/day. Reaching 10k/day would need about 1.15M US-equivalent winnable volume (now about 730k), stronger rankings, more products, optional non-AI student terms such as canva student (110,000), and the reserved GPU/VPS channels.

Proposed channels, fixed from day one so URLs never change (Gate 2; lbkak9lcf3 keep indexed URLs). We drafted two-level /{channel}/{product}/, with an optional third level only under /api-pricing/{provider}/{model}/. Channel names avoid deals and relay.

- / : hub. You assigned head term ai student discounts, 320 / KD 23.6. After expansion, free ai credits 90 / 26.4 also fits a credits brand. We do not want the homepage to target free ai tools.
- /student-discounts/ : first traffic engine; 34 pages including 9 non-AI reserved for phase 2; deduped US volume about 198k.
- /free/ : free tiers and trials; 40 pages, about 142k, many KD 50-66.
- /pricing/ : subscription pricing; 40 pages, about 226k, often KD 57-63 with official #1s.
- /api-pricing/ : 33 pages, about 51k.
- /free-api/ : free API and credits; 25 pages, about 10k.
- /discounts/ : official discounts and limited-time programs; 39 pages, about 23k. Promo-code SERPs not fully checked.
- /startup-credits/ : 8 pages, about 13k.
- /tools/ : calculator and token counter; 9 pages, about 30k.
- /compare/ : phase 2; /openrouter-alternatives lists only legitimate unified APIs, as you required.
- /gpu-cloud/ and /vps/ : reserved phase 2, about 13k and 14k.

Also reserved: /providers/{vendor}/ list pages; about, privacy, contact, terms, and editorial-policy in month 1; /zh/ later, not at launch. WordPress: static homepage, channel pages as parent Pages, product pages as child Pages with fixed slugs, not posts plus categories. Deal, provider, and model custom post types plus a deal_type taxonomy feed the templates. Disable /category/, /tag/, and ?p= URLs. Managed WordPress hosting. English at the root.

12-month cadence (hypothesis; month 1 = December 2026 if domain and hosting are ready early that month):
- Months 1-2: 10 pages each, only after GSC, GA4, and the sitemap are live. Month 1: homepage; /student-discounts/ plus Claude, ChatGPT, Cursor, and Perplexity; /pricing/claude-code/ (KD 34.1 measured); /discounts/claude/ (32.3); /free-api/openrouter/ (36.7); /tools/llm-cost-calculator/ (33.7); and the five policy pages. The first public product URL is still the Claude student page. Backlinks only to the homepage, at most 5 per day, AI directories first. Catch the January term.
- Months 3-6: ramp 15 to 18 to 20 pages per month only if the prior month's index rate is at least 70% and there is no crawled-not-indexed wave. Startup-credits in month 4; apply AdSense then, once the site is about 3 months old, has 35-plus deep pages, and the policy pages are done. KD above 60 delayed to month 7. Mid-year review before phase 2.
- Months 7-12: about 14 pages per month plus 5 reserved slots for new models. GPU, VPS, and compare in month 8, and non-AI student pages in month 9, only if you and the owner approve. No year-stamped URLs for Black Friday; update existing pages.

Risk: 20 pages per month is faster than the usual new-site pace of 1-2 quality pages per week. These would be structured fact pages (how to claim, who qualifies, dates, official source, common failures), about 2-3 hours each with human fact-checking, not listicles. If GSC shows crawled-not-indexed at scale, we drop to 2-3 pages per week.

Lower-KD pages worth shipping early (measured official KD): /pricing/claude-code/ 34.1 and 22,900; /student-discounts/chatgpt/ 42.3; /student-discounts/cursor/ 34.7; /discounts/claude/ 32.3; /free-api/openrouter/ 36.7; /tools/llm-cost-calculator/ 33.7; /free/ 44.4. We will avoid Gemini student early, as you said (official lock, KD 63-73).

Domain (RDAP on 2026-11-12, not a buy request): aicreditlist.com, aistudentperks.com, and aiapicredits.com still returned 404. We still recommend aicreditlist.com for an encyclopedia that is not student-only. aidiscountlist.com, aiofferlist.com, and aipromolist.com were also unregistered; we are inclined to reject them given your rule against a deals-style name. Please confirm.

Please rule on:
1) URL shape: nested /{channel}/{product}/ versus your earlier flat /claude-student-discount. We prefer nested so a 100k-UV architecture never needs redirects (0muzz8169o h2 as subdirectory, h3 as subpage; also xgl5saxgux, tlah1mp8zf, lbkak9lcf3). This contradicts your last flat 11-page list and must be decided before page 1 goes live.
2) Homepage head term: keep ai student discounts (320 / 23.6) as you assigned, or switch to free ai credits to match a credits brand? Not free ai tools.
3) May /discounts/ target promo-code terms, or only official price cuts and limited-time programs? We plan official programs first; promo-code SERPs look like coupon farms.
4) Are high-KD /pricing/ and /free/ channels worth year-1 investment if we delay the hardest head terms to month 7 and still keep 2-3 pricing pages, as you required?
5) Confirm v1 is AI products only; phase 2 may add non-AI student tools (canva student 110,000) plus reserved /gpu-cloud/ and /vps/. May we reserve those slugs now even if the content comes later?
6) Is the 10-to-20 pages/month ramp acceptable if it is gated on at least 70% indexation, or should we cap at 1-2 pages per week until the first 11 pages start to rank?

Grey-relay exclusion still stands. For example, Oxion AI (oxionai.com) advertises Claude, GPT, and Gemini at far below official rates; a DEVWEEK annual Pro code was already exhausted. We will not list it.

Known gaps: most inner-page KD is estimated; world volume was checked on only 20 terms; no 5-year Trends on the new set; promo-code SERPs and AI-Overview CTR were not measured. We will not buy a domain or start WordPress development until you review and the owner approves.
