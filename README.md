# Ludo Supreme

A browser-based Ludo game with a mobile-first arena layout, dice controls, turn countdown, match timer, and three-missed-turn elimination rules.

## Features

- Mobile-friendly Ludo board and animated dice/token interactions.
- Local play modes, match timer, turn countdown, pause/resume, and new game controls.
- Three missed turns eliminate a player; the last active player wins.
- Online room creation and joining from separate phones using a six-character room code.
- Online matches support 2 or 4 seats and start after all seats connect. The room creator is the host and must remain connected during the match.
- Online communication uses PeerJS/WebRTC; both devices need an internet connection. Peer connection service availability can affect room creation/joining.

## Run locally

Open `index.html` in a modern browser. Tailwind CSS, Google Fonts, and PeerJS are loaded from CDNs, so these features need an internet connection.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the static site when code is pushed to `main`. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source if it is not already selected.

After the first successful workflow run, the site should be available at:

https://skvijay052.github.io/ludo-game/
