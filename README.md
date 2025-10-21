# The Odin Project — Landing Page (Assignment)

A simple responsive landing page built as an exercise for The Odin Project. The project demonstrates layout using a centered content container (.wrapper) with full‑width colored sections (header, hero, footer, etc.).

## Features
- Centered content constrained by .wrapper (max-width)
- Full‑width section background colors
- Simple responsive layout using Flexbox
- Minimal HTML/CSS — easy to extend

## Files
- index.html — main markup
- style.css — styles for layout and visuals
- images/ — placeholder images used in the page
- README.md — this file

## How to view locally
1. Open index.html directly in your browser:
   - macOS: double-click index.html or right-click → Open With → Safari/Chrome
2. Or run a simple local server (recommended for reliable relative paths):
   - python3 -m http.server 8000
   - Open http://localhost:8000 in your browser

## Notes / Implementation details
- Constrain content width: .wrapper has a max-width (960px by default) and auto horizontal margins to keep content centered.
- Full‑width backgrounds: section elements (e.g., .header, .hero-section, .quote-section, .footer) span the full viewport width; place .wrapper inside them to keep content constrained while the background remains full width.
- Example: <div class="header"> <div class="wrapper"> ... </div> </div>

## Possible improvements
- Add responsive breakpoints for smaller screens (stacking, font scaling).
- Replace fixed image heights with responsive sizing (max-width: 100%; height: auto).
- Improve accessibility: semantic elements, ARIA where needed, proper alt text.
- Add unit tests / style linting and a build step if the project grows.

## Credits
Built for The Odin Project assignment.

## License
MIT — feel free to reuse and modify.