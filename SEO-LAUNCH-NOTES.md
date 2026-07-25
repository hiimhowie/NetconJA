# NetCon SEO launch notes

## Included in this update
- Unique, location-led titles and meta descriptions for Home, About, Contact and Careers.
- Canonical URLs, Open Graph/Twitter preview metadata, an `en-JM` page language, and a branded 1200×630 social-share image.
- LocalBusiness JSON-LD on the home page and page-level schema for About and Contact.
- `robots.txt` and `sitemap.xml` for the three public pages.
- The careers page is `noindex,follow` and excluded from the sitemap because its roles and application form are still demo placeholders.

## NAP used everywhere
**Name:** NetCon (Powered by Hometime)  
**Address:** Shop #8, Four Paths Shopping Mall, Four Paths, Clarendon, Jamaica  
**Phone:** 876-807-7276 | 876-700-2591  
**Email:** customerservice@netcon.com  
**Hours:** Monday–Saturday, 9:00 AM–5:00 PM

Keep this spelling, phone format, address and hours identical on Google Business Profile, Facebook, Instagram, directories and invoices. A tiny disagreement is not the end of the world, but it gives Google one more loose screw to rattle.

## Before moving to a custom domain
This build uses the currently live Workers URL as the canonical source:
`https://white-sea-81cc.howardaris111.workers.dev`

When the client domain is connected, replace that base URL in these places before deploying:
1. `index.html`, `about.html`, `contact.html`, `join-us.html` for canonical, Open Graph and JSON-LD values.
2. `robots.txt` for the sitemap URL.
3. `sitemap.xml` for each listed page.

Do not leave the Workers URL as canonical after a custom domain becomes public. The live custom domain should become the one true address Google is asked to index.

## After deployment
1. Confirm `/robots.txt`, `/sitemap.xml` and `/images/netcon-social-preview.jpg` each load publicly.
2. Submit the sitemap in Google Search Console. The existing verification file is already in the project.
3. Use Google’s Rich Results Test to check the home page markup.
4. Claim or create the NetCon Google Business Profile with the same NAP above, correct category, current hours, photos and service areas.
5. When there are real vacancies and a working application path, remove `noindex,follow` from `join-us.html` and add it to the sitemap.

## Content next, in the order that actually matters
- Create one useful service-area page each for Four Paths, Sandy Bay and Free Town only after confirming coverage and adding genuinely different local details.
- Add a real FAQ: availability checks, installation timing, supported locations, support hours, payment methods, equipment and business packages.
- Turn demo forms into real WhatsApp/email/Sheets submissions. A page cannot be the conversion engine if the button is cardboard.
- Add authentic photos, customer reviews and a Google Business Profile link once approved.
