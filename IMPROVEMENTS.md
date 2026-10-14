# Patty's Mobile Detailing: Website Demo

Built on spec by tsKaizen. Every price, package, service, credential, photo and the logo come from the current pattysmobiledetailing.com. Nothing is invented.

## Pages (each tab is its own page)

| Page | File |
|---|---|
| Home | index.html |
| Ceramic Coating | ceramic-coating.html |
| Detailing Packages | detailing.html |
| Paint Correction | paint-correction.html |
| Interior Detailing | interior.html |
| Gallery | gallery.html |
| Contact / Free Quote | contact.html |

## Problems on the current site (good talking points)

1. **Google sees the wrong business name.** The homepage meta description, which Google can show under the link in search results, calls the company "Greater New Orleans Detailing."
2. **Coating packages don't match.** The ceramic coating page sells 1 year, 3 to 5 year and 6+ year packages, but the quote form asks customers to choose 2-Year, 5-Year or 9-Year.
3. **Copy-paste error.** The Wheel Ceramic Coating add-on uses the Headlight Restoration description word for word.
4. **Gtechniq is misspelled** ("Gtehcniq") on the coating page.
5. **Low-contrast buttons.** Dark gray text on bright red is hard to read, especially on phones in sunlight.
6. **"Paint Correction" appears twice** in the quote form's package builder.

## What the new design does, and why

These choices follow published guidance on detailing and local service websites (sources below).

| Tactic | Where it shows up |
|---|---|
| Starting prices on every service page, so customers self-qualify before calling | Every package card, plus "From $X" on each page header and home service tile |
| A clear booking action at the end of every page and contact info on every page | Red "Get a Free Quote" in the header, hero, each package and a closing banner; phone in the header and footer |
| Thumb-friendly mobile design with click-to-call | Call and Free Quote buttons pinned to the bottom of the phone screen |
| Real photos only, organized so people can find relevant work | Gallery with filters (Ceramic, Detailing, Paint, Interior) and a full-screen viewer |
| Trust signals spread across pages, not buried | "Since 2005, IDA Certified, 4.8 on Google, Mobile or in-shop" bar on every service page |
| Top menu kept to about 5 items, services grouped | Home, Services (dropdown with all 4), Gallery, Contact |
| Service-area list for local search | 12 neighborhoods on Home and Contact |
| Promote recurring services | "Keep it clean all year" section for the $85 maintenance plans |
| Shoppers watch video when choosing a local business | YouTube linked in the header area, footer and gallery |
| Package builder that matches what's actually sold | Quote form service list mirrors the real packages and prices; "Get a quote for this" prefills the service |

The existing Urable online booking link is kept everywhere as "Book Online," so nothing about how they schedule changes.

## Brand

- Same logo, hosted from their current site
- Same colors: signal red #FE0000, deep red #BD0000, black, white
- New scheme: black header and hero, light content sections for easy reading, deep red buttons with white text (passes contrast), bright red for accents
- Heading font Rubik, the same font their current site uses, paired with Inter for body text

## Before launch

- Photos and logo load from their current site. Download and host them with the new site before switching domains.
- Confirm the 4.8 Google rating is still current.
- Quote form uses Netlify Forms; submissions land in the Netlify dashboard and can email the shop.

## Sources

- CyberOptik, Best Auto Detailing Websites: https://cyberoptik.net/blog/best-auto-detailing-websites-success-secrets
- BrightLocal, Local Consumer Review Survey 2025: https://www.brightlocal.com/research/local-consumer-review-survey-2025/
