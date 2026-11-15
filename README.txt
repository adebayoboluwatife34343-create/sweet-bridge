SWEET BRIDGE — NETLIFY STOREFRONT DEMO
====================================

QUICK START
1. Unzip Sweet-Bridge-Netlify.zip.
2. Open index.html in a modern browser for a local preview.
3. To publish, upload the extracted folder containing index.html to Netlify's
   manual deploy area. Keep assets/, app.js, config.js and style.css together.
4. No installation, build command, database or API key is needed.

WHAT WORKS
- Responsive store layout and animated bottle hero with pointer tilt.
- Motion pause button and reduced-motion support.
- Product search, size filters, price sorting and saved favourites.
- Product details, quantity selector and small/medium/large bottle transitions.
- Persistent bag, quantity editing and removal.
- Checkout validation, delivery options and SWEET10 (10% off the subtotal).
- Flutterwave-style MOCKUP with preset card and bank-transfer previews.
- Successful and declined payment simulations.
- Browser-local demo order history and downloadable text receipts.
- FAQs, story, sweet-moment cards and enquiry draft downloads.

SAMPLE PRICES — NOT APPROVED COMMERCIAL VALUES
Small 250 g: NGN 3,500
Medium 500 g: NGN 6,500
Large 1 kg: NGN 12,000
Standard delivery: NGN 1,500
Express delivery: NGN 3,000
Pickup: free (demonstration only)

The original supplied bottle photograph showed 500 g. The 250 g and 1 kg sizes
are proposed options, not verified products. All sizes and prices are editable
in config.js. Only confirmed brand/product claims should be used for live sales.

MEDIA STATUS — IMPORTANT
Included:
- The generated Sweet Bridge three-size concept image.
- A generated transparent product cutout based on the bottle concept.
- A temporary typographic brand mark and SVG favicon.

Not included:
The original logo JPEG, two original product/lifestyle JPEGs and both uploaded
MP4 videos could not be downloaded in the build environment. The code supports
local video files, but the video section remains hidden until files are added.
Do not describe this ZIP as containing those original uploads.

To add original media:
1. Copy the logo to assets/logo.jpg.
2. Copy the shopping-basket image to assets/lifestyle.jpg.
3. Copy the original bottle image to assets/original-product.jpg.
4. Copy the videos to assets/brand-film-1.mp4 and assets/brand-film-2.mp4.
5. In config.js set:
   logo: 'assets/logo.jpg',
   lifestyle: 'assets/lifestyle.jpg',
   originalProduct: 'assets/original-product.jpg',
   videos: ['assets/brand-film-1.mp4', 'assets/brand-film-2.mp4']
6. Upload the updated complete folder to Netlify.

The original files can be downloaded from the same conversation attachments.
The transparent generated bottle stays in use for the motion effects.

DEMO PAYMENT BEHAVIOUR
The Flutterwave-style UI is an independent visual mockup, not the actual
Flutterwave checkout or SDK. No external payment service is called. There are
no keys, card inputs, live bank account numbers, charges or merchant orders.
The demo card is a preset visual only.

Use made-up customer details, e.g. Demo Customer / demo@example.com, to test.
Customer contact/address inputs stay in page memory, are reset after a
successful simulation and are not saved to local storage or transmitted.
Cart, favourites and demo order totals are saved only in that browser.
There is no account login, server order database, inventory, email service,
real order tracking, admin system or backend in this static package.
The enquiry form downloads a draft; it does not send an email.

GOING LIVE LATER
Confirm actual sizes, prices, stock, business contacts, delivery areas,
pickup address, return/refund terms and privacy notice. Add the original media.
A live payment integration needs a trusted backend to recalculate prices,
verify payment references/amount/currency, handle signed payment notifications,
and store confirmed orders before any fulfilment. Never add secret keys to
config.js or any public file. Simply changing demo:true will NOT activate
live payments; no live-payment path is implemented in this package.

CHECKS COMPLETED
JavaScript syntax; local asset and anchor references; cart arithmetic;
quantity caps; persisted cart and invalid-storage recovery; bottle size
selection; shipping and promo totals; successful/declined simulation; saved
order history; exclusion of customer contact/address data from saved orders.
Browser visual/interactive QA could not run because the preview environment
was unavailable. Responsive styles are included but are not browser-verified.

FONT NOTE
Google Fonts is optional. If unavailable, the design falls back to Georgia
and Arial. Product imagery, styling, scripts and demo functionality are local.
