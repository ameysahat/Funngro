# Funngro — Premium Landing Pages

A lightweight, responsive, three-page static website concept for Funngro.

## Included

- `index.html` — homepage with two audience journeys
- `teen.html` — teen-focused information page
- `company.html` — company/brand campaign page
- `styles.css` — shared responsive design system
- `script.js` — accessible mobile navigation and current-year footer
- `404.html` — custom not-found page
- `assets/favicon.svg` — site icon
- `assets/og-cover.svg` — social sharing graphic
- `robots.txt` and `sitemap.xml` — starter SEO files

## Run locally

No build step, package manager or framework is required.

### Option A: open directly

Open `index.html` in a browser.

### Option B: local server (recommended)

From this folder run:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy to GitHub Pages

1. Open the `ameysahat/Funngro` repository on GitHub.
2. Replace the existing `index.html`, `teen.html`, `company.html`, `styles.css`, `script.js`, `robots.txt` and `sitemap.xml` with these files.
3. Add `404.html` and the `assets/` folder.
4. Commit the changes to the branch configured for GitHub Pages (usually `main`).
5. In GitHub, open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select `main` and `/ (root)`, then save.
8. Wait for the Pages deployment to finish. Your site should be available at:
   <https://ameysahat.github.io/Funngro/>

## Before publishing

- Confirm you own or are authorized to publish the Funngro name, logo and content.
- Confirm the official production domain. This starter is configured for the GitHub Pages URL `https://ameysahat.github.io/Funngro/`. If using a custom domain, update canonical URLs, Open Graph URLs, `robots.txt` and `sitemap.xml` consistently.
- Confirm every external destination and current platform feature.
- Verify age eligibility, guardian-consent requirements, safety processes, privacy terms, rewards and payout conditions with Funngro. This concept intentionally avoids making unverified promises.
- Replace the SVG social preview with an approved brand asset if required by brand guidelines.
- Test mobile layouts, keyboard navigation, contrast, links and forms before launch.

## Contact links and functionality

The company CTA points to the official Funngro contact page. The teen CTA points to the official Funngro website. These pages are informational landing pages; they do not create user accounts, accept project applications, process payments or store enquiries.

A production enquiry form requires an approved backend or form provider and a privacy notice. Do not collect teen personal information without a reviewed legal, privacy and safeguarding process.

## Design notes

The design uses a dark aubergine base, lavender surfaces and lime accents, with responsive layouts and reduced-motion support. Google Fonts are loaded remotely; system fallbacks are included.
