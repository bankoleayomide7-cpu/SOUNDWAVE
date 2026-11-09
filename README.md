# Soundwave — React Music Explorer

A standalone React + Vite music discovery website with a familiar streaming-service feel but original branding and interface. It connects directly to Apple's iTunes Search API; no API key or account is needed.

## Pages and routes
- `/` Home with popular music searches, an Afrobeats section and album picks.
- `/discover` Curated search categories.
- `/charts` Popular catalogue searches presented as ranked lists.
- `/artists` Artist catalogue search.
- `/albums` Album catalogue.
- `/album/:id` Album detail and track listing.
- `/podcasts` Podcast catalogue.
- `/search?q=...` Search results.
- `/library` Locally saved tracks.

## Features
- Live API search and catalogue requests.
- Responsive album artwork and track cards.
- Playable short audio previews where Apple provides a preview URL.
- Save tracks to a local library using browser localStorage.
- Category chips, search navigation, loading and error states.

## Run in VS Code
1. Install Node.js (LTS).
2. Extract the ZIP and open the `soundwave` folder in VS Code.
3. Open Terminal > New Terminal.
4. Run `npm install` then `npm run dev`.
5. Open the localhost URL printed by Vite.

## API
Apple iTunes Search API: https://performance-partners.apple.com/search-api
Requests use `https://itunes.apple.com/search` and `https://itunes.apple.com/lookup`. The API is free and does not require an API key. Apple requires promotional use of artwork and audio previews to comply with its terms; previews should be shown in proximity to the relevant store badge/link. Review Apple's current terms before public or commercial use.
