# Mist & Mug

A fictional educational café concept — Mussoorie, Uttarakhand. Single-file
static site (HTML/CSS/vanilla JS), no build step, no dependencies.

## Deploy on Render

1. Push this repo to GitHub (private is fine once Render is authorized on it).
2. In Render: **New → Static Site** → select this repo.
3. Build Command: leave blank
4. Publish Directory: `.`
5. Deploy.

`render.yaml` is included so you can alternatively use Render's
**New → Blueprint** flow, which reads this file and pre-fills those same
settings automatically.

## Notes

- `index.html` contains everything — markup, styles, and script.
- Find My Cup's AI-assisted step only activates inside Claude's own preview
  environment (see the "About AI" section on the site itself for why). On
  any other host, including this one, it runs in rule-based fallback mode
  automatically and safely — no broken behavior, just no live AI call.
