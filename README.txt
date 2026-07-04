MAYERS.CLUB — UPLOAD KIT
========================

Upload all 3 files to the domain root of mayers.club:

  index.html             The page itself. Fully self-contained (fonts, images,
                         CSS, JS all inline). Works on any host, any path,
                         even file://. No build step, no server config needed.

  apple-touch-icon.png   Icon shown when someone adds the page to their
                         iPhone home screen. iOS looks for this exact
                         filename at the domain root.

  og.jpg                 Preview card shown when the link is pasted into
                         iMessage / WhatsApp / Slack / social posts.
                         Referenced as https://mayers.club/og.jpg.

Notes
-----
- Only index.html is required. The other two are enhancements; if they are
  missing nothing breaks (previews/icons just fall back to blank).
- The browser-tab favicon is embedded INSIDE index.html — no separate file.
- If the page ends up somewhere other than the domain root, update the two
  absolute URLs in <head> (og:url and og:image).
- Upload as-is (binary/exact copy). Do not run the HTML through formatters,
  minifiers, or "optimize on upload" features.

Verify after deploy (2 minutes, on a real phone)
------------------------------------------------
1. Open mayers.club — hero slideshow runs, all 3 numbered cards + icons show.
2. Tap each card: ebook, Tally test, Stripe checkout all open.
3. Paste mayers.club into WhatsApp — preview card with photo appears.
