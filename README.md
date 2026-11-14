# J.A.R.V.I.S. PWA — Version 1.0 foundation

This is the first mobile-first PWA foundation.

## Included
- Responsive blue HUD interface
- Local demo chat (not a connected AI)
- Optional local chat persistence
- Browser speech synthesis where supported
- Browser speech recognition where supported
- Basic service-worker caching for offline app shell
- PWA manifest and SVG icon
- Local data deletion control

## Important limitations
- No AI provider is connected yet.
- Voice recognition support depends on browser/device and may require internet.
- This is a PWA, not a native Android APK.
- Do not enter passwords, payment details, API keys, or sensitive personal information.
- Never put an AI API key in frontend JavaScript or a public GitHub repository.

## Deploy with GitHub Pages
1. Upload the contents of this folder to the root of a GitHub repository.
2. In repository Settings > Pages, choose deploy from branch `main` and folder `/ (root)`.
3. Save and wait for GitHub Pages to publish.
4. Open the published HTTPS site in Chrome on Android.
5. Use Chrome menu > Add to Home screen / Install app (wording varies).

## Next milestone
Connect an AI provider only through a secure server-side gateway, after checking current provider age requirements, free-tier limits, and data-handling terms.
