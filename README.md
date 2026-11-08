# Food Scanner

A free web app that scans a packaged food's barcode and tells you, in plain language, what's good and bad in it.

**Live demo:** https://sahir-123.github.io/food---scanner/

## What it does
- Scans a barcode with the phone camera (or type it in)
- Fetches product data from the Open Food Facts API
- Shows sugar, saturated fat and salt as green/orange/red, using UK traffic-light limits per 100 g
- Shows the NOVA processing group and Nutri-Score when available
- Flags concerning ingredients (palm oil, hydrogenated fat, artificial colours and flavours, preservatives, refined flour)
- Gives a simple verdict: Looks fine / Okay occasionally / Limit this
- If a product isn't in the database, lets you type the label values and still get a verdict

## Built with
HTML, CSS, vanilla JavaScript, html5-qrcode, Open Food Facts API, GitHub Pages. No backend, no cost.

## Limitations
- Open Food Facts is crowd-sourced, and many locally sold Indian products are missing or incomplete
- The verdict is a simple rule-based guide, not medical or nutritional advice
- Ingredient flags use text matching and only work on English ingredient lists

## Ideas for later
- Read the label from a photo (OCR) for products not in the database
- FSSAI-based limits and plain-language explanations of INS additive numbers
