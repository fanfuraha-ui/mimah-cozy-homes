# Mima Cozy Homes

*Stay • Relax • Feel at Home*

Single-file website for Mima Cozy Homes serviced apartments in Migori (built from the Whitehouse Stays site layout).
Guests pick dates and an apartment, and the form opens WhatsApp with the booking message ready to send. No photos or video yet.

## What is in this repo
- `index.html` holds everything (HTML, CSS, JS). Edit the `CONFIG` object at the bottom of the script for phone, WhatsApp, location, apartments, prices and FAQ.

## Put it online
**GitHub Pages:** Settings, Pages, deploy from branch `main`, folder `/ (root)`.
**Any hosting provider (cPanel):** upload `index.html` into `public_html`.

## To fill in
- Prices: set `price: "From Ksh 3,500 / night"` on each apartment in `CONFIG` (empty shows no price).
- Photos and video: none yet. Add a gallery section when Mima has its own pictures.
- Confirm the three apartment types (1, 2 and 3 bedroom) and the amenity list match Mima's actual homes.
