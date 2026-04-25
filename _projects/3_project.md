---
layout: page
title: Tucson Zillow Value Lens
description: A bilingual Chrome extension that estimates future value, sale profit, and Tucson-specific housing signals directly on Zillow listing pages.
img: assets/img/project-tucson-zillow-value-lens-demo.jpg
importance: 3
category: work
related_publications: false
---

Tucson Zillow Value Lens is a Chrome extension prototype I built for faster housing screening while browsing Zillow listings in the Tucson area.

Instead of switching across spreadsheets, tax notes, and mortgage calculators, the extension injects a compact side panel directly into the Zillow page and estimates:

- future value scenarios for `2 / 3 / 4 / 5 / 10 / 20` years
- low / base / high sale-price range
- estimated sale profit and ROI after selling
- remaining mortgage balance and net sale proceeds
- optional FIRPTA withholding toggle for foreign sellers
- adjustable assumptions for down payment, mortgage rate, and appreciation potential

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-tucson-zillow-value-lens-demo.jpg" title="Tucson Zillow Value Lens demo" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Real Zillow listing screenshot with the Tucson Zillow Value Lens extension panel.
</div>

The current prototype is tailored for Tucson-area browsing and uses regional assumptions for neighborhoods and zip codes such as `85718`, `85750`, `85737`, `85704`, `85741`, `85742`, and `85749`.

Highlights:
- bilingual interface in English and Chinese
- compact side panel designed for quick listing comparison
- mortgage-aware profit estimation instead of raw appreciation only
- simple year selector to keep the interface clean
- designed as a practical SDE-style product prototype, not just a spreadsheet

Downloads:
- [Chrome extension package (ZIP)](/files/extensions/tucson-zillow-value-lens-extension.zip)

Notes:
- This is a prototype and uses a local heuristic parser rather than an official Zillow API.
- Estimates are directional and should not be treated as legal, tax, or appraisal advice.
- FIRPTA shown in the extension is modeled as withholding, not final tax liability.
