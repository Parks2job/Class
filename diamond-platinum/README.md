# Diamond Platinum Cleaning: Website

A single-page, animated marketing website for **Diamond Platinum Cleaning**, a
checklist-driven move-in/move-out, deep and recurring cleaning service in Metro Detroit.
Content is drawn from the company's Business Plan, Policy & Procedure Manual and Hiring
Package (July 2026).

## What's included

- `index.html`: the full responsive site (HTML, CSS and JavaScript in one file, no build step)
- `assets/logo.webp`: the original full-size DPC logo (transparent background). A web-sized copy is embedded directly in `index.html`, so the page shows the logo even when the HTML file is downloaded or opened on its own.

## Sections

Top contact bar · Sticky header · Animated hero with sparkle particles and an instant
square-footage estimator · Scrolling trust marquee · Who we serve (property managers,
homeowners/renters, real estate agents) · Services · Before/after slider · 4-step process
(quote, pre-clean walkthrough, checklist clean, final inspection) · Move-In/Move-Out
checklist tabs (from Business Plan Appendix A) · Per-square-foot pricing and add-ons ·
Core values · Reviews carousel · Careers (Cleaning Technician, Crew Lead) · FAQ · Contact
form · Footer · Mobile "Call / Free Quote" bar.

All animation respects the visitor's "reduce motion" setting.

## Where the content came from

| Site content | Source |
|---|---|
| Metro Detroit service area, client segments, services | Business Plan, Sections 1 to 4 |
| Pricing tiers, per-visit minimums, add-on prices | Business Plan, Sections 4.4 and 5 |
| Move-In/Move-Out checklist | Business Plan, Appendix A |
| Core values, background checks, uniforms, complaint and cancellation policy | Policy & Procedure Manual, Sections 2, 3, 6, 7 |
| Careers roles, requirements, hiring steps, pay perks | Hiring Package, Sections 2, 3, 9; Manual Section 8 |

## Before going live

| Item | Where | Status |
|---|---|---|
| Phone | (313) 750-6159 | done |
| Email | info@diamondplatinumcleaning.com | done (confirmed by owner) |
| Hours | search `Mon to Sat` | placeholder, not in source documents |
| Prices | `PRICING` at the top of the script | uses Business Plan midpoints; the plan says to confirm with 2 to 3 local competitor quotes before publishing |
| Reviews | Reviews section | sample text, marked "Sample review"; replace with real client reviews |
| Forms | quote and contact forms | demo only; connect to an email/CRM form service with privacy protections |
| Insurance / bonding | not claimed on the site | add "insured & bonded" only after coverage is in place |

## Preview

Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder and
visit `http://localhost:8000`.
