# KasiConnect

**KasiConnect** is a mobile-friendly community opportunity directory concept for discovering local jobs, services and small businesses. It is designed around a simple idea: useful opportunities should be easier to find close to home.

## Features in this prototype

- Browse sample listings across Jobs, Services and Small businesses
- Search by title, organisation, description, category or area
- Filter by category and selected Johannesburg-area communities
- Sort listings alphabetically or by recent demo listing order
- Save listings for the current browser session
- Submit a new demo listing using the “Post an opportunity” form
- Responsive layout for desktop and mobile screens
- Accessible labels, modal close controls and keyboard Escape support

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser, or use the VS Code Live Server extension.
3. No package installation or build step is required.

## Project structure

```text
KasiConnect/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
└── README.md
```

## Important prototype limitations

This is a front-end demonstration, not yet a production service. The included opportunities are sample data and are **not verified vacancies or verified service providers**. Newly added listings and saved items are held in browser memory for the current session; they are not shared with other users and are not stored in a central database. Contact and safety checks are not implemented.

Before a real launch, add a secure backend/database, authentication, moderation and reporting, verified business profiles, privacy controls, contact verification, and anti-scam measures. Test with community members before relying on the service.

## Deployment with GitHub Pages

1. Create a new public GitHub repository named `kasiconnect` (or another name you prefer).
2. Upload the contents of this folder, keeping `index.html`, `css/`, and `js/` at the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for the deployment to finish and open the Pages URL shown by GitHub.

## Suggested next steps

- Interview local job seekers, small businesses and service providers to validate the problem.
- Add a database and secure user accounts.
- Build listing review and verification workflows.
- Add reporting, privacy and anti-fraud controls.
- Measure active users, legitimate enquiries and successful connections.

## Project pitch

KasiConnect brings local jobs, services and small businesses into one simple community directory, helping people discover nearby opportunities and helping local providers reach the people around them.
