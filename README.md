# Music Player (Spotify-Inspired UI)

A simple browser-based music player built with plain **HTML + CSS + JavaScript**. No build tools, no frameworks, no dependencies to install.

## Features

- Play/pause, next/previous
- Seek bar with current time and duration
- Volume control (compact)
- Random and repeat
- Animated “wave” while playing
- Spotify-inspired dark UI with subtle ambient glow per track

## Run Locally

Option 1: open the file directly

1. Open [`index.html`](./index.html) in your browser.

Option 2: serve the folder (recommended)

1. Run a local static server in this folder (any will do).
2. Open the shown `http://localhost:...` URL in your browser.

## Project Structure

- [`index.html`](./index.html): markup
- [`style.css`](./style.css): styling and animations
- [`script.js`](./script.js): player logic and playlist
- [`Images/`](./Images): cover art
- [`music/`](./music): audio files (mp3)

## Customize the Playlist

Edit the `music_list` array in [`script.js`](./script.js) to add/remove tracks:

- `img`: path to cover image
- `name`: track title
- `artist`: artist name
- `music`: path to audio file

## Troubleshooting

- Audio won’t play until you click:
  Most browsers block autoplay. Click the play button once to start playback.
- Missing images or audio:
  Make sure paths in `music_list` match your real filenames exactly (including case). This matters on some hosts.

## Create a Git Repo Here

If you want to turn this folder into a Git repo:

```powershell
git init
git add .
git commit -m "Initial commit"
```

## Credits

- Icons: Font Awesome (loaded via CDN in `index.html`)
- Font: Manrope (loaded via Google Fonts in `index.html`)

Made by AVANTHIKA K S