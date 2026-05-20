# Mini Property Offer Calculator

A simple single-page web app for real estate investors to quickly estimate a **maximum allowable offer (MAO)** on a fix-and-flip property.

## What it does

The app lets you enter:

- Property address
- ARV (after-repair value)
- Estimated rehab cost
- Closing/holding/resale costs
- Desired profit
- Max offer formula percentage (defaults to **65%**)

It calculates:

- **Max allowable offer** = `ARV * percentage - rehab - costs - desired profit`
- **Estimated spread**
- A concise **retail flip summary** in plain language

## How to use

1. Open `index.html` in any modern web browser.
2. Review or replace the sample default values.
3. Update each field to match your deal assumptions.
4. Read the live-updating max offer, spread, and summary.

## Notes

- No build tools or dependencies are required.
- Built with plain HTML, CSS, and JavaScript only.
- Mobile-friendly layout for quick use in the field.
