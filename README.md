# HomeBridge — Elegant multi-page Tailwind HTML concept

A visually complete **frontend-only** prototype for the NRB Support Platform, based on the original NRB support design brief.

## How to preview

Open `index.html` in a modern browser. All pages are separate HTML files and link to each other. Internet is required for the Tailwind CDN, Google Fonts, and Unsplash images.

## Pages

- Public: `index.html`, `services.html`, six `service-*.html` pages, `how-it-works.html`, `about.html`, `contact.html`, `faq.html`, `urgent.html`, `blog.html`, `article.html`
- Customer journey: `request.html`, `track.html`, `login.html`, `signup.html`
- Customer portal preview: `dashboard.html`, `my-requests.html`, `request-detail.html`, `family.html`, `payments.html`, `documents.html`, `profile.html`
- Legal placeholders: `privacy.html`, `terms.html`

## Demonstration behavior

- Mobile navigation, page transitions via hyperlinks, FAQ accordion, request form validation, and sample tracking view.
- Demo forms do not submit, save, or transfer information; payment and upload functionality is intentionally disconnected.
- Customer dashboard contains *fictional data*.

## Before production

1. Replace HomeBridge with approved brand and licensed photography.
2. Convert Tailwind CDN to a compiled production build. Add local images and optimize them.
3. Integrate Laravel + Inertia + React components, authentication and authorization.
4. Implement verified quotes, private document handling, role-based access, idempotent payment handling, receipts and notifications.
5. Implement SSR, canonical URLs, unique descriptions, structured data, robots/sitemap and an accessibility audit.
6. Confirm availability, pricing, operating hours, emergency response disclaimers, and legal policies.

No competitor artwork or source code is copied.
