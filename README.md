# kskdigital-site

Public-facing company website for **KSK Digital LLC**, deployed at [kskdigital.app](https://kskdigital.app).

## Purpose

This site exists to satisfy Google Play Developer (Organization account) verification requirements: Google requires a public business website that displays the company name, address, email, and phone consistent with the developer profile and D-U-N-S record. It is intentionally minimal.

## Stack

- Single static HTML file (`index.html`), no build step.
- Hosted on Vercel.
- DNS via Cloudflare (CNAME flattening at apex), same pattern as `wearandwhen.app`.

## Updating content

1. Edit `index.html` locally in any editor.
2. Commit and push via GitHub Desktop.
3. Vercel auto-deploys from the `main` branch.

## Known placeholders

- **Phone number** is currently shown as "Available soon" pending the Google Voice number claim for `kskdigitalvoice@gmail.com`. Swap into the `.phone-pending` `<dd>` element once the Voice number is live. Update class to remove pending styling.

## Canonical business data

All values on the site must byte-match across:
- Wisconsin DFI LLC filing (`KSK DIGITAL LLC`, entity ID K069060)
- D-U-N-S record (pending)
- Google Payments profile (pending)
- Google Play Developer profile (pending)

If any of those change, this site changes first or in lockstep.

| Field | Value |
|---|---|
| Legal name | KSK Digital LLC |
| Address | 3101 Whiting Ave, A1, Stevens Point, WI 54481-5120 |
| Email | founder@kskdigital.app |
| Phone | (pending Voice claim) |
| Entity ID | K069060 (WI) |
| Effective date | March 27, 2026 |

## Owner

K (Kevin Kimmel), sole member of KSK Digital LLC.
