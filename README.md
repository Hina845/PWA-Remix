# PWA Launcher

A lightweight **Progressive Web App (PWA)** that lets you open any website inside a standalone PWA window.
Think of it as a universal launcher to turn websites into app-like experiences (no address bar, no browser chrome).
Site (or host yourself via localhost or whatever): 

---
## What it does
- Open any URL in a PWA-style window
- Save frequently used sites as shortcuts
- Launch saved sites with one click
- Runs fully offline once installed (except the target sites)

## How to use

1. Install as PWA
	- Open the site in whatever support PWA (Chrome / Edge / Brave)
	- Click Install app (address bar or browser menu)
	- Launch it like a native app
2. Launch a website
	- Enter a URL (e.g. https://figma.com, https://remix.ethereum.org)
	- Click Go → opens inside the PWA window
	- Or Save Shortcut → save to quick start menu
## Notes & limitations

- The opened website must allow being embedded / navigated to
- Some sites may block PWA-style navigation due to security headers
- Favicons are fetched via Google’s favicon service
- This PWA acts as a launcher, not a site wrapper per domain

## Why this exists
- Browser tabs are chaos. Sometimes you just want: this site, as an app. End of story.
- Sure, fullscreen works — but good luck summoning the taskbar without breaking flow.
- Extensions, search bars, buttons everywhere… and your focus? Gone.

## License

MIT — do whatever you want with it.