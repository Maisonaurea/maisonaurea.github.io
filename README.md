# Maison Aurea — free starter storefront

This is a static storefront designed for GitHub Pages. It includes product categories, product search/sorting, selectable options, a basket saved in the visitor's browser, and order-request preparation.

## Files
- `index.html` — store structure and order form
- `style.css` — responsive black, ivory and champagne-gold design
- `script.js` — demo products, basket, WhatsApp and email order flow

## Before publishing
1. In `script.js`, set `WHATSAPP_NUMBER` to your business WhatsApp number in international format, digits only. For Bulgaria, use `359...` without `+` or spaces.
2. Set `BUSINESS_EMAIL` (see note below) to the email address that should receive order requests. In the current starter code, find `const emailTo = "";` and replace the empty string with your business email.
3. Replace all demo product names, prices, options, descriptions and images with accurate details. Demo prices and stock labels are not real offers.
4. Check supplier permission, availability and delivery timing before listing supplier products.
5. Test on mobile and desktop before sharing the website.

## Publish with GitHub Pages
1. Create a public GitHub repository named `maison-aurea` (or another name you prefer).
2. Upload `index.html`, `style.css`, `script.js` and this README to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose **main** and **/(root)**, then save.
5. Wait for GitHub Pages to publish the site. The URL will normally look like `https://YOUR-USERNAME.github.io/maison-aurea/`.
6. Test every category, add-to-bag controls, quantity changes and order buttons.

## Important limitations
- GitHub Pages is static hosting. It does not store or email orders automatically, process payments, reserve inventory, or provide a secure admin dashboard.
- The basket is saved in each customer's own browser. It is not a shared inventory or order database.
- WhatsApp order links work after you set your number. Email order requests use the visitor's own email application after you set your business email in `script.js`.
- A real order is not confirmed until you receive and confirm the request. Confirm stock, final price, delivery fee, payment, returns and delivery timing with the customer.
- Before selling, publish accurate business contact details, terms, privacy information, delivery/returns policy, and legally required consumer and product information for Bulgaria/EU. Beauty/cosmetics and branded products may have extra compliance requirements.

## Product image note
Demo photos use remote Unsplash URLs and require an internet connection. Replace with product photos you have the right to use. Do not use supplier or brand photos without permission where required.
