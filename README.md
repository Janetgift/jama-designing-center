# Jama Designing Center — website starter

A responsive storefront for Jama Designing Center in Kabul, built with HTML, CSS and vanilla JavaScript. It uses the supplied shop/product photographs included in this folder.

## Preview locally
Open `index.html` in a browser. For a more accurate local preview, run a static server in this folder (for example `npx serve .`).

## Deploy to Vercel
1. Create a GitHub repository and upload all files in this folder.
2. In Vercel, choose **Add New → Project**, import that repository.
3. Framework preset: **Other**. Build command: leave blank. Output directory: `.` (or leave the default if Vercel detects static files).
4. Deploy. You can attach a custom domain from the Vercel project settings.

## Current functionality
- Responsive landing page and catalog using the provided photos.
- Category filters, enquiry bag, and WhatsApp order enquiry.
- Consultation request form that prepares a WhatsApp message for the shop to confirm.
- English, Dari and Pashto interface switcher with RTL layout for Dari/Pashto.
- Product prices are deliberately not invented; the customer is asked to confirm current prices and stock with the shop.

## Important before real business use
This is a **front-end starter**, not yet a full commerce backend. The enquiry bag is browser-only; product catalogue content is currently in `app.js`. There is no secure admin dashboard, persistent database, inventory, user accounts, or online payment integration yet. Do not advertise it as having these until they are implemented and tested. For a secure admin/dashboard, connect a database and authentication provider (for example Supabase) and enforce access rules server-side. Payment options for a merchant in Afghanistan need to be confirmed with a supported provider before enabling online payment. The WhatsApp links assume the listed phone number is WhatsApp-enabled; confirm that with the shop. Appointment and order requests are not confirmed until the shop replies.

## Business details shown
Jama Designing Center · G45V+HJQ, 1st St, Kabul 100312, Afghanistan · +93 72 872 7070. Opening hours are not claimed; visitors are asked to contact the shop to confirm.
