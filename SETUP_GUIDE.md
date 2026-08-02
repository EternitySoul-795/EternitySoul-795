# Setup Notes

Pushed to `EternitySoul-795/demo587` for review. Copy `README.md` and `assets/` into your profile repo (`EternitySoul-795/EternitySoul-795`) when ready — no workflows, no secrets, nothing to configure. Everything is either a static local SVG or a live external image URL.

## Structure (10 sections, ~120 lines)

Hero Banner → Short Introduction → About → Tech Stack → Overview (Stats + Streak + Top Languages, one row) → Featured Projects (6 cards, 3×2 grid) → Contact → Footer.

This version deliberately drops what earlier rounds had: no Currently Listening, no Achievements, no contribution-calendar heatmap, no star/fork badges on project cards — none of those were in your requested section list, and cutting them is most of what got this under the line-count and "fits near one screen" targets. Add any of them back if you change your mind; they're simple to reintroduce as one more image row.

## Placeholders to fill in

| Placeholder | Where |
|---|---|
| `your-email@example.com`, `your-handle` (LinkedIn/X), `your-portfolio.example.com` | Contact section |
| `lucy-ai`, `unicard-engine`, `whatsapp-ai`, `ai-automation-projects` | Featured Projects links — these repos don't exist yet; create them or edit the links |

## Design notes

- **Tech Stack is icon-only** — every badge uses a blank label (`img.shields.io/badge/-name-color`) so only the logo glyph shows, on a uniform dark pill. No category subheadings, just one row.
- **Overview combines three stat services in one row** instead of three separate headed sections — each image already carries its own title internally (e.g. the stats card renders "Khileshwar Dewangan's GitHub Stats" inside itself), so a repeated markdown heading per image would just be redundant vertical space.
- **Project cards are plain typography, no cover art or badge images** — a 3-column grid keeps six projects to two rows instead of six, which is most of the vertical space saved versus the earlier 2-column version.
