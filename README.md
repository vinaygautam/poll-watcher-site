# Poll Watcher Website

This is a static website for controlling a locally installed Windows companion.

## Included
- `index.html` — complete website

## Not included
- `PollWatcherSetup.exe` — place your final Windows installer beside `index.html`, or change the install button's `href`.

## Expected desktop integration
The installer should register:
- `pollwatcher://start`
- `pollwatcher://stop`

The website uses those links to ask Windows to open your installed companion.

## Hosting
This can be hosted on GitHub Pages, Cloudflare Pages, Netlify, Vercel, or a normal web server.

A normal browser cannot silently install software. The user still needs to approve the installer/browser prompts the first time.
