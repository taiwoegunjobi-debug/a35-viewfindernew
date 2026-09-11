# A35 Lens Finder — Install Ready

Minimal ALEXA 35 / Super 35 anamorphic viewfinder for Pixel 6 Pro landscape.

## Files
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

## Deployment
Deploy the entire folder to Vercel. Open the HTTPS deployment in current Chrome on Android.

The service worker and PNG icons are included to make Chromium PWA installation much more reliable.

## Pixel
Open the deployed URL in Chrome, allow camera access, then use Chrome's three-dot menu. Depending on Chrome version, the command may appear as:
- Install app
- Add to home screen
- Install A35 Lens Finder

If the command does not appear immediately after first load, reload the page once after the service worker has registered.

The app requests landscape orientation when installed and is designed for a Pixel 6 Pro landscape display.

Note: lens framing is a practical ALEXA 35/S35 FOV simulation, not an optical replacement for a real ALEXA 35 and anamorphic lens.
