# December Creative Showcase: Maze Advertising

An interactive Christmas presentation of the December content ideas for 11 clients (24 ideas, 37 slides).

## How to open
1. Unzip the folder anywhere.
2. Double-click **index.html** (Chrome, Edge, Safari or Firefox). Everything uses relative paths, so it works offline and can be moved between computers.
3. Optional, if a browser blocks local video: open a terminal in this folder and run `python3 -m http.server 8000`, then visit http://localhost:8000.

## Controls
- Next / previous: on-screen buttons, ← → keys, or swipe on touch screens.
- **Clients** button (top left), the Home key or Esc: back to the client directory.
- Dots (top right): jump between the current client's introduction and ideas.
- Progress bar (bottom): one segment per client; click a segment to jump there.
- Click a photo to enlarge it (← → browse photos in the viewer, Esc closes).
- Videos load only when their slide opens and never autoplay. Press play; sound is on when you play.
- Links like `index.html#garden-avenue-4` open a specific slide.

## Project structure
```
index.html   styles.css   script.js   data.js
assets/
  christmas-elements/   all 80 supplied decorative files
  vip/ altunsa/ asan/ furat/ garden-avenue/ garden-city/ bricks/ imperial/ hps/ zhala/ joytown/
                        original client files, names unchanged
  logos/                trimmed display copies of each logo (empty margins removed; originals stay in the client folders)
```
`data.js` holds every client, idea, description and media link. To edit text or swap media, change `data.js` only.
To show a client description on the directory card and the client page, fill in that client's `"desc"` field.

## Notes
- The Joy Town `.mov` was also saved as `carousel game video.mp4` (lossless re-wrap, no re-encoding) so it plays in every browser. The original `.mov` is still in the folder.
- Fonts are system fonts, and there are no external links or dependencies.
- Snow, lights and swinging ornaments are switched off for visitors whose system requests reduced motion.

See **MEDIA_REPORT.md** for the media matching and the items that need your review.
