# NASCO Android App — starter build

This is a native Android Studio project for the NASCO shopping app.

## Included now
- NASCO blue/green branded interface
- Product catalogue and prices
- Add to cart and checkout
- Customer login or guest mode
- Order details stored locally on the phone
- Delivery request
- Call NASCO button
- SMS/message button
- Google Maps/location intent
- Basic local admin panel with PIN
- Add products from admin panel

## Important before publishing
This project is a working starter app, but a real commercial app needs a secure online backend for:
- user accounts across devices
- real-time orders and admin dashboard
- product images/catalogue syncing
- online payments/M-Pesa STK Push
- live delivery tracking
- push notifications
- secure messaging

Change `ownerPhone` and `adminPin` in `MainActivity.java` before publishing.

## Build
Open this folder in Android Studio, allow Gradle to sync, then Run on a phone/emulator. To publish, create a signed Android App Bundle (AAB) from Android Studio.
