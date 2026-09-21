# tappybird-site

Marketing page for Tappy Bird, hosted via GitHub Pages.

Live: https://vibedev1229.github.io/tappybird-site/

This is what App Store Connect's **Marketing URL** points at (the field renders as "Developer
Website" on the product page). It previously pointed at the Android privacy policy, which read as
a mistake to anyone who clicked it.

| Asset | Source |
|---|---|
| `assets/icon.png` | the real shipping app icon (`store_assets/icon_512.png`) |
| `assets/shot-*.jpg` | the real App Store screenshots, not mockups |
| `assets/hero.jpg` | generated (FAL, flux/schnell): background art only, no characters, no text |
| `assets/og.jpg` | composed locally: generated backdrop + real icon + typography |

The hero is the only generated asset, and deliberately contains no bird: an AI-drawn bird beside
the real one looks like a different game. An earlier generation put three brown birds in the sky
and was rejected for exactly that reason.

Privacy policies and support live in the separate `tappybird-privacy` repo.
