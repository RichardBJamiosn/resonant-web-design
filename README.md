# Resonant Web Design

Static landing-page mockup for a selective web design and services studio.

## Local Preview

```bash
python3 -m http.server 4173
```

Open:

```text
http://127.0.0.1:4173/
```

## Temporary Public URL

```text
https://resonant-web-design.loca.lt/
```

This URL is served through a localtunnel process and stays live only while the local server and tunnel are running on this machine.

## Build Summary

- Brand name: Resonant Web Design.
- Built as a plain static site: `index.html`, `styles.css`, `script.js`.
- Includes original generated hero artwork saved at `assets/img/resonant-studio-hero.png`.
- Portfolio work uses supplied screenshots for OVLP, Rolling Smoke ATX BBQ, DJ Landscaping, and RichardBJamison.com.
- Portfolio grid places Rolling Smoke bottom-left with a mobile showcase panel to its right.
- Stats strip was replaced with selective-client positioning: hundreds of builds, international experience, in-house SEO, all custom work.
- GitHub Pages-ready marker: `.nojekyll`.

## Deployment Notes

GitHub CLI is installed, but the saved GitHub token for `RichardBJamiosn` is invalid. Permanent GitHub Pages hosting is blocked until `gh auth login -h github.com` is completed.
