# Wedding Shoot Itinerary Maker

Converts a wedding planner's timeline doc into a distilled, photo/video-team-ready itinerary page.

- **`index.html`** — the editor tool. Upload a PDF/DOCX/TXT (or paste text), auto-extract couple names, date, venues, timeline, vendors, and shot list with Claude, review in the form, and download a standalone HTML itinerary.
- **`template.html`** — reference design used as the style source for the output.

Runs entirely in the browser. Bring your own Anthropic API key (stored in `localStorage`, calls `api.anthropic.com` directly).

Part of [Marco Wang Photography](https://www.marcowang.com).
