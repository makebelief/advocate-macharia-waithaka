# Advocate Macharia Waithaka — Website

Static, Vercel-compatible multi-page website based on the established C.O. Were website design.

## Brand & contacts
- Firm: Advocate Macharia Waithaka (supplied logo reads ADVOCATE MACHARIA+WAITHAKA)
- Phone / WhatsApp: +254 701 421 511
- Email: advocatemacharia.waithaka@proton.me
- Street address: **not independently confirmed**. Do not publish a guessed office address.
- Public Lawzana directory lists Nairobi; supplied background includes Nyeri as a profile location, not a confirmed street office.

## To preview locally

Run `python3 -m http.server 8000` in this directory, then open `http://localhost:8000/`.

## Deploy

1. Create GitHub repo via `gh repo create advocate-macharia-waithaka --public --source=. --remote=origin --push` after `git init`, `git add -A` and `git commit`.
2. Deploy with `npx vercel --prod` (choose **Other**, serve files from project root; no build step).
3. If Vercel assigns a different production domain, replace `https://advocate-macharia-waithaka.vercel.app` in HTML, robots.txt and sitemap.xml and redeploy.

## Notes
- Pexels photographs are illustrative; they are **not** portraits of firm members. Original Pexels URLs are recorded in PHOTO-SOURCES.md.
- Personal portraits and logo supplied by the user.
- High-resolution logo files are **upscaled and extracted from the original JPEG**; they are not native vector artwork.
- The enquiry form prepares a mailto email draft in the visitor's email app; there is no back-end form processing.
- Verify the spelling/placement of the office and the WhatsApp account before using the demo commercially.
- SEO: individual canonical pages, semantic heading structure, LegalService schema, sitemap.xml and robots.txt. Submit sitemap to Search Console after publishing.
- Copyright/legal information is general and does not imply engagement.
