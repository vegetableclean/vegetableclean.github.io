---
title: "Tucson Zillow Value Lens"
excerpt: "A Chrome extension that estimates future value, sale profit, and Tucson-specific investment signals directly on Zillow listing pages.<br/><img src='/images/projects/tucson-zillow-value-lens-preview.png'>"
collection: portfolio
---

## Tucson Zillow Value Lens

`Tucson Zillow Value Lens` is a Chrome extension prototype for quick house-underwriting on Zillow listing pages in the Tucson area.

Instead of switching across spreadsheets, calculators, and neighborhood notes, the extension injects a compact side panel directly into the Zillow page and shows:

- future value scenarios for `2 / 3 / 4 / 5 / 10 / 20` years
- low / base / high sale-price range
- estimated sale profit and ROI
- remaining mortgage balance and net sale proceeds
- optional FIRPTA withholding toggle for foreign sellers
- adjustable assumptions for down payment, mortgage rate, and appreciation potential

## Why it is useful

This tool is designed for fast decision support when comparing listings in different Tucson submarkets such as:

- Catalina Foothills
- Oro Valley
- Casas Adobes
- Marana
- Central Tucson
- key zip codes including `85718`, `85750`, `85737`, `85704`, `85741`, `85742`, and `85749`

The goal is not to replace formal appraisal, but to make early-stage screening much faster and more transparent.

## Demo

Real Zillow listing screenshot with the extension panel:

![Tucson Zillow Value Lens preview](/images/projects/tucson-zillow-value-lens-preview.png)

## Download

- Chrome extension package: [Download ZIP](/files/extensions/tucson-zillow-value-lens-extension.zip)

## Current features

- bilingual interface: English / Chinese
- compact on-page panel
- year-selector buttons to reduce clutter
- mortgage-sensitive profit estimation
- Tucson-area regional baseline logic

## Notes

- This is a prototype and uses a local heuristic parser rather than an official Zillow API.
- Estimates are directional and should not be treated as legal, tax, or appraisal advice.
- FIRPTA shown in the extension is modeled as withholding, not final tax liability.
