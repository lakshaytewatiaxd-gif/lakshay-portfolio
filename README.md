# Lakshay Tewatia — Portfolio

A clean, dependency-free static portfolio site built with HTML, CSS, and a small amount of vanilla JavaScript.

## Sections

- Hero / academic snapshot
- About
- Education
- Technical skills
- Selected project
- Certifications
- Contact

## Run locally

No build step or package install is needed.

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

The site is ready for GitHub Pages or any static host:

1. Push these files to the `main` branch of a GitHub repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` / `root`.
4. Save. Your site will be available at `https://<username>.github.io/<repository>/`.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Page content and semantic structure |
| `styles.css` | Layout, typography, colors, and responsive rules |
| `script.js` | Mobile menu, footer year, and active navigation state |
| `favicon.svg` | Site icon |

No tracking scripts, third-party embeds, or generated-page branding are included.
