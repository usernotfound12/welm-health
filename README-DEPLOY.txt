
WELM HEALTH — COMPLETE WEBSITE EXPORT
Exported August 10, 2026

────────────────────────────────────────────────────────────────
DEPLOY IN ONE STEP
────────────────────────────────────────────────────────────────
Upload  index.html  and  faq.html  to any static host — Netlify,
Vercel, GitHub Pages, S3, or any web server — keeping them in the
same folder. Both are fully self-contained: every image, font, the
hero video and all code are embedded inside them. Nothing else in
this archive is needed for the site to run.

To preview locally, just double-click index.html.

GITHUB PAGES
────────────────────────────────────────────────────────────────
1. Create a repository (public, any name).
2. Upload index.html and faq.html to the root of the default
   branch. Do not put them in a subfolder.
3. Settings → Pages → Source: "Deploy from a branch",
   Branch: main, Folder: / (root). Save.
4. The site is live at
   https://YOUR-USERNAME.github.io/YOUR-REPO/
   within about a minute.

   For a custom domain (welmhealth.com), add it under
   Settings → Pages → Custom domain, then point a CNAME record at
   YOUR-USERNAME.github.io with your registrar.

   No build step, no Jekyll config, no .nojekyll file needed —
   both files are plain static HTML.

────────────────────────────────────────────────────────────────
WHAT'S IN THE SITE
────────────────────────────────────────────────────────────────
index.html — the whole site in one file:
  Home (hero, Where to begin, How we differ, Start with your goal,
  In their words, founders), Shop, all six product pages, protocol
  bundles, the matching assessment, plan drawer + checkout,
  clinical intake, My account, About + founder letter, founder
  bios, the Journal (shelf archive of ten sample editions with the
  book-opening transition), Contact, State coverage, Privacy
  Policy, Terms & Conditions, Controlled Substance Policy.

faq.html — standalone FAQ page. Reached from "View all questions"
  inside the FAQ view on index.html, and it links back to index.html.
  The header and menu FAQ links open the FAQ in place on index.html.

DEEP LINKS (for ad campaigns — point ads at these, not the home page):
  index.html#shop
  index.html#product/semaglutide
  index.html#product/tirzepatide
  index.html#product/nad
  index.html#product/sermorelin
  index.html#product/micc
  index.html#product/b12

────────────────────────────────────────────────────────────────
LOOSE ASSETS  (for WordPress or any rebuild — not needed to deploy)
────────────────────────────────────────────────────────────────
  welm-hero.mp4 .......... Hero molecular-assembly footage
  welm-rx.png ............ Rx badge
  welm-wordmark.png ...... Wordmark, source with alpha
  welm-wordmark-light.png  Cream wordmark (dark backgrounds)
  welm-wordmark-maroon.png Maroon wordmark (light backgrounds)

  images/product-page/ ... 6 product vials
  images/bundles/ ........ 9 bundle photos
  images/home-page/ ...... team + about portraits
  images/brand/ .......... logo SVGs, LegitScript badge

────────────────────────────────────────────────────────────────
EDITABLE SOURCE  (to make changes later — not needed to deploy)
────────────────────────────────────────────────────────────────
  Welm Health Redesign.dc.html ... main site source
  Welm-FAQ.dc.html ............... FAQ page source
  support.js, image-slot.js ...... runtime
  welm-photos.js ................. embedded photo data
  .image-slots.state.json ........ dropped-image data (hidden file)

  Serve the folder over http:// (not file://) when editing, so the
  image data loads.

────────────────────────────────────────────────────────────────
STILL TO FINALIZE BEFORE LAUNCH
────────────────────────────────────────────────────────────────
  · Product page copy and FAQs are drafts pending Dr. Kelm review.
  · Testimonials are placeholders — swap for real friends-and-family
    reviews (Trustpilot badge once ~100 are seeded).
  · Bundle names, copy and the 15% pricing are placeholders.
  · Nine bundles ship; six are linked from "Start with your goal" on
    the home and shop pages, the other three are reachable from the
    footer under Company → Bundles. A Tirzepatide-micro + NAD+ pairing
    is on hold pending a two-vial product photo.
  · Legal pages still carry the source WellSync / Click to Fill
    entity names — swap for Welm Health LLC.
  · Journal articles are samples written in the Welm clinical voice
    and are NOT physician-reviewed yet — every edition carries a
    "Clinically reviewed by Dr. Ryan C. Kelm, MD" line that must be
    earned before launch, or removed.
  · State coverage is 36 states + Washington, D.C. Update
    this.supportedStates in the source if licensing changes.
