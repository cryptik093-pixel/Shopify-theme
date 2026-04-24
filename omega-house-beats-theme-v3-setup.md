# Omega House Beats Theme V3 — Setup Guide

## What V3 changes
- central **Revenue routing** controls in Theme Settings so one update can repoint the full funnel
- all major CTA surfaces now resolve through global routing if local section links are blank
- homepage, funnel page, product page bridge, cart upsells, sticky mobile CTA, header CTA, and footer CTA now iterate faster
- hero secondary CTA anchors correctly into the core-offer comparison section
- placeholder route links were removed from templates so V3 behaves like a store-control system rather than a fixed scaffold

## Revenue logic in V3
This version is built so you can operate the store from one routing spine:

- Beta
- Core
- Signature
- Premier I
- Premier II
- Premier III
- Premier Bundle
- Mix & Master
- Custom Beat Request
- Funnel landing page

When those are set once, the theme reuses them across the funnel.

## Upload steps
1. In Shopify Admin, go to **Online Store -> Themes**.
2. Click **Add theme -> Upload zip file**.
3. Upload `omega-house-beats-theme-v3.zip`.
4. Click **Customize**.
5. Open **Theme settings -> Revenue routing**.
6. Fill in every route first.
7. Then assign `page.days-of-dawn-on-end` to your main funnel page.
8. Upload hero artwork and audio preview URLs.
9. Connect header and footer menus.
10. Test mobile CTA, cart upsells, and checkout handoff.

## Fill these first in Theme settings -> Revenue routing
- Funnel landing page URL
- Beta offer URL
- Core offer URL
- Signature offer URL
- Premier Collection I URL
- Premier Collection II URL
- Premier Collection III URL
- Premier Bundle URL
- Mix & Master URL
- Custom Beat Request URL

## Why this matters
V2 still depended on template-level placeholder links. V3 removes that dependency so the store can be iterated without editing every section by hand.

## Highest-priority customizations after routing
1. hero image
2. audio preview URLs
3. header menu
4. footer menu
5. contact email
6. social links
7. product media and product descriptions

## Surfaces that now inherit routing automatically
- header primary CTA
- announcement bar CTA
- hero primary CTA
- audio proof CTA
- beta section CTA
- core comparison buttons
- Premier pack buttons and bundle button
- services buttons
- final CTA buttons
- sticky mobile CTA
- product page secondary CTA
- cart upsells
- footer CTA

## Recommended first QA pass
- mobile hero load
- sticky CTA visibility on phone
- beta to cart
- core/signature buttons
- bundle add-to-cart path
- cart upsell clicks
- service links
- footer email form
- page speed after real media is loaded

## Hard rule for V3
If a section does not help:
- conversion
- AOV
- email capture
- trust
- checkout completion
- repeat purchase logic

it should be stripped or deprioritized.
