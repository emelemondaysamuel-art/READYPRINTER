# Ready-Writer
Upload .txt / .docx manuscripts, add pictures, and get a KDP-ready **PDF** and **EPUB** plus an AI back cover.
Free AI via Pollinations (no API key needed).

## Run locally
    npm install && npm start     # http://localhost:3000

## Deploy on Render
1. Push this folder to a GitHub repo.
2. Render -> New -> Web Service -> pick the repo.
3. Build: `npm install`   Start: `npm start`   (or use render.yaml / Blueprint)

## Tips
- Start chapters with a line like `Chapter 1: Title` (or Prologue, Part One...). Files without headings become one chapter each.
- Put `[[image:1]]` alone on a line to place the 1st uploaded picture there. Unplaced pictures are spread across chapters.
- Pictures: JPG or PNG. PDF uses built-in fonts (Latin characters only); EPUB supports full Unicode.
- Render free tier sleeps when idle and wipes files on restart; download your files right after generating.
