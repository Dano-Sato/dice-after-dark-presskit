DICE AFTER DARK — PRESS KIT SETUP
===================================

This folder is ready to deploy as a static website.

1. UPDATE LINKS AND CONTACT IN index.html
-----------------------------------------
The Steam and trailer links and press email are already filled in.

2. ADD YOUR MEDIA
-----------------
Put these files in /assets:

assets/logo.png
  - Transparent Dice After Dark logo.
  - Recommended: large transparent PNG.

assets/key-art.png
  - Main hero / capsule-style artwork.
  - Recommended: 1920×1080 or larger.

assets/icon.png
  - Game icon.

assets/screenshots/screenshot-01.png
assets/screenshots/screenshot-02.png
assets/screenshots/screenshot-03.png
assets/screenshots/screenshot-04.png
assets/screenshots/screenshot-05.png
  - Use real gameplay screenshots.
  - 16:9 is recommended.

assets/dice-after-dark-media-pack.zip
  - Optional downloadable ZIP for press.
  - Suggested contents:
      Logo/
      Key Art/
      Screenshots/
      Icon/

If you want more screenshots, duplicate one gallery <a> block in index.html.

3. DEPLOY
---------
GitHub Pages:
- Make a new repository, e.g. dice-after-dark-presskit
- Upload everything in this folder to the repository root.
- Repository Settings → Pages
- Deploy from branch → main / root
- GitHub will give you a public URL.

You can also deploy the same folder unchanged to Cloudflare Pages or Netlify.

4. OPTIONAL CHANGES
-------------------
- Change "Coming Soon" once the release date is announced.
- Rewrite the Realmono Studio bio if desired.
- Add review quotes later.
- Add Discord/social links once public.
- Add a custom domain later; it is not required at first.

5. MEDIA USAGE
--------------
The page includes this line:
"All downloadable assets on this page may be used for editorial coverage of Dice After Dark."

That makes it clear that press/creators can use the supplied assets for coverage.
