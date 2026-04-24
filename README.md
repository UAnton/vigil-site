# Vigil Cloudflare Pages Site

This folder contains a static site for:

- landing page
- privacy policy
- terms of use
- support page

## Deploy to Cloudflare Pages

1. Push this repository to GitHub.
2. In Cloudflare Pages, create a new project from the repo.
3. Set:
   - Framework preset: `None`
   - Build command: leave empty
   - Build output directory: `site`
4. Deploy.

## Files

- `index.html`
- `privacy.html`
- `terms.html`
- `support.html`
- `styles.css`

## URLs to use in App Store Connect

After deployment:

- Privacy Policy URL: `https://<your-pages-domain>/privacy.html`
- Support URL: `https://<your-pages-domain>/support.html`
- Terms of Use: `https://<your-pages-domain>/terms.html`

## Before publishing

Review and update:

- contact email address
- product wording
- effective dates
