# NSTR Fashions — Conversion Tracking Practice Website

This is a local practice store created for learning advertising conversion tracking.

## Run it
1. Open `index.html` in Chrome.
2. Add a product to the cart.
3. Proceed to checkout.
4. Fill the test details.
5. Click **Place Test Order**.
6. Open Chrome DevTools → Console to see the test events.

## Events included
- page_viewed
- items_added
- checkout_started
- order_created

## Important
The `sendTestEvent()` function is intentionally a placeholder. It does NOT send data to OpenAI.

To connect this site to OpenAI Ads, create your OpenAI Ads measurement/data source first and then replace the placeholder with the current official OpenAI Measurement Pixel and/or Conversions API implementation from OpenAI's documentation.

Do not put an OpenAI Conversions API access token in browser-side JavaScript. Server-side credentials must remain on a secure backend/server.

All orders are fake test orders. No real payment is processed.
