# Konaseema Parampara website – updated prototype

Open `index.html` in a modern browser. Keep the `assets` folder beside it; it contains the ten generated pickle product images used by the website.

## Included
- Ten pickle products with locally bundled product images
- Veg / non-veg categories, search and filters
- 250 g, 500 g and 1 kg pack selectors
- Temporary sample prices (INR) for testing cart calculations
- Add/remove cart items, quantity controls, subtotal
- Wishlist stored in the visitor browser
- Animated jar brand mark, floating pickle images in hero, gentle hero drift, product-card entrance, hover effects and scroll-reveal sections
- Coming-soon sweets, hot snacks and Pindi Vantalu categories
- WhatsApp chat and prefilled WhatsApp order message flow
- Responsive mobile layout

## Temporary sample prices (not final selling prices)
| Product | 250 g | 500 g | 1 kg |
|---|---:|---:|---:|
| Mango Avakaya | ₹160 | ₹300 | ₹560 |
| Green Chilli Pickle | ₹140 | ₹260 | ₹480 |
| Gongura Pickle | ₹150 | ₹280 | ₹520 |
| Tomato Pickle | ₹130 | ₹240 | ₹440 |
| Chintakaya Pickle | ₹150 | ₹280 | ₹520 |
| Boneless Chicken Pickle | ₹260 | ₹500 | ₹950 |
| Chicken Pickle with Bone | ₹230 | ₹440 | ₹840 |
| Mutton Pickle | ₹320 | ₹620 | ₹1,180 |
| Prawn Pickle | ₹300 | ₹580 | ₹1,100 |
| Fish Pickle | ₹250 | ₹480 | ₹920 |

## Before launch
1. Replace `WHATSAPP_NUMBER = "91XXXXXXXXXX"` in `index.html` with the actual business WhatsApp number in international format (India: 91 + 10 digits). It is not displayed on the website.
2. Confirm and replace the sample prices in each product's `prices` object.
3. Confirm the product photographs accurately represent your actual products; replace any image if needed.
4. Add the official FSSAI logo and licence number only after the licence is issued and verified. A placeholder area is currently shown.
5. Connect a secure backend/database for real order storage, stock management and admin access. This prototype stores cart and wishlist in the customer's browser; orders are sent as a WhatsApp message and are not saved to a business database.

WhatsApp opens a pre-filled order message; the customer must press Send. Payment is coordinated in the WhatsApp conversation. This site does not collect or verify payment.
