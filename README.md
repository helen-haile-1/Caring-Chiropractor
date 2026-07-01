# Advantage Rehabilitation & Wellness Center Website

A redesigned marketing site for Advantage Rehabilitation & Wellness Center (Dr. Rashida Cohen), Washington, DC.

## Structure

```
.
├── index.html        Main page markup
├── css/
│   └── style.css      All styles
├── js/
│   └── main.js        Mobile nav toggle
├── images/            Real practice photos (Dr. Cohen, patients, pediatric care)
└── README.md
```

## Running locally

No build step needed. Open `index.html` directly in a browser, or serve the folder with any static server, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Editing

- Colors and fonts are defined as CSS variables at the top of `css/style.css` (the `:root` block), so palette or type changes only need to happen in one place.
- Fonts used: **Baloo 2** (headings) and **Nunito** (body text), loaded from Google Fonts in `index.html`.
- Content sections (hero, services, about, process, testimonials, contact) are laid out in order inside `index.html` with matching class names in `style.css`.

## Deploying

This is a static site. It can be hosted as-is on GitHub Pages, Netlify, Vercel, or any static host by pointing it at `index.html`.
