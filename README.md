# Mimah's Cozy Getaway

Single-file website for Mimah's Cozy Getaway, a furnished one-bedroom serviced apartment at Luxore Apartments, Syokimau, near JKIA, Nairobi.
Guests pick dates and the form opens WhatsApp (0725790850) with the booking message ready to send.

Details and photos come from the Airbnb listing: https://www.airbnb.com/rooms/1426845128649012679

## What is in this repo
- `index.html` holds everything (HTML, CSS, JS). Edit the `CONFIG` object at the bottom of the script for phone, WhatsApp, location, photos, price, amenities and FAQ.

## Put it online
**GitHub Pages:** Settings, Pages, deploy from branch `main`, folder `/ (root)`.
**Any hosting provider (cPanel):** upload `index.html` into `public_html`.

## To fill in
- Photos are loaded from Airbnb's image server. Before launch, download them into an `images/` folder and change `CONFIG.photos` to the local paths (they can stop loading if Airbnb changes the links).
- Set `price` on the apartment in `CONFIG` once the rate is confirmed.
- Check-in and check-out times and house rules were not on the listing, so they are not shown.
