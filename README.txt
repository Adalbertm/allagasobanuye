zosezisobanuye PWA installation package

DEPLOY:
1. Extract this ZIP.
2. Upload index.html, manifest.webmanifest, sw.js, and the icons folder together to the same website root.
3. Deploy/redeploy on Vercel using HTTPS.
4. Open the HTTPS website in Chrome/Edge on Android or desktop.
5. Click "Install App". On iPhone/iPad, open in Safari, tap Share, then "Add to Home Screen".

IMPORTANT:
- Do not upload only index.html. The manifest, service worker, and icons are required.
- The service worker caches the main app shell only. Linked third-party movie websites still need internet.
- PWA installation is browser/device controlled; some browsers show their own install option instead of the custom prompt.
