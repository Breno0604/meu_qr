# AGENTS.md

## Project

Single-page QR Code web app (reader + generator). Pure vanilla HTML/CSS/JS in one file. No build step, no bundler, no framework, no package manager.

## Running

Open `index.html` directly in a browser, or serve with any static server. No install or build required.

**Camera access** (QR reader) requires `https://` or `localhost`. It will not work on `file://` or plain `http://`.

## Key facts

- **Single file**: all HTML, CSS, and JS live in `index.html`. Do not split into multiple files unless explicitly asked.
- **Language**: UI text is in Brazilian Portuguese (pt-BR). Keep new user-facing strings in pt-BR.
- **CDN libraries** (loaded via `<script>` tags, not bundled):
  - `html5-qrcode@2.3.8` — camera-based QR reader
  - `qrcodejs@1.0.0` — QR code generation (renders to `<canvas>`)
- **Storage**: uses `localStorage` for scan history (`qrcode_history`) and high-contrast preference (`qrcode_highcontrast`).
- **No tests, lint, or CI** exist. Verify changes by opening the file in a browser.

## Conventions

- JS runs inside a single IIFE at the bottom of `index.html`.
- DOM queries use a local `$` shorthand (`document.querySelector`).
- CSS uses BEM-like class naming (`.reader-result`, `.btn-sm-primary`).
- High-contrast mode is implemented via `body.high-contrast` class with `!important` overrides.
