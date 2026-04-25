---
layout: page
title: ValueLens
description: A lightweight Chrome extension for comparing official Miu Miu US and Japan product pricing from the product page itself.
img: assets/img/project-valuelens-miumiu-demo.jpg
importance: 3
category: work
related_publications: false
---

ValueLens is a lightweight Chrome extension prototype for quick official-price comparison while browsing Miu Miu product pages.

Instead of switching across tabs, calculators, and notes, the extension injects a compact side panel directly into the product page and helps compare the official US and Japan pricing view for the same item.

Current prototype features:
- product-page overlay for `miumiu.com`
- current-region price parsing from the live page
- US / JP comparison workflow
- exchange-rate normalization
- simple assumptions for tax refund, sales tax, shipping, and markup
- manual fallback when the counterpart-region price is not automatically found

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-valuelens-miumiu-demo.jpg" title="ValueLens Miu Miu demo" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Real Miu Miu product-page screenshot with the ValueLens comparison panel.
</div>

The current direction is intentionally narrow: compare official Miu Miu US and Japan pricing first, make the workflow clean, and only expand after the matching logic becomes reliable.

Highlights:
- luxury-styled compact side panel
- focused comparison for official-region pricing rather than broad scraping
- built for quick screening instead of spreadsheet-heavy work
- product-oriented prototype with a narrow scope and clear workflow

Access:
- If you are interested in trying the extension, please contact me directly by email or LinkedIn.
- The code and package are not publicly linked from this page.

Notes:
- This is still a prototype and uses heuristic page parsing rather than an official commerce API.
- Cross-region matching is reliable only when the counterpart product page can be inferred correctly.
- The current version is intentionally limited to a narrow brand-and-region workflow before any broader expansion.
