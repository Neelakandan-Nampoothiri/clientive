# Clientive

A small React + Vite frontend (landing/marketing) scaffold used in this workspace. Built with Vite, React 19, and a simple ESLint configuration.

**Key features**
- Fast dev server with HMR using Vite
- Modern React (hooks + components)
- Lightweight component structure for a landing page (Hero, Services, Teams, Contact, etc.)

**Tech stack**
- React 19
- Vite
- ESLint
- Dev tooling: @vitejs/plugin-react

## Repo structure

Top-level project files live in this folder. Important source files:

- `index.html` — Vite entry HTML
- `src/main.jsx` — App bootstrap
- `src/App.jsx` — Root component
- `src/index.css` — Global styles
- `src/assets/assets.js` — image/asset references
- `src/components/` — UI components (see list below)

Notable component files in `src/components`:

- `Navbar.jsx`
- `Hero.jsx`
- `Services.jsx`
- `ServiceCard.jsx`
- `OurWork.jsx`
- `Teams.jsx`
- `TrustedBy.jsx`
- `ContactUs.jsx`
- `Footer.jsx`
- `ThemeToggleBtn.jsx`
- `Title.jsx`

## Available scripts

Run these from the `proj` folder.

- Install dependencies

```bash
npm install
```

- Start development server (HMR)

```bash
npm run dev
```

- Build for production

```bash
npm run build
```

- Preview the production build locally

```bash
npm run preview
```

- Lint the codebase

```bash
npm run lint
```

## Development notes

- The project uses Vite (`vite.config.js`) and the React plugin (`@vitejs/plugin-react`).
- ESLint config is in `eslint.config.js` and can be adjusted to match your preferred rules.
- If you add assets, update `src/assets/assets.js` to export or reference them consistently.

## Contributing

Small changes are welcome. For larger features, create a branch and open a PR against `main`.

## License & contact

This repository does not include a license file. Add one if you intend to publish or share the project.

If you need help running or extending the project, open an issue or contact the maintainer.
