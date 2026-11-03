# Sanwriya Catering website (Phase 1: public website)

Pure vegetarian catering website with a cinematic hero, a thali that fills up as you scroll, a 100-dish menu with a custom menu builder, sample packages, gallery and a quote request form.

## Files
- `index.html` the whole website (styles and scripts included)
- `img/hero/` the 7 photos used in the rotating hero
- `img/dishes/` the 100 dish photos (file name = dish name)
- `favicon.svg`, `404.html`, `.nojekyll`

## 1. Add your business details
Open `index.html`, search for `CONFIG` and fill in the values:

    whatsapp, phone, email, address, mapsLink, instagram, googleReviews

Until a value is filled in, its button shows a "not added yet" message instead of doing nothing. The quote form sends the request to your WhatsApp number once `whatsapp` is set.

## 2. Replace photos with real Sanwriya photos
Upload a new JPG with the same file name into `img/dishes/` or `img/hero/`. For example, replace `img/dishes/dal-makhani.jpg` with your own photo. Square photos (about 900 x 900) work best.

## 3. Edit packages
In `index.html`, search for `PKGS`. The three packages are samples. Change the names, text and dish list (use the file names without `.jpg`).

## 4. Deploy on GitHub Pages
1. Create a public repository (name it `rupali140.github.io` for a link with no repo name).
2. Upload everything in this folder (including `img/`) to the main folder of the repo.
3. Settings > Pages > Deploy from a branch > `main` and `/ (root)` > Save.

## Not in this phase
Customer login, bookings, admin dashboard, quotations, payments, receipts and reports are later phases and need a backend (Supabase) and a payment gateway. This version saves nothing on a server. A visitor's custom menu is kept only in their own browser.
