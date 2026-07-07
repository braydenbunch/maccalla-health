# The MacCalla Agency — final multi-page static site

This version fixes the routing issue and makes the service pages look like the homepage.

## Important
Upload the entire ZIP contents to GitHub/Netlify. Do not upload only `index.html`, because the navigation needs the other `.html` files and the `assets` folder.

## Pages included
- `index.html`
- `the-basics.html`
- `original-medicare.html`
- `medicare-advantage.html`
- `part-d.html`
- `med-supp.html`
- `ancillary.html`
- `aca.html`
- `about-us.html`
- `contact-us.html`
- `privacy-policy.html`
- `terms-of-service.html`
- `thank-you.html`
- `404.html`

## Routing fixes
- Navigation uses direct static links like `part-d.html` so GitHub Pages and normal file previews work.
- Netlify `_redirects` supports clean URLs like `/part-d` and `/part-d/`.
- Fallback folders like `/part-d/index.html` are included to prevent clean-URL 404s on simple static hosts.

## Link approach
Only the nav, buttons, contact info, footer/legal, and official resources are clickable. Service cards are not links.

## Contact
Phone: 321-382-4787
Email: melissa@machealthagency.com
Address: 3370 Garden St. Titusville, FL 32796
