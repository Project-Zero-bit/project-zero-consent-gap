# PROJECT ZERO — Consent Gap site QA

Tested 12 October 2026 with Python Playwright and headless Chromium.

## Functional verification — passed

- Page renders without JavaScript errors.
- Auto-generated EIR request updates for operator, recipient, record type, place and dates.
- Verified contacts populate only for Southern Water and Thames Water; custom operator requires explicit manual recipient.
- Copy-to-clipboard action has a downloadable alternative for blocked clipboard permissions.
- Drafts can be stored, given manually tracked statuses, copied and downloaded; changes persist in a test storage provider across document refresh.
- Exported workspace JSON is valid and includes saved requests; round-trip import tested.
- Saved drafts can be cleared after explicit confirmation.
- Evidence Vault filters categories correctly: 2 decision records, 3 registers/data links and 5 guidance links.
- Evidence-gap note generation and TXT download verified.
- TXT request generation and download verified.
- Mobile navigation opens and closes correctly.
- No unexpected horizontal scroll at 320, 360, 390, 768, 1024 or 1440 px.
- No Playwright page JavaScript exceptions during tested flows.

## Deliberate exclusions

- No actual outbound EIR request sent, email service provisioned or user mail account accessed.
- Did not crawl or scrape source spreadsheets; official link provided to original publisher.
- Did not claim compliance certification, active monitoring, verified absence of consent or live industry coverage.
- Does not include a deployed public domain or connected cloud database.

## Deployment checklist

1. Secure brand/domain rights and decide publication name.
2. Upload website as a static site to a host and verify HTTPS, mobile, source links, download functions and browser storage.
3. Recheck operator contacts and ICO guidance before public announcement.
4. Add a real contact route controlled by the business, then publicly announce. No placeholder signup/contact capture is present.
5. Contact qualified users and obtain genuine consent for any outreach campaign.