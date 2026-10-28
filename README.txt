PULSEFRAME STUDIO — RETRO WEBSITE (ALPHA v0.2.8)
=================================================

A complete, static, responsive website for pulseframe.tihsmile.space.
No framework, package manager, or server runtime is required on your hosting.

CONTENTS
--------
index.html         Main page (RU/EN UI)
style.css          Responsive styles and effects
script.js          Preset visualizer, audio analyser, Pulsy Runner web demo,
                   mobile menu, gallery and language switch
assets/            Optimized local images and favicon
robots.txt         Search crawler rules
sitemap.xml        Sitemap
THIRD_PARTY_NOTICES.txt

DEPLOYMENT
----------
1. Back up the files currently deployed at pulseframe.tihsmile.space.
2. Unzip this archive.
3. Upload the FILES INSIDE the extracted folder (not necessarily the
   parent folder itself) to the hosting site's web-root / public_html.
   index.html must live at the web-root.
4. Open https://pulseframe.tihsmile.space/ and hard-refresh (Ctrl+F5).
5. Check that all images, CSS and JavaScript work.

If deploying to GitHub Pages, place the files in the configured Pages root.
If deploying to a CDN, invalidate the previous site cache after upload.
The site needs HTTPS for the best Web Audio behavior.

FEATURES
--------
- Animated landing hero with PulseFrame Studio project artwork.
- Interactive Retro/Neon/Montagem canvas showcase.
- Optional local audio file upload for real Web Audio spectrum analysis.
  The selected file is played locally in the user's browser; the website
  does not upload it to a server.
- Retro TV themed section and simulated CRT visualization.
- Playable Pulsy Runner WEBSITE MINI-DEMO with keyboard/touch controls.
  This is a separate promotional mini-demo, not the exact built-in game.
- Features, early Alpha screenshots, setup guidance, FAQs, social links.
- Russian/English locale toggle saved locally in the browser.
- Responsive layout with reduced-motion support.

IMPORTANT ACCURACY NOTES
------------------------
- Visual demo is a site-specific interpretation of the project presets.
- Interface screenshots show an EARLIER ALPHA, labeled on the site.
- The website links to the general GitHub Releases list rather than an
  unverified exact v0.2.8 archive URL.
- The app is currently a source Alpha, not a ready-to-install desktop
  binary. Desktop use requires Node.js, MP4 export requires FFmpeg.
- Browser previews do not export MP4.
- The real Pulsy Runner in the application has three levels; the compact
  promotional website game uses a separate simplified arcade layout.
- Optional Google Fonts are requested for the multi-file hosted version;
  suitable system fallbacks are used when offline or blocked.

ALTERNATE FILE
--------------
A companion PulseFrame_Retro_v028_Standalone.html contains embedded CSS,
JavaScript, and image assets for an easy single-file preview or deployment.

CREATOR & PROJECT
-----------------
TihomirovSmile / PulseFrame Studio
https://github.com/pulseframeops/studio
https://pulseframe.tihsmile.space
https://www.reddit.com/r/plsframe/
