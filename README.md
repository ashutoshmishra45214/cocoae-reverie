# Cocoae Reverie — Website Project

A responsive static website starter for the premium chocolate brand **Cocoae Reverie**.

## Included
- Home, Our Story, Collection, Product Details, Gallery, Contact, Cart, FAQ, Shipping & Returns, Privacy, and Terms pages
- Responsive navigation
- Product search and price filter
- Product details selected by URL (`product.html?id=hazelnut` or `?id=brownie`)
- Demo cart with quantity controls, subtotal, and browser `localStorage`
- Contact and newsletter forms with demo-only feedback
- WhatsApp link using the supplied number (confirm it before launch)
- CSS-made temporary chocolate artwork; no actual brand images were supplied

## Run on your Mac
1. Unzip the project.
2. Open VS Code.
3. Choose **File → Open Folder…** and select `cocoae_reverie_website`.
4. Open `index.html`.
5. Either open `index.html` in Chrome from Finder, or install the VS Code **Live Server** extension and choose **Open with Live Server**.
6. After editing, save with `Command + S`. With Live Server, the browser usually reloads automatically; otherwise refresh Chrome with `Command + R`.

## Main files
- `index.html`: homepage structure and copy
- `assets/css/style.css`: colors, layout, typography, responsive design
- `assets/js/app.js`: search, filtering, product detail, cart, and demo form behavior
- `assets/images/`: add your approved image files here

## Supplied content used
- Brand name: Cocoae Reverie
- Tagline: `a love of swetness and purity.` (spelling preserved from brief; confirm whether “swetness” should be “sweetness”)
- Product names/prices: Hazelnut ₹300; Brownie ₹200 (unit/weight not specified)
- Contact number: 9939407910
- Story text is reproduced as provided, including `ocoae Raveria` / `cocoae Raveria`; confirm spelling before launch.

## Important items to confirm before publishing
- Upload the real logo, motif, and product photography. Current artwork is CSS placeholder artwork, not product photography.
- Confirm brand spelling, tagline spelling, and final brand-story copy.
- Confirm whether prices are per piece, and provide product size/weight, ingredients, allergens, storage information, and availability.
- Confirm contact number and WhatsApp availability, plus business email, address, and social links if applicable.
- Write and review actual shipping, returns/refunds, privacy, and terms policies. Current policy pages are placeholders, not legal advice or final legal documents.
- Add a real contact/newsletter form service or backend. Current forms do not transmit or store submissions.
- The cart is a front-end demo. It does not create orders, reserve inventory, calculate shipping/tax, send confirmations, or take payments.
- Online payments, customer accounts, and order management are **not implemented**. These need a secure backend or commerce platform and payment provider, with testing before launch. Never collect card details directly in this static project.
- Website is not published. Hosting, domain/DNS, HTTPS, and deployment remain to be configured.

## Quick content edits
- To change a heading or paragraph, edit the text inside its HTML tags.
- To change a product price, update the product price in `assets/js/app.js` inside `PRODUCTS`, and the displayed price in `collection.html` and `index.html`. Keep those values in sync.
- To change colors, edit the CSS variables near the top of `assets/css/style.css`.
- To replace CSS placeholder artwork with photographs, add image files to `assets/images/`, then update the product art markup/CSS or the relevant page to use `<img src="assets/images/your-file.jpg" alt="Clear description">`.
