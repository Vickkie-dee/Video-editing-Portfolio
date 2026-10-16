# Video editing portfolio

Single-page portfolio for @victory.mp4 (video editing and AI video production).

- `index.html` holds the whole site: HTML, CSS and a little JavaScript, with thumbnails embedded.
- Open it in a browser to preview, or turn on GitHub Pages (Settings > Pages > Deploy from a branch > main, / root) to host it.

## Pages

- `index.html`: home page (hero, portfolio player + two buttons, services, process, reviews, contact)
- `ai-videos.html`: the AI videos portfolio, with its own filters
- `video-editing.html`: the video editing portfolio, with its own filters
- `styles.css`: shared styling
- `assets/thumbs/`: video thumbnails
- `assets/clips/`: put short preview clips here (see below)

## Adding preview clips to the home page player

The player on the home page shows thumbnails until a video file is set for an item. To make an item play real video, add its short `.mp4` to `assets/clips/` and set that item's `"clip"` in `index.html` (for example `"clip": "assets/clips/ai-ugc.mp4"`). Clips start muted; visitors tap the sound button to hear them.
