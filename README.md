# Inventory App

This is the first working cloud/mobile build for the Supabase Inventory App.

## What it does
- Mobile-friendly inventory screen
- Search inventory
- Add new inventory items
- Camera barcode/QR scanning
- Stock IN and Stock OUT
- Employee name recorded on transactions
- Low-stock indicator
- Cloud sync through Supabase
- Export inventory to CSV for Excel

## Important
The app uses the Supabase publishable key, which is designed for use in browser applications. Database security still depends on Supabase Row Level Security (RLS) policies.

## Run it
The camera requires a secure HTTPS website on the phone. Do not open index.html directly from Downloads. Host these files on an HTTPS static host, open the site in Chrome, allow camera permission, then choose "Add to Home screen" / "Install app".

## Next build
The next version can add:
- Employee sign-in
- Product photos
- Better barcode support
- Transaction/history screen
- Excel desktop sync
- Admin controls
