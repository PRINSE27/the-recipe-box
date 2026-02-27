# The Recipe Box

Live demo: https://prinse27.github.io/the-recipe-box/

A simple, responsive recipe manager for adding, viewing, editing, and organizing personal recipes. This repository contains the static site (HTML, CSS, JavaScript, and assets) used to power the live demo above.

## Features
- Add new recipes with title, ingredients, and preparation steps
- View recipe details in a clean, readable layout
- Edit and delete recipes
- Search and filter recipes (by name or category)
- Persisted locally using browser localStorage (no backend required)
- Responsive UI for desktop and mobile

## Tech
- HTML, CSS, JavaScript (vanilla)
- localStorage for persistence
- Hosted on GitHub Pages

## Getting started (local)
Option 1 — Open locally:
1. Clone the repo:
   git clone https://github.com/prinse27/the-recipe-box.git
2. Open `index.html` in your browser.

Option 2 — Use a simple local server (recommended):
1. Install a static server (example using npm):
   npm install -g live-server
2. Start the server from the project root:
   live-server

This opens a local dev server and enables live reload on changes.

## Usage
- Click "Add Recipe" (or the form) to create a new recipe — include a title, ingredients (one per line or comma-separated), and step-by-step instructions.
- Use the search box to find recipes by name or ingredient.
- Use edit/delete controls on each recipe to update or remove an entry.
- Recipes are stored in your browser and persist between reloads.

## Customization
- Edit `index.html` to change layout, headings, or form fields.
- Update CSS (likely in `css/` or `styles/`) to change colors, fonts, spacing.
- Modify JavaScript (likely `app.js`, `main.js`, or similar) to change storage behavior (e.g., sync with a backend) or add features (tags, ratings, images).
- Replace or add assets (icons/images) in the `assets/` or `images/` folder and update references.

## Export / Import (optional)
If you add export/import features:
- Export lets you download recipes as JSON.
- Import lets you restore or bulk-add recipes from a JSON file.
- When adding these, ensure you validate imported data to avoid corrupting localStorage.

## Deployment (GitHub Pages)
To publish updates:
1. Commit and push changes to the `main` branch (or the branch configured in repository settings).
2. GitHub Pages will serve the site at:
   https://prinse27.github.io/the-recipe-box/

To use a custom domain, add a `CNAME` file with your domain and configure DNS at your registrar.

## Troubleshooting
- If recipes don’t persist, ensure localStorage is enabled and not full.
- If JavaScript errors occur, check the browser console for stack traces and missing file/network errors.
- If images or assets fail to load, confirm paths and that files are included in the repo.

## Contributing
Contributions are welcome — open a PR for bug fixes, UI/UX improvements, accessibility, performance, or new features (tags, categories, sharing, user accounts). Please include a short description and screenshots for UI changes.

## License
Add a LICENSE file to apply an open-source license (MIT is a common choice).

## Contact
- GitHub: https://github.com/prinse27
- Site: https://prinse27.github.io/the-recipe-box/
