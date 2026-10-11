# Shreyas Shirke — Portfolio

Personal portfolio for **Shreyas Shirke**, Business Analyst · Project Operations · M.S. Project Management at Northeastern University (Dec 2026), Boston, MA.

**Live site:** https://shreyu311.github.io
**Résumé:** [Shreyas_Shirke_Resume.pdf](./resume/Shreyas_Shirke_Resume.pdf?v=20261011)

## What's on the site

- **Selected work:** UI/UX Guidelines & Design System, Portfolio Report Agent (Actuals vs Forecast automation), and an IT-transformation capstone
- **Experience, education & skills:** kept in sync with the résumé PDF

## Structure

```
index.html          Single-page site (HTML, inline CSS and JS)
404.html            Not-found page
favicon.svg         Site icon
images/             Photos and the link-preview card (og-card.png)
resume/             Current résumé PDF (one file only)
robots.txt          Crawler rules
sitemap.xml         Pages for search engines
```

Hosted on GitHub Pages from the `master` branch. No build step.

## Updating the résumé

1. Replace `resume/Shreyas_Shirke_Resume.pdf` with the new PDF (same file name).
2. In `index.html` and this README, bump the `?v=YYYYMMDD` query on every résumé link so browsers fetch the new file.
3. Update any site text that changed on the résumé, then commit and push to `master`.
