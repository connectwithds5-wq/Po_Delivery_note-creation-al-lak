# AL LAK Universal — PO & Delivery Note Creator

A free, static browser-based tool for creating purchase orders for Al Lak Universal.

## Features
- Create and edit purchase orders with multiple line items
- Quantity, unit price, line discounts, order discount, configurable VAT and totals
- Vendor, ship-to, delivery, warranty, payment terms and special instructions
- Save/open/search/delete POs in this browser
- Print or save as PDF
- Download a Word-compatible `.doc` file
- Export and restore a JSON backup
- No paid API, server, or database required for the basic version

## Use the tool
Open the published GitHub Pages URL, enter your PO information, and use **Print / Save PDF** or **Download Word** to export the document.

## Publish for free with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. The included workflow at `.github/workflows/pages.yml` deploys the site whenever changes are pushed to `main`.
4. Open the **Actions** tab and check the latest **Deploy PO Creator to GitHub Pages** run. After it succeeds, the Pages URL appears in the workflow summary and Settings → Pages.

## Important notes
- Saved POs remain in the current browser's local storage. They do not sync between devices or users.
- Use **Backup Data** regularly. Clearing browser data may remove saved records.
- The VAT rate defaults to 0% to avoid assuming tax treatment. Verify the applicable rate before issuing a PO.
- The Word export is an editable Word-compatible HTML `.doc` file.
- Confirm PO numbering is unique when multiple people create purchase orders.
