# Aegis AI & Digital Risk Website v1.7 Executive Consulting Polish

This is a static, multi-page website package for editing in Visual Studio Code and deploying through GitHub + Vercel, GitHub Pages, Netlify, or GoDaddy hosting/cPanel.

## Pages

- `index.html` — Homepage
- `services.html` — Services page
- `assessment.html` — Flagship assessment page
- `about.html` — About/founder-led expertise page
- `contact.html` — Contact page
- `styles.css` — Brand styling and responsive layout
- `script.js` — Mobile navigation behavior
- `assets/` — Aegis logo, icon, and favicon

## Local preview in VS Code

1. Open this folder in VS Code.
2. Install the VS Code extension **Live Server**.
3. Right-click `index.html` and choose **Open with Live Server**.
4. Review the site on desktop and mobile width.

## Recommended deployment path

Recommended: GitHub + Vercel, then point `aegisriskai.com` from GoDaddy to Vercel.

Basic workflow:

```powershell
cd path-to-this-folder
git init
git add .
git commit -m "Launch Aegis website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/aegis-website.git
git push -u origin main
```

Then import the repository into Vercel and add the custom domain in Vercel project settings.

## Contact settings

The public contact path uses:

- `info@aegisriskai.com`
- `privacy@aegisriskai.com`
- `security@aegisriskai.com`

The contact form currently uses `mailto:info@aegisriskai.com`. Replace later with Microsoft Forms, HubSpot, or a secure form backend if needed.

## Launch checklist

- Confirm `aegisriskai.com` ownership and DNS access in GoDaddy.
- Confirm business email inboxes and aliases exist before publishing contact links.
- Add LinkedIn company page URL when available.
- Add capability statement PDF when finalized.
- Test logo, navigation, contact form, desktop view, and mobile view.
- Ask Colin to review the public copy before external launch.

## Logo Update
This v1.3 package uses the supplied current Aegis full-color logo on navy as the primary logo asset.
- Header logo: `assets/aegis-logo-nav.png` — generated from the latest horizontal Aegis lockup provided by the user
- Full logo: `assets/aegis-logo-primary.png` and `assets/aegis-logo-horizontal.png` — updated to the latest horizontal lockup
- Favicon/icon: `assets/favicon.png` and `assets/aegis-icon.png`

## v1.5 favicon update
This package includes the uploaded `favicon.ico` at the website root and in `assets/favicon.ico`.
All HTML pages reference `/favicon.ico` first, with `assets/favicon.png` retained as a fallback.


## v1.7 Logo Asset Update
This package uses the full logo set uploaded after v1.5:

- `assets/aegis-logo-nav.png` — horizontal Aegis lockup used in the site header.
- `assets/aegis-logo-horizontal.png` — horizontal Aegis lockup used in the footer.
- `assets/aegis-logo-primary.png` — full primary stacked logo retained for future hero/brand use.
- `assets/aegis-icon.png` — transparent Aegis icon mark.
- `favicon.ico` and `assets/favicon.ico` — browser favicon.
- `assets/logo-library/` — original uploaded logo files kept for reference.

Use this v1.7 package as the source going forward. Earlier packages v1.2–v1.5 should be treated as archived drafts.


## v1.7 Executive consulting polish
- Reduced oversized heading scale for a more executive advisory feel.
- Reduced hero height and visual glow intensity.
- Enlarged and tightened the horizontal Aegis lockup for the header and footer.
- Kept the icon mark for favicon and supporting brand use only.
- Tuned CTA sizing, card shadows, and section spacing for a more professional consulting-company presentation.
