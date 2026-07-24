# GMB handoff

## Outcome

Launch a polished call-and-book website and Google Business Profile asset pack for Bayou Dryline Water Damage Restoration Houston.

## Confirmed facts

- Brand: Bayou Dryline Water Damage Restoration Houston
- Service: Water damage restoration
- Market: Houston, Texas
- Phone: +1 832-242-9380
- Domain: bayoudryline.shop
- Domain state: registered successfully through Spaceship on 2026-07-23
- Registration: one year, high privacy with consent, auto-renew off (verified through registrar readback)
- Current first-year price: USD $0.90 before applicable tax ($0.70 registration plus $0.20 mandatory ICANN fee)
- Booking: https://cal.com/sumitdatta/auto-detail-service

## Decisions and truth constraints

- Brand research found no surfaced exact-match or close Houston competitor for “Bayou Dryline”; the local market is dominated by generic and franchise restoration names.
- Audience: Houston property owners dealing with leaks, appliance failures, storm intrusion, or indoor flooding.
- Primary conversion: call; paired secondary action: book online.
- No address, hours, prices, response-time promise, emergency/24-7 claim, certification, insurance-handling claim, guarantee, review, customer count, or service-radius claim unless confirmed.
- Do not imply stock launch photography shows this company’s employees or completed work.
- Public contact paths are telephone and Cal.com only; no form or email.
- Visual direction: deep navy, desaturated floodwater blue, equipment orange, mist white, and concrete gray; condensed industrial display type with a highly readable humanist body face; a structured inspection-to-dryout layout; signature animated moisture-line motif that resolves from saturated to dry while respecting reduced-motion settings.
- Design critique: avoid the common dark-plus-neon restoration template; keep the equipment orange limited to calls to action and use the waterline motif as the sole expressive device.

## Acceptance criteria

- Responsive static site with call and booking actions in every CTA group.
- Honest restoration funnel covering assessment, water removal, drying, monitoring, and next-step guidance without unsupported claims.
- Licensed local/service-relevant images, accessible structure, metadata, and no placeholder copy.
- Dedicated GitHub repository connected to a production Vercel project.
- Apex and `www` attached; Spaceship nameservers saved for Vercel.
- `GMB-INFO.txt`, one square PNG logo, four landscape covers, four business JPGs, and `SOURCES.txt`.

## Tasks

- [x] Recover the confirmed public phone number from Space City Gleam.
- [x] Delete the Space City Gleam local project as requested.
- [x] Research Houston competitors and choose a distinct brand.
- [x] Confirm the proposed `.shop` is available and non-premium through Spaceship.
- [x] Verify current standard `.shop` registration pricing and mandatory fee.
- [x] Receive approval to buy the exact proposed domain at the recorded price.
- [x] Recheck and register the approved domain with the recorded settings.
- [x] Define and source licensed imagery.
- [x] Build the responsive website.
- [x] Validate desktop, mobile, accessibility, links, and content.
- [x] Create and push the GitHub repository.
- [x] Deploy through Vercel and attach apex plus `www`.
- [x] Save Vercel nameservers at Spaceship and perform one propagation check.
- [x] Build and verify the GMB asset pack.
- [x] Record final operating links and propagation status.

## Current state

All non-DNS deliverables are complete. The approved domain is registered with high privacy and auto-renew off. The responsive static website passes static plus real-browser QA at desktop and phone widths: one H1, no broken images, no horizontal overflow, no console errors, no form or email links, eight call links, eight booking links, and a working mobile menu. The public GitHub repository is connected to the Vercel project for push-to-production deployments. Production is `READY`, both custom hosts are attached, the Vercel fallback passes HTTPS/content verification, and Spaceship reads back the two Vercel nameservers. The final GMB pack contains the confirmed website, phone, 702-character description, exact site logo, four 1600×900 covers, and four business photos.

## Blocker

Fresh-domain public DNS and HTTPS propagation are pending. The single immediate Vercel snapshot still returned the registry nameservers; no further DNS polling was performed.

## Exact next action

In a later run, verify the apex and `www` hosts after DNS propagation. Do not repeat the registrar change unless Spaceship no longer reads back the saved Vercel nameservers.

## Operating record

- Custom website: https://bayoudryline.shop
- Production fallback: https://bayou-dryline-houston.vercel.app
- GitHub: https://github.com/DaInfernalCoder/bayou-dryline-water-damage-restoration-houston
- Vercel project: https://vercel.com/dainfernalcoders-projects/bayou-dryline-houston
- Local folder: `/Users/sumit/Documents/gmb/Bayou Dryline Water Damage Restoration Houston`
