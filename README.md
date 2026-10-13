# Jiu-Jitsu Nordfjord website

Static, responsive, bilingual website ready for GitHub Pages.

## Structure
- `index.html`: Norwegian one-page website
- `en/index.html`: English one-page website
- `personvern.html` / `en/privacy.html`: privacy information
- `assets/css/style.css`: shared design
- `assets/js/main.js`: mobile menu, language preference, email handoff
- `assets/images/`: logo, banner and app icons

## Publish on GitHub Pages
1. Upload the contents of this folder to the root of a GitHub repository.
2. In repository Settings > Pages, select deployment from the main branch and root folder.
3. Replace every `[FYLL INN ...]` / `[INSERT ...]` placeholder before publishing.
4. Replace canonical, hreflang, sitemap, robots and JSON-LD placeholders with the final domain.

## Legal and technical pre-publication checklist
- [ ] Confirm official club/organisation name, registration number, address and controller.
- [ ] Confirm the lawful basis and email retention period.
- [ ] Record GitHub Pages, domain provider and email provider as relevant suppliers/processors.
- [ ] Check whether any supplier transfers data outside the EU/EEA and document safeguards.
- [ ] Confirm publishing rights and consent for the logo, banner, and future photos, especially images of children.
- [ ] Confirm training times, age limit, prices, contact details and instructor claims.
- [ ] Replace all URL placeholders in HTML, `robots.txt`, `sitemap.xml`, and JSON-LD.
- [ ] Test Norwegian/English navigation, mobile menu, phone links and email form.
- [ ] Test keyboard navigation, contrast, alt text and reduced motion.
- [ ] No analytics, advertising pixels, external fonts, maps, videos or embedded social feeds are included.
- [ ] The only browser storage is `localStorage` key `preferredLanguage`; no cookies are set by this code.
- [ ] If analytics, maps, videos, social embeds or third-party forms are added later, review consent and cookie requirements before loading them.
- [ ] The contact form uses `mailto:` and stores no submissions in the repository or website.
- [ ] Never commit passwords, API keys, personal submissions or secrets.

## Images
`logo.jpg` is the supplied club logo. `banner.png` is an AI-generated visual and should be replaced if the club prefers an approved original photograph.
