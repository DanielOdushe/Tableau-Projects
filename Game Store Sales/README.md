# Game Store Overview — Global Sales Dashboard

## Web Preview
https://public.tableau.com/views/VideoGameSalesAnalysis_17603082192540/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Project Overview
This Tableau dashboard summarizes global video game sales across products, platforms, publishers, genres and time (1980–2020). It highlights where revenue concentrates, which platforms and publishers lead sales, genre demand, and how global sales changed over time. Use this write-up as the README for your GitHub repo — it contains the dashboard insights, technical notes, and reproducible steps.

**Data Source:** Global game-sales transactional / aggregated dataset (product, platform, publisher, genre, year, sales)  
**Tools Used:** Tableau Desktop / Tableau Reader  
**Date Range:** 1980 → 2020  
**Units:** Sales units use the same metric displayed on the dashboard (confirm in your data file — often millions of units or millions in revenue).

---

## Top-line KPIs (visible on dashboard)
- **Total Products:** 11,493  
- **Total Platforms:** 31  
- **Total Publishers:** 579  
- **Total Genres:** 12  
- **Start Date:** 1980  
- **End Date:** 2020

---

## Key Findings (concise, evidence-based)
1. **Sales growth and decline over time.** Global sales rise sharply from the late 1990s, climb to a clear peak in the mid-2000s, then fall off toward later years. The stacked area chart shows a concentrated peak period when platform-and-genre launches drove the highest global sales volumes.  
2. **Platform concentration.** A few platforms dominate lifetime sales. Shown values on the dashboard highlight X360 (≈969.6), PS3 (≈949.3), Wii (≈909.8), and DS (≈819.0) as the largest contributors. Platform market share varies by generation.  
3. **Publishers drive scale.** Top publishers account for the largest slices of overall sales. The top 10 publishers by sales on the dashboard (with displayed values) are:
   - Nintendo — 1,784  
   - Electronic Arts — 1,093  
   - Activision — 721  
   - Sony Computer Entertainment — 607  
   - Ubisoft — 474  
   - Take-Two Interactive — 399  
   - THQ — 340  
   - Konami Digital Entertainment — 279  
   - Sega — 271  
   - Namco Bandai Games — 254  
4. **Top-selling products are wildly uneven.** The Top 10 product list shows a handful of titles with very high cumulative sales; example values:
   - Wii Sports — 82.74  
   - Grand Theft Auto V — 55.92  
   - Super Mario Bros. — 45.31  
   - Tetris — 35.84  
   - Mario Kart Wii — 35.82  
   - Wii Sports Resort — 33.00  
   - Pokemon Red/Blue — 31.37  
   - Call of Duty: Modern Warfare — 30.83  
   - New Super Mario Bros. — 30.01  
   - Call of Duty: Black Ops — 29.40  
   These titles are platform-defining and often tied to bundled hardware (e.g., Wii Sports) or franchise strength.  
5. **Genre demand ranking.** Action is the largest-selling genre (1,723), followed by Sports (1,309), Shooter (1,026), Role-Playing (924), Platform (829), and Misc (798). Niche genres like Strategy (173) and Adventure (223) show lower absolute sales.  
6. **Cross-view signals.** The stacked area (by genre) + platform bubbles reveal that peaks in total sales align with specific successful platforms and high-selling titles — when a dominant platform and a few hit titles align, total sales spike.

---

## How to read each visual
- **Top KPI blocks (left column):** quick inventory counts and date range. Use these to confirm dataset scope before drilling deeper.  
- **Sales per Years and Genres (stacked area):** monthly/annual stacked area by genre. The height shows total sales; color bands show genre mix. Look for peaks and post-peak declines.  
- **Top 10 Platforms (bubble chart):** bubble size = global sales per platform; bubble color uses a sales zone scale (dashboard legend ranges approximately 81.9 → 969.6). Larger, darker bubbles indicate higher total sales.  
- **Top 10 Publishers (bar chart):** horizontal bars sorted by sales for easy rank and comparison.  
- **Top 10 Products (bar chart):** horizontal bars showing cumulative sales per title — useful to surface franchise hits.  
- **Sales by Genre (bar chart):** vertical bars with numeric sales above each bar; this gives a clear rank by genre.

