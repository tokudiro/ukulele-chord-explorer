# Ukulele Chord Explorer

A single-file, no-build web app for exploring ukulele chord voicings across the entire fretboard (0–15th fret) — from open-position shapes to high-position "ultra" voicings.

**Live demo:** https://tokudiro.github.io/ukulele-chord-explorer/

[日本語版 README はこちら](README-ja.md)

## Features

- **Exhaustive voicing search** — generates every playable fingering for a given root and chord type across frets 0–15, not just a few textbook shapes
- **Fret range filter** — narrow results to Low (0–4F) / Mid (5–8F) / High (9–11F) / Ultra (12F+) positions
- **Focus view** — a large chord diagram with Prev/Next navigation and playback, in vertical or horizontal orientation
- **Panoramic fretboard map** — see every chord tone across the full neck, toggle between note names and scale degrees
- **All Voicings grid** — browse and tap through every matching fingering at once
- **Playback** — Web Audio API strum with a choice of waveform (Ukulele / Soft / Buzzy / Retro)
- **Quick search** — type a chord name like `Am7` or `C#m` to jump straight to it
- **High-G / Low-G tuning**, **left-handed (lefty) mode**, and **accent color / light-dark theme** — all in the settings panel (gear icon)
- 14 chord types: Maj, m, 7, M7, m7, m7b5, dim7, 6, m6, sus4, 7sus4, add9, 9, aug

## Usage

This is a static, dependency-free single HTML file — no build step, no install.

- Open [`index.html`](index.html) directly in a browser, or
- Visit the [live demo](https://tokudiro.github.io/ukulele-chord-explorer/)

## Tech

- Plain HTML / CSS / JavaScript in one file
- [Tailwind CSS](https://tailwindcss.com/) via the Play CDN (JIT, arbitrary values, class-based dark mode)
- Web Audio API for chord playback
- No frameworks, no bundler, no package manager

## License

[MIT](LICENSE)
