# Design Your Ideal Day: landing page

Static sales page for the $18 fillable lifestyle workbook. No build step.

## Files
- `index.html`: the landing page (page previews embedded, no external requests)
- `terms.html`: Terms of Use
- `privacy.html`: Privacy Policy
- `robots.txt`: crawler rules
- `sitemap.xml`: sitemap for idealday.dtdm.us
- `_headers`: Cloudflare Pages security headers

## Checkout
The SamCart checkout link is set in `index.html` (`var CHECKOUT_URL`, near the bottom).

## Deploy on Cloudflare Pages
- Framework preset: None
- Build command: (leave empty)
- Build output directory: `/`

Contact shown on the site: dan@dtdm.us

Live address: https://idealday.dtdm.us
