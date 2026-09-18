# CarePath Transport — Website

A single-page marketing website for **CarePath Transport**, a non-emergency medical
transportation (NEMT) company specializing in wheelchair, stretcher, and ambulatory rides.

## What's included

- `index.html` — the full responsive website (HTML + embedded CSS/JS, no build step)
- `assets/images/carepath-logo.webp` — company logo

## Sections

Sticky header · Hero with quick-quote form · Trust strip · Services (Wheelchair /
Stretcher / Ambulatory) · Use cases · How it works · Why us · Service area ·
Testimonials · FAQ · Call-to-action band · Contact / booking form · Footer ·
Sticky "tap to call" bar on mobile.

## How to preview

Open `index.html` in any web browser, or serve the folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before going live — replace the placeholders

These are marked with placeholder values throughout `index.html`:

- **Phone number** — `(000) 000-0000` (search and replace, including `tel:+10000000000`)
- **Email** — `dispatch@carepathtransport.com`
- **Office address & hours**
- **Service area** — city/county tags in the Service Area section
- **Testimonials** — replace samples with real, permission-granted reviews
- **FAQ answers** — insurance/payment answer especially
- **Form backend** — the booking and quick-quote forms are demos; connect them to
  an email service, CRM, or form handler to receive submissions.

## Compliance note

The site states it is non-emergency only and to call 911 in emergencies. Insurance
acceptance, licensing, and vehicle/driver certification claims are jurisdiction-specific
— confirm the exact wording with counsel and update the disclaimer before publishing.
