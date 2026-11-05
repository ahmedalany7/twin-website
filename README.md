# Twin – Our Love World: public site

Static pages only (home, privacy policy, terms of use, account deletion; Arabic and English). No script, no tracking, no external resources.

- `public/` is what GitHub Pages serves. It is generated from the main Twin project (`node scripts/build-site.mjs --final --site-repo <this folder>`): do not edit it by hand.
- `.github/workflows/pages.yml` publishes `public/` on every push to `main`, after a guard that refuses drafts, app code and secret-like files.
- A page that still shows "Draft for review" is a draft: it is not final legal text.

Contact: ENG. Ahmed Alany · mhdmoutazhammad@gmail.com · https://t.me/Ahmedwaad7 · +79873380804
