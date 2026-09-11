# ProTech Internal Correspondence System (PICS)

A single-file, browser-based tool for drafting internal ProTech Security Solutions
emails, notices, and handbook sections — with a live-rendering BBCode editor and
a division/badge-based staff roster for signatures.

## Features

- **Staff roster** — add staff by name, division, rank, and badge number; saved
  between visits via in-browser storage
- **Classification stamps** — Routine / Internal / Confidential / Urgent
- **BBCode toolbar** — bold, italic, underline, color (presets + custom picker),
  quote, center, headings, bullet/numbered lists, tables, spoilers, images, dividers
- **Live preview** — BBCode renders as you type, styled to match the letterhead
- **Export** — copy as BBCode, copy as plain text, or save the whole letterhead
  as a PNG image

## Usage

Open `index.html` in any modern browser. No build step, no server, no dependencies
beyond Google Fonts and html2canvas (loaded from CDN for the image-export feature).

## Stack

Vanilla HTML/CSS/JS. Fonts: Space Grotesk, Inter, IBM Plex Mono.
