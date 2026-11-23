# Mimah's Cozy Getaway

Single-file website for Mimah's Cozy Getaway: two apartments in Syokimau, about a 10-minute drive from JKIA.
- **Taurus Residences**, 8th floor, Mwananchi Road: studio, queen bed and couch, 55" smart TV, 5G Wi-Fi, self check-in.
- **Luxore Apartments**, Block E, Chady Road: 31 m² one-bedroom, balcony and terrace, bath.

Guests choose an apartment and dates; WhatsApp (0725790850) opens with the booking message ready to send.

Sources: Airbnb (rooms 1357766964721904923 and 1426845128649012679), Booking.com, Agoda and HiChee listings.

## Edit
Everything is in `index.html`. Change the `CONFIG` object at the bottom (phone, apartments, photos, comparison table, FAQ).

## Put it online
GitHub Pages: Settings, Pages, deploy from `main`, folder `/ (root)`. Or upload `index.html` to `public_html` on cPanel.

## Before launch
- Photos load from Airbnb's image server. Download them into `images/` and switch `base`/`photos` in `CONFIG` to local paths.
- Add nightly rates (none are shown yet).
- Confirm check-in (until midnight) and check-out (10:00) apply to both apartments.
