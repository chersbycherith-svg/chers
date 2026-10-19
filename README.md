# Chers free website starter

A responsive static catalogue for Chers. Product enquiries open WhatsApp. There is no checkout, database, or paid hosting requirement.

## Included
- `index.html` — page content
- `styles.css` — design and responsive layout
- `products.js` — product names, categories, prices, descriptions and image paths
- `script.js` — search, filters and WhatsApp enquiry links
- `images/` — place product photos here

## Before publishing
1. Review the sample product list and pricing in `products.js`. This is a starter list, not a verified complete inventory.
2. WhatsApp is set to `919380431760` (India country code +91 and the number you confirmed). Change it in `index.html` and `script.js` if needed.
3. Add product photos to `images/` and set the corresponding product `image` value, for example `image: "images/bridal-bouquet.jpg"`. Leave `image: ""` until you have a photo.
4. Review the Instagram profile link in `index.html`.
5. Test the website on your phone before sharing it publicly.

## Update products
In `products.js`, each product looks like:
`{id:"sample", name:"Sample Product", category:"Hair Accessories", price:499, tag:"New", description:"Short description.", image:"images/sample.jpg"}`
Use a number to show a price, or `price: null` for “Price on enquiry”. Give every product a unique `id`.

## Publish for free using GitHub Pages
1. Sign in or create an account at https://github.com/
2. Create a **public** repository named `chers` (or another name you prefer).
3. Upload the files and the `images` folder from this ZIP. Upload the files inside the folder, not the ZIP itself.
4. Open repository **Settings → Pages**.
5. Choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then save.
6. After deployment, GitHub will show the website address. For a repository named `chers`, it is usually `https://YOUR-USERNAME.github.io/chers/`.
7. Give the first deployment a few minutes, then test the link on your phone.

## Important
- GitHub Pages is free for public repositories, but website files and product details are public.
- This static site has no admin dashboard. To change products, edit `products.js` and upload the updated file.
- It does not accept online payments or store customer information.
- The decorative bouquet artwork is a placeholder, not actual Chers product photography.
