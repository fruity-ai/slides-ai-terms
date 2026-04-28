# AI Terms Slide Deck

Reveal.js 5 slide deck explaining 12 AI/tech terms in Danish, branded for Fruity AI.

## Architecture

- `index.html` — Template engine + CSS + Reveal.js config. Fetches `slides.json` at runtime.
- `slides.json` — All slide content as structured JSON. Edit this to change content.
- `illustrations/` — Pixel-art illustrations (color for term slides, monochrome for dark slides).

## Slide types

7 render functions in index.html: `title`, `term`, `prompt`, `section-divider`, `overview`, `confusions`, `closing`.

## Design system

- Fonts: Karla (headings/body), Fira Code (monospace/labels)
- No border-radius anywhere
- Color tokens defined in `:root` CSS variables
- Dark slides use `data-background-image` with `data-background-opacity="0.2"`

## Local development

```
python3 -m http.server 8767
```

Open `http://localhost:8767/index.html`

## Deployment

Hosted via GitHub Pages from `main` branch at `fruity-ai.github.io/slides-ai-terms`.
