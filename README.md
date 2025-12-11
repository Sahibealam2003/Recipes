App Link:- https://recipesappfe.netlify.app/
(only UI search functionality not included it will added soon)

# Recipes

[![Repo size](https://img.shields.io/github/repo-size/Sahibealam2003/Recipes)]()
[![Languages](https://img.shields.io/github/languages/top/Sahibealam2003/Recipes)]()
[![Issues](https://img.shields.io/github/issues/Sahibealam2003/Recipes)]()

A small, static recipes website built with plain HTML, CSS and JavaScript. The project provides a simple interface to browse recipe listings and view recipe details. It's a front-end-first project — no build step or server required to run locally.

Table of contents
- [What this project does](#what-this-project-does)
- [Why this project is useful](#why-this-project-is-useful)
- [Getting started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Quick start (open in browser)](#quick-start-open-in-browser)
  - [Serve locally (recommended)](#serve-locally-recommended)
- [Project structure](#project-structure)
- [How to use](#how-to-use)
- [Where to get help](#where-to-get-help)
- [Who maintains and contributes](#who-maintains-and-contributes)
- [Contributing](#contributing)
- [License](#license)

## What this project does
Recipes is a static front-end project that shows a list of recipes and recipe detail pages. The UI and interactions are implemented in client-side JavaScript (main.js) and markup files (index.html and recipe.html). It is intended as a small demo or starter template for recipe websites and small front-end projects.

## Why this project is useful
- Minimal, dependency-free starter for front-end learning or demos.
- Easy to fork and extend into larger recipe/catalog sites.
- Good basis for experimenting with:
  - Client-side routing or templating
  - Adding a JSON data source or localStorage persistence
  - Converting to a framework (React/Vue) or adding a backend API

## Getting started

### Prerequisites
- A modern browser (Chrome, Firefox, Edge, Safari)
- Optional for serving locally: Node.js (for `npx serve`) or Python (for `python -m http.server`)

### Quick start (open in browser)
1. Clone the repository:
   git clone https://github.com/Sahibealam2003/Recipes.git
   cd Recipes

2. Open the site:
   - Double-click `index.html` in the project root, or open it with your browser.

Note: Some browsers restrict features (like fetching local files) when opening files directly. If you see errors, use a local static server as described below.

### Serve locally (recommended)
Run a simple static server from the project root so routes and assets behave reliably:

- Using Python 3:
  python -m http.server 8000
  Open http://localhost:8000

- Using Node (serve):
  npx serve .
  Open the URL printed by `serve`

This will ensure navigation between `index.html` and `recipe.html` works as expected.

## Project structure
- index.html — Main listing page for recipes
- recipe.html — Recipe detail page template
- main.js — Client-side JavaScript that powers the UI and interactions
- hero.svg, hero2.svg, name.nav.1.svg — Visual assets used by the pages
- README.md — This file

(If you add CSS, assets, or scripts, place them in appropriate subfolders such as `css/`, `assets/`, `js/`.)

## How to use
- Browse recipes on the main page (`index.html`).
- Click a recipe to open its details (served via `recipe.html`).
- To add or edit recipe data, update the relevant HTML or the JavaScript data structures in `main.js`. The project is intentionally simple so data can be edited inline while prototyping.

Example: open `main.js` and look for the recipes array or loader function (simple edits will appear after reloading the page).

## Where to get help
- Open an issue in this repository for bugs, feature requests, or questions: Issues → New Issue.
- If you want to propose larger changes, open a pull request with a clear description of the change.

## Who maintains and contributes
Maintained by: Sahibealam2003

If you want to contribute, please read the repository's contribution guidelines:
- CONTRIBUTING.md (if present) — use the repository's contributor guidelines
- Otherwise, open an issue to discuss larger changes before submitting a PR

## Contributing
Short contributing guidance for developers:
1. Fork the repo and create a branch: `git checkout -b feat/my-change`
2. Make changes and test locally (see "Serve locally")
3. Commit with a clear message and push your branch
4. Open a Pull Request describing the change and link any related issues

For full contribution guidelines, add a `CONTRIBUTING.md` file and link it here:
- See `CONTRIBUTING.md`

Do not include large generated files in PRs. Keep changes focused and well-documented.

## License
See the LICENSE file in this repository for license details.

