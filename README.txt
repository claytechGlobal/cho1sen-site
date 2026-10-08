CHO1SEN HEALING CENTER - WEBSITE FILES
======================================

WHAT'S IN THIS FOLDER
  index.html   The whole site: Home, Shop, product pages, Our Mission,
               Founder, Donate, cart. All styles and code are inside this file.
  img/         Product and brand images used by the site.
      banner.jpg       Home page banner
      journal.jpg      90-Day Healing Journal
      giftbox.jpg      Healing Gift Box
      experience.jpg   Cho1sen Experience Box
      founders.jpg     Founder's Limited Edition
      jacket.jpg       Letterman Jacket (front and back)
      sleeves.jpg      Letterman Jacket sleeves
      founder.jpg      Dayna Laurette Broussard photo

PREVIEW ON YOUR COMPUTER
  Unzip the folder and double-click index.html. Keep index.html and the
  img folder together, or the pictures won't show.

PUT IT ONLINE
  Upload index.html and the img folder together to any web host
  (Netlify, GitHub Pages, Hostinger, GoDaddy, etc.).

EDITING COMMON THINGS (open index.html in any text editor)
  Prices & product text   Search for "const PRODUCTS" near the bottom.
  Free shipping amount    Search for "FREE_SHIP" (currently 100).
  Donation amounts        Search for "D_MIN", "D_MAX", "D_STEP" and "PRESETS"
                          ($10 to $1,000 in $10 steps).
  Donation impact lines   Search for "impactFor".
  Hotline numbers         Search for "1-800-799-7233".

BEFORE TAKING REAL ORDERS OR DONATIONS
  - Payments are NOT connected. The Checkout button shows a notice and does
    not charge anyone. Connect Stripe, Square, PayPal or Shopify Buy Button
    (monthly donations need a provider that supports recurring billing).
  - The newsletter form does not save emails yet. Connect Mailchimp,
    Flodesk, ConvertKit or similar.
  - The cart is saved in each visitor's own browser only.
