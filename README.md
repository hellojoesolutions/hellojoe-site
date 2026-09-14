# HelloJoe Business Solutions Website

Production-ready static launch build for **HelloJoe Business Solutions** (`hellojoe.solutions`).

## Included

- Main marketing homepage with interactive 10-minute lead intake
- Netlify Forms lead capture with confirmation page
- Pricing page
- RGV, McAllen, Mission, and Pharr local marketing pages
- Social Media Management service page
- Local SEO / Google Business Profile service page
- Resource hub and launch articles
- SEO metadata, canonical URLs, structured data, internal linking
- `robots.txt` and `sitemap.xml`
- Static QA report and SEO launch plan

## Primary positioning

**Get Found. Get Chosen. Get More Business.**

Starting prices:
- Get Found — $99/month
- Social Media — $499/month
- Websites — $1,250
- Custom Apps / Systems — custom quote

## Business information

- Website: https://hellojoe.solutions
- Email: joe@hellojoe.solutions
- Phone: 956-884-1418
- Market: Rio Grande Valley / South Texas

## CMS

Sanity project: **HelloJoe Business Solutions**  
Project ID: `rvjyvgc8`  
Dataset: `production`  
Studio: https://hellojoe-business-solutions.sanity.studio/

API credentials are intentionally not stored in this repository.

## Production deployment

The site is configured for **Netlify** from the repository root.

Recommended Netlify settings:
- Repository: `hellojoesolutions/hellojoe-site`
- Production branch: `main`
- Build command: leave blank
- Publish directory: `.`
- Canonical domain: `https://hellojoe.solutions`
- Redirect `www.hellojoe.solutions` to `hellojoe.solutions`

`netlify.toml` contains clean-URL routing for service, city, pricing, and resource pages plus baseline security and asset-cache headers.

## Lead intake

The 10-minute intake is configured as a Netlify Form named `hellojoe-lead`. It collects the requested services, business/contact information, preferred call type/date/time, and optional context, then routes successful submissions to `thanks.html`.

## After hosting is connected

- Configure Netlify form submission notifications for `joe@hellojoe.solutions`
- Connect `hellojoe.solutions` and `www.hellojoe.solutions`
- Preserve all existing Google email MX/TXT records during DNS changes
- Add GA4 and conversion events
- Verify Search Console and submit `/sitemap.xml`
- Add Microsoft Clarity if desired
- Continue Google Business Profile optimization
- Add verified testimonials/case-study metrics as they become available
