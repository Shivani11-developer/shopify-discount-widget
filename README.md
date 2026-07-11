# shopify-discount-widget
Shopify Discount Widget Assignment

## Overview

A custom Shopify discount widget built using Shopify Liquid, JavaScript, HTML, and CSS.  
The section provides dynamic product selection, discount calculation, and real-time price updates on the product page.

## Features

- Custom Shopify Liquid section
- Dynamic product and variant selection
- Real-time price calculation
- Discount and savings amount display
- Quantity-based pricing updates
- Dynamic capsule/quantity selection
- Responsive custom design

## Setup Instructions

1. Add the Liquid section file into the Shopify theme `sections` folder.
2. Add JavaScript and CSS files into the theme `assets` folder.
3. Include required assets in the Liquid section.
4. Add the section to the product page template through Shopify theme editor.

## Design Approach

- Built a reusable Shopify section instead of hardcoded product content.
- Used Shopify Liquid to fetch dynamic product data
- Separated CSS and JavaScript files for better maintainability.
- Created a clean product-focused UI with custom styling.
- Used JavaScript for dynamic interactions of change price and add to cart without page reloads.

## Technologies Used

- Shopify Liquid
- JavaScript
- HTML5
- CSS3

## Features implemented

✅ **3 products** — NMN 250mg (₹1,520), 500mg (₹2,880), 1000mg (₹4,800)  
✅ **4 discount tiers** — 0% / 10% (2–3 bottles) / 18% (4–5) / 25% (6+)  
✅ **Live pricing** — total, per-capsule, savings all update on every +/− tap  
✅ **Tier progress bar** — visual dots + fill bar showing current tier and progress  
✅ **Savings summary box** — shows total price, original price crossed out, ₹ saved, % off  
✅ **Tier nudge** — "Add 2 more → unlock 25% off, save ₹491 more" when 1–2 away from next tier  
✅ **Cart drawer** — slides in from right, shows per-item discount breakdown, totals, savings  
✅ **Mobile responsive** — tested at 375px, no horizontal scroll, all CTAs accessible  

## Functionality

The widget dynamically updates product information based on user selection, calculates discounts, updates pricing, and provides a smooth shopping experience directly on the product page.
