# Himanshu Portfolio Site

Open `index.html` in a browser to view the site.

## Replacing Photos

The current placeholder is:

`assets/photo-placeholder.svg`

To add real photos later, place image files in `assets/` and update the matching
`src` values in `index.html`. Good slot sizes:

- Portrait: vertical 4:5 image
- Behind the scenes: vertical 4:5 image
- Stage / Event: vertical 4:5 image

## Replacing Work Images

Each portfolio card also has its own image placeholder:

- Aurum Models: `assets/work-aurum-placeholder.svg`
- Production / Unjellic: `assets/work-production-placeholder.svg`
- Outreach / Uphoria: `assets/work-outreach-placeholder.svg`
- Stage / Panache: `assets/work-stage-placeholder.svg`

For example, add `aurum-showcase.jpg` inside `assets/`, then in `index.html`
change:

`assets/work-aurum-placeholder.svg`

to:

`assets/aurum-showcase.jpg`

Wide landscape photos work best here, roughly `16:9` or `3:2`.

## Main Files

- `index.html` - content and sections
- `styles.css` - visual design and responsive layout
- `assets/growth-signal.svg` - hero background artwork
- `assets/photo-placeholder.svg` - reusable photo placeholder
- `assets/work-*-placeholder.svg` - portfolio work image placeholders
