# Rizal High School Sports Center

A responsive HTML/CSS/JavaScript tournament management dashboard inspired by the provided designs.

## Run in VS Code (This is optional. No need to download the ZIP file.)
1. Extract the ZIP file.
2. Open the `rizal-sports-tournament` folder in VS Code.
3. Run `index.html` using the **Live Server** extension (recommended), or open `index.html` directly in a browser.
4. Choose **Create account** to make a local demo account, or use **Continue with Google (demo)** to enter the dashboard immediately.

No build step or npm packages are required.

## Included features
- Demo account creation and sign-in, sign-out, account profile editing.
- Create, read, update, and delete teams.
- Team captain, standings, win/loss/draw records, win rate, and tournament points.
- Record and delete match results. A non-draw win automatically awards 3 points.
- Add, deduct, or set exact team points, with a point-adjustment audit history.
- Overview, Team Records, Scores, Point Controls, and Settings pages.
- Light/dark/system theme selection and compact dashboard toggle.
- JSON backup export and JSON backup import.
- Responsive layouts for desktop, tablet, and mobile.

## Data and security notes
- Application data and demo accounts are stored in the browser's `localStorage`.
- `data.json` is a sample/empty JSON structure for reference. The browser app does not write directly to this file; use **Settings → Data & backup → Export JSON backup** to download current data as JSON.
- The authentication is a local demonstration only. Passwords are not securely hashed and there is no server/database. Do not use real passwords or sensitive data.
- For a production deployment, replace local demo authentication/storage with a backend API, hashed passwords, session management, authorization, and a database.
