# The Infortainment Company

Single-page landing site. Plain HTML and CSS: no framework, no build step, no JavaScript.

## Files

- `index.html`: the page
- `styles.css`: all styles
- `assets/`: logo, favicon (`favicon.ico`, `apple-touch-icon.png`), social image (`og-image.png`) and `fonts/` (self-hosted Inter Black for the headline, SIL OFL)

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Notes

- Background red is `#f90a0a`.
- `assets/favicon.ico`, `assets/apple-touch-icon.png` and `assets/og-image.png` are placeholders generated from the logo. Replace them with final artwork when ready.
- The `og:image` and `twitter:image` URLs are relative. Social platforms need absolute URLs, so update them to the full domain once hosting is set up.
- Not deployed yet.
