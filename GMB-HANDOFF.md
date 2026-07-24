# GMB handoff

## Outcome

Launch a polished call-and-book website and Google Business Profile asset pack for Bayou Dryline Water Damage Restoration Houston.

## Confirmed facts

- Brand: Bayou Dryline Water Damage Restoration Houston
- Service: Water damage restoration
- Market: Houston, Texas
- Phone: +1 832-242-9380
- Proposed domain: bayoudryline.shop
- Domain state: Spaceship API confirmed available and non-premium on 2026-07-23
- Proposed registration: one year, high privacy with consent, auto-renew off
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
- [ ] Recheck and register the approved domain with the recorded settings. (Spaceship `.shop` registry currently returns `unexpectedError`.)
- [x] Define and source licensed imagery.
- [x] Build the responsive website.
- [x] Validate desktop, mobile, accessibility, links, and content.
- [ ] Create and push the GitHub repository.
- [ ] Deploy through Vercel and attach apex plus `www`.
- [ ] Save Vercel nameservers at Spaceship and perform one propagation check.
- [ ] Build and verify the GMB asset pack.
- [ ] Record final operating links and propagation status.

## Current state

Brand, phone, approved domain, first-year price, and registration defaults are established. The responsive static website is implemented with licensed local assets and passes static plus real-browser QA at desktop and phone widths. Browser checks found one H1, no broken images, no horizontal overflow, no console errors, no form or email links, eight call links, eight booking links, and a working mobile menu. No domain has been purchased yet.

## Blocker

Spaceship's availability service currently returns `unexpectedError` for multiple `.shop` controls while successfully checking `.com`; this indicates a registry-specific provider error. Purchase approval for `bayoudryline.shop` is already confirmed, but registration must not be submitted until the required recheck returns `available` and non-premium.

## Exact next action

Publish the verified website to its dedicated GitHub repository and Vercel production project. Recheck `bayoudryline.shop` again later in the workflow; register only after Spaceship returns `available` and non-premium.
