# tasky-web

A responsive landing page for **tasky**, built with vanilla HTML5, CSS, and
JavaScript. No build step, no dependencies.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Features

- Semantic HTML5 landmarks (`header`, `nav`, `main`, `section`, `footer`)
- Responsive layout with CSS Grid and Flexbox
- Light/dark theme toggle (remembers choice in `localStorage`, respects OS preference)
- Mobile navigation menu
- Copy-to-clipboard for the install command
- Accessible: skip link, ARIA attributes, reduced-motion support

## Structure

```
index.html      # markup
css/styles.css  # styles and theme variables
js/main.js      # theme, nav, copy, footer year
```

## Customize

- Colors and spacing live in the `:root` CSS variables in `css/styles.css`.
- Replace the copy in `index.html`; the terminal animation is plain HTML.
