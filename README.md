# Twenty Hours

A static site. No build step, no server code, no dependencies.

## Files
- `index.html` — the whole app
- `manifest.json` — makes it installable to a phone home screen
- `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-180.png` — the app icon

## To publish (any one of these, all free)
- **Cloudflare Pages** — create a project, "Direct Upload", drag this folder in.
- **Netlify** — netlify.com/drop, drag this folder in.
- **GitHub Pages** — push these files to a repo, Settings → Pages → deploy from branch.

Serve the folder at the site root. Nothing here needs HTTPS to work, but installing
to a home screen does — every host above gives you HTTPS by default.

## To install on a phone
- **iPhone (Safari):** Share → Add to Home Screen.
- **Android (Chrome):** menu → Install app / Add to Home screen.

## Where the data lives
In the browser's local storage, on that one device. It is never sent anywhere,
and it is not shared between people. Clearing site data erases it.
