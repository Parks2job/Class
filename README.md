# CarePath Transport — Website

The website for **CarePath Transport**, a Saginaw, Michigan non-emergency medical
transportation (NEMT) company providing wheelchair and ambulatory rides in town and
across rural Mid-Michigan.

## Live site

https://carepathtransportmi.com, hosted free on GitHub Pages from this branch. The domain
is registered at Hostinger (auto-renews; expires 2027-10-17). DNS: four A records for `@`
(185.199.108.153, .109.153, .110.153, .111.153) and a CNAME `www` to `parks2job.github.io`.
The `CNAME` file in this folder must stay, or the custom domain disconnects.

## What's included

Seven pages (plain HTML with embedded CSS/JS, no build step) plus the logo in
`assets/images/`. See **Pages** below.

## How to preview

Open `index.html` in any web browser, or serve the folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Contact details

Phone (989) 481-1186, email carepathllc26@gmail.com, office 203 S. Washington Ave,
Saginaw, MI 48607 — set across all three pages.

## Pages

- `index.html` — homepage, including Payment & Insurance and a facilities teaser
- `facilities.html` — for facilities and case managers, with a partnership inquiry form
- `careers.html` / `apply.html` — driver recruiting and the full application
- `privacy.html`, `terms.html`, `accessibility.html` — approved by counsel (October 2026)

## Forms

All four forms (callback, ride request, facility inquiry, driver application) send
to carepathllc26@gmail.com through FormSubmit. FormSubmit must be activated once:
after the site is live, submit a test and click the "Activate Form" email.

## Online payments (Square)

"Pay Your Bill Online" buttons sit in the homepage Payment section and every footer,
live, linked to Square (https://square.link/u/48He2oRs). To change the link, replace it in every
`data-square-link` button across all seven pages.

## Before going live

- **Contracted health plans** — add them to the Medicaid card in the Payment section once contracts are signed
- **Testimonials** — removed; add real, permission-granted reviews later
- **Insurance coverage** — confirm the coverage statement in Terms section 10 with your agent
- **Accessibility** — last reviewed October 7, 2026 (WCAG 2.1 AA automated scan + keyboard test);
  review again at least yearly and after major changes

## Compliance note

The site states it is non-emergency only and to call 911 in emergencies. Insurance
acceptance, licensing, and vehicle/driver certification claims are jurisdiction-specific
— confirm the exact wording with counsel and update the disclaimer before publishing.
