# Village Timer — Clash of Clans Home Village

A mobile-friendly, single-page Home Village upgrade tracker for Clash of Clans.

## Features

- Import your in-game village Data Export JSON
- Show active upgrade/research timers and estimated completion times
- Add and remove timers manually
- Save tracker data in this browser using local storage
- No Supercell login or API key required
- Designed for iPhone Safari and desktop browsers

## Open the app

After GitHub Pages is enabled, the site URL is:

https://thewpololover.github.io/Upgrade_timer_widget/

The repository name is case-sensitive in the project-site path. Keep the `Upgrade_timer_widget` spelling and capitalization exactly as shown.

## Enable GitHub Pages

1. Open **Settings → Pages** for this repository:
   https://github.com/TheVWpoloLover/Upgrade_timer_widget/settings/pages
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Press **Save**.
5. Wait for the Pages deployment to finish. Check the **Actions** tab for the Pages build/deployment workflow if the site does not appear.

The published source must have `index.html` at its top level (not inside another folder). The filename must be lowercase.

## Local data and privacy

Imported data is processed in the browser. The tracker stores its timers in browser local storage. Clearing browser/site data may remove locally saved timers. Do not put private information into this public repository.

## Limitations

This is a client-side tracker, not an official Supercell product. Browser countdowns update while the page is open and recalculate from saved end times when reopened. iOS Safari may suspend background activity, so this page cannot promise second-by-second background updates or a native iOS widget.

## Repository structure

```
.
├── index.html      # App entry point (required by GitHub Pages)
├── 404.html        # Friendly not-found page
├── .nojekyll       # Disable Jekyll processing for this static app
└── README.md       # Setup and usage instructions
```
