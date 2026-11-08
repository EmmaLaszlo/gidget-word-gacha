# Gidget's Word Gacha 🐾

A pixel-art vocabulary game starring Gidget the maltipoo. Each day there are 5 new
words to collect: send Gidget to fetch one, and she trots off-screen and comes back
carrying a capsule with the word, its pronunciation, definition, and an example
sentence. Collect all 5 to keep your daily streak going.

All of Gidget's sprites (idle, walking, licking, carrying) are hand-drawn pixel art.

**▶ Play it: https://emmalaszlo.github.io/gidget-word-gacha/**

## Features
- 5 words a day from a 50-word bank, picked by a seeded shuffle, so everyone gets the same set each day
- Frame-by-frame walk-cycle animation
- 🔊 Pronunciation with the browser's built-in speech synthesis
- Daily streak and progress saved in the browser with localStorage
- Countdown to the next set, which rolls over at midnight
- Mobile-friendly layout

## Tech
- Plain HTML, CSS, and JavaScript in a single file, with no framework or build step
- Hand-drawn 64×64 PNG sprites embedded as data URIs
- Hosted on GitHub Pages

## Deployment
The game was first deployed on Fly.io as temporary hosting, served from an nginx
Docker container (see the `Dockerfile`). It now lives on GitHub Pages, which
redeploys automatically on every push to `main`.

## Run locally
Open `index.html` in a browser. Add `?dev` to the URL to show a button that resets today's progress.
