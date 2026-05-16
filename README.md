# Resendiz Fence — Quote Estimator

A single-file, mobile-first web app for generating on-site fence estimates from a phone or iPad. No install, no server — open it in any browser.

## Features

- **Job types:** New Install, Repair, Replacement
- **Fence materials:** wood (cedar, pine, picket, shadowbox), vinyl (privacy, picket), chain link (galvanized, vinyl-coated), aluminum ornamental, wrought iron — with height multipliers (3–8 ft) and editable per-foot rates
- **Repair line items:** post / panel / picket / rail replacement, reset post, gate repair, hardware, stain/seal, custom
- **Gates:** walk and drive, single and double — editable prices
- **Demo & removal** with per-LF rate and haul-away flat fee
- **Photo attachments per section** (auto-resized, included on printed estimate)
- **Save / Open / New** quotes via browser `localStorage`
- **Invoice-style PDF** — dedicated print layout with letterhead, itemized table, totals, terms, signature lines, and site photo gallery

## Use it

Open `index.html` in any modern browser. On iPad/iPhone, tap **Share → Add to Home Screen** to launch fullscreen like a native app.

## Customize

Edit constants near the top of the `<script>` block in `index.html`:

- `COMPANY` — name, tagline, phone, email, address, license # (shown on every printed estimate)
- `MATERIAL_DEFAULTS` — fence types and base $/linear foot
- `HEIGHT_MULT` — height multipliers
- `CORNER_POST_COST` — per-corner upcharge
- `GATE_DEFAULTS` — gate prices
- `REPAIR_DEFAULTS` — repair line item prices

You can also override the $/ft on each section directly in the UI.
