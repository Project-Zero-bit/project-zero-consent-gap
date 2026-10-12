# PROJECT ZERO — THE CONSENT GAP

Research prototype / Expedition 003 / 12 October 2026

## Run immediately

Open `index.html` in any modern browser. All primary functionality is static and runs locally with no build step, third-party scripts or external API keys.

## What actually works

- Responsive landing page, navigation and source links
- Request Studio: select water company, date range, geographic scope and evidence type, generate a properly scoped EIR request, copy, download TXT or open your own email app
- Operator contact: Southern Water and Thames Water contacts sourced from their published official pages; other operators require user verification
- Browser-local request tracker: save drafts, change manually tracked status, copy, export, import JSON, remove drafts
- Evidence Vault: filter 10 verified public source links; all citations link to original pages
- Evidence-Gap Brief Builder: construct and export an uncertainty-qualified due-diligence note

## Limitations

- Not hosted; publishing requires a hosting account and domain if desired.
- `mailto:` prepares a message but cannot guarantee a local email app is configured, and does NOT send any messages.
- Saved requests use `localStorage` in the current browser. If browser storage is disabled or cleared, use JSON export/import.
- Copy uses clipboard API where permitted and a legacy fallback. If disallowed, download TXT.
- No live central database, analytics or request-response status polling. All records/claim source links are public.
- Not legal advice, environmental auditing, a finding of wrongdoing, or proof that information is missing.
- No ownership claim to the name “ZERO INTELLIGENCE” (an existing UK company name).

## Deploy

Drag the `index.html` file, or the entire unzipped folder, to a static hosting service that supports drag-and-drop deploys (e.g., Netlify Drop). Alternatively place the contents at a static GitHub Pages repository and enable Pages. No backend or environment variables needed. Do not imply the site is online until it is actually deployed.

## Sources and business validation

See `RESEARCH.md` for the competitor screen, verified source URLs, hypotheses, current status and next commercial falsification test.