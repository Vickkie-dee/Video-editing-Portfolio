# Video editing portfolio

Portfolio site for @victory.mp4 (video editing and AI video production). Plain HTML, CSS and a little JavaScript, no build step.

To preview, open `index.html` in a browser. To host it, turn on GitHub Pages (Settings > Pages > Deploy from a branch > main, / root).

## Pages

- `index.html`: home page (hero video loop, portfolio player with two buttons, services, process, reviews, contact)
- `ai-videos.html`: the AI videos portfolio, with filters, search and a project brief form
- `video-editing.html`: the video editing portfolio, with filters, search and a project brief form
- `styles.css`: shared styling
- `assets/thumbs/`: video thumbnails
- `assets/clips/`: the videos that play on the site (portfolio pop-up player, home player and hero)

## How videos play

- Clicking a portfolio card opens a pop-up player with sound. Cards without a video file here still open their Google Drive link.
- The home player and the hero loop play muted until a visitor turns sound on (browsers block autoplay with sound).
- Keep each file small (about 720p, a few MB) so the site loads quickly.

## Notes

- The "Send the Brief" form opens the visitor's email app with the message filled in. It does not send by itself.
- The public repo exposes the contact details written in the pages.
