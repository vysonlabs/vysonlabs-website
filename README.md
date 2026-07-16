# Vyson Labs Website

Static public website for Vyson Labs Limited, prepared for deployment to Netlify at `https://vysonlabs.com`.

## Structure

- `index.html` - main company website
- `privacy/index.html` - privacy policy
- `terms/index.html` - terms of use
- `assets/css/styles.css` - site styles
- `assets/js/main.js` - mobile navigation
- `netlify.toml` and `_redirects` - Netlify configuration
- `robots.txt` and `sitemap.xml` - search engine metadata

No database, backend, analytics, contact form, or build step is required for the first release.

## Netlify build settings

This is a plain static site. Use these Netlify settings:

- Build command: leave blank
- Publish directory: project root (`.`)
- Production branch: `main`

The primary production URL should be `https://vysonlabs.com`. Configure `https://www.vysonlabs.com` to redirect permanently to the root domain. Preserve existing Zoho Mail DNS records when connecting the domain.

## Pre-submission checks

Before Apple Developer Program resubmission, confirm the live domain uses HTTPS, the `www` redirect works, Zoho email still sends and receives, and the site works in a private browser window and on mobile data.
