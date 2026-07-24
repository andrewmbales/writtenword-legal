# WrittenWord — Public Pages

Public-facing legal and support pages for **WrittenWord**, a Bible study app for iPad (NASB 1995 text, interlinear Greek/Hebrew word lookup, Apple Pencil annotations, highlights, bookmarks, notes, cross-references, and concordance search).

These pages are static HTML served via **GitHub Pages** and are the URLs referenced in the app's App Store Connect listing.

## Live pages

| Page | File | URL |
| --- | --- | --- |
| Privacy Policy | `index.html` | https://andrewmbales.github.io/writtenword-legal/ |
| Support | `support.html` | https://andrewmbales.github.io/writtenword-legal/support.html |

## Updating

1. Edit the relevant HTML file (`index.html` or `support.html`).
2. When changing the privacy policy, also update the **"Last updated"** date near the top of `index.html`.
3. Commit and push to the `main` branch — GitHub Pages redeploys automatically within a minute or two.
4. If a change affects what data the app collects or stores, make sure the App Store Connect **App Privacy** answers and the app's bundled `PrivacyInfo.xcprivacy` stay consistent with the policy.

Both pages are hand-authored HTML with inline CSS (no build step, no dependencies), so they can be edited directly.

## Contact

Questions about the app: [writtenwordsupport@gmail.com](mailto:writtenwordsupport@gmail.com)

---

Bible text: New American Standard Bible, 1995 edition (NASB® 1995), © 1960, 1971, 1977, 1995 by The Lockman Foundation. Used by permission. [www.lockman.org](https://www.lockman.org)

© 2026 WrittenWord
