# Portfolio_gun

Personal portfolio website built with HTML, SCSS, and JavaScript.

## Features
- Responsive layout (mobile, tablet, desktop)
- SCSS architecture with partials and variables
- Interactive animations: scroll reveal and vanilla-tilt
- Bundled with Parcel for fast development and builds

## Tech Stack
- HTML5
- SCSS (SASS)
- JavaScript (ES6+)
- Parcel (bundler)
- Bootstrap 5 (utility & grid)
- Optional: jQuery, Popper.js (used for legacy plugins)

## Quick Start
1. Clone the repository:

```bash
git clone https://github.com/bansalgun31/Portfolio_gun.git
cd Portfolio_gun
```

2. Install dependencies:

```powershell
npm install
```

3. Start the development server:

```powershell
npm start
```

4. Build for production:

```powershell
npm run build
```

Parcel will start a local dev server and open the site in your default browser.

## Project Structure

- `src/` — source files
  - `index.html` — main HTML entry
  - `index.js` — main JS
  - `styles.scss` — top-level SCSS
  - `assets/` — images, icons, and data
  - `sass/` — SCSS partials (abstracts, base, components, layout, sections)
  - `scripts/` — custom JS modules (scrollReveal, tiltAnimation)

## Development Notes
- SCSS is organized into partials under `src/sass/` for maintainability.
- Parcel handles module bundling and hot reloading during development.
- If you remove or add dependencies, run `npm install` again.

## Common Commands
- `npm start` — Run dev server with hot reload
- `npm run build` — Create production build in `dist/`
- `npm run lint` — (If configured) Run linters

## Troubleshooting
- If the dev server doesn't start, delete `node_modules` and run `npm install` again.
- If styles don't update, ensure `styles.scss` imports the partials from `src/sass/`.

## License & Credits
This project is provided under the terms in `LICENSE.md`.

