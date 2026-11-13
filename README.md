# Village Timer — Clash of Clans Home Village

A mobile-friendly, single-page Home Village upgrade tracker.

## App features

- Import your in-game village Data Export JSON
- Display active upgrade and research timers
- Add and remove timers manually
- Save timer data in this browser using local storage
- No Supercell login or API key required
- Designed for iPhone Safari and desktop browsers

## Open the app

**Project Pages URL:**

https://thevwpololover.github.io/Upgrade_timer_widget/

This is a project site, so the repository name is part of the URL. Do not open only `https://thewpololover.github.io/`—that is the account's root site and is not this repository's project site.

## GitHub Pages deployment

This repository includes an automatic GitHub Actions deployment workflow at `.github/workflows/pages.yml`.

1. Open **Settings → Pages**:
   https://github.com/TheVWpoloLover/Upgrade_timer_widget/settings/pages
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Save if GitHub displays a Save button.
4. Open the **Actions** tab and select **Deploy Village Timer to GitHub Pages**.
5. Confirm the most recent run finishes with a green check.
6. Open the Project Pages URL above.

The workflow runs automatically after each push to `main`, and can also be run manually from the Actions tab.

### Alternative: branch publishing

If you prefer not to use the workflow, remove/disable the Actions workflow and select **Deploy from a branch**, branch `main`, folder `/(root)` in Settings → Pages. Do not mix the two deployment methods.

## Required root files

- `index.html` — app entry point. Keep this exact lowercase filename in the repository root.
- `.nojekyll` — asks GitHub Pages to serve this as a plain static site.
- `404.html` — friendly not-found page.
- `.github/workflows/pages.yml` — automated Pages deployment workflow.

## Local data and privacy

Imported export data is processed in the browser. Timers are saved in browser local storage. Clearing the browser's site data may remove saved timers. Do not commit private game exports to this public repository.

## Limitations

This is an unofficial client-side tracker, not a Supercell product. Timers recalculate from their saved end times when the page is reopened. iOS Safari may suspend background activity, so this page cannot guarantee second-by-second background updates or provide a native iOS widget.

## Artwork and credits

Upgrade artwork uses public Clash of Clans image assets served by [ClashKing Assets](https://assets.clashk.ing/). Asset paths follow the published asset directory structure. Please credit ClashKing Assets when reusing these hosted files. Clash of Clans names and artwork belong to Supercell; this is an unofficial fan project and is not affiliated with or endorsed by Supercell.

The interface uses a Clash-inspired warm wood, stone, and gold colour palette. The game artwork is loaded separately from the asset host, so images require an internet connection; emoji fallbacks appear if an image cannot be loaded.
