# viabaltic.lt

Website of Via Baltic Partners (operated by Spessartia UAB). A static single-page site with no build step.

## Files
- `index.html` contains the whole page: markup, styles, script and the inline SVG illustration and logo.
- `img/` holds the partner portraits.
- `fonts/` holds Hanken Grotesk, self-hosted so the site makes no requests to Google.
- `favicon.svg` is the browser tab icon.

## Contact form
The form posts to `FORM_ENDPOINT`, a constant near the bottom of `index.html`. While it is empty, the form asks visitors to email info@viabaltic.lt instead. Set it to the form service URL (for example Formspree or Web3Forms) before launch.

## Open items
- Lithuanian version
- Lawyer review of the privacy notice and disclaimer
