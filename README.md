# Sampige Semiconductors — Landing Page

## Quick Start
1. Place `index.html` and `logo.png` in the same folder
2. Open `index.html` in any browser — it works fully offline

All images (pencil sketch portraits) are embedded as base64 data URIs inside `index.html`. No external dependencies except Google Fonts (DM Sans + Playfair Display), which degrade gracefully if offline.

## Checkpoint State (Feb 21, 2026)
- Saankhya Labs Legacy section: **removed** (credibility woven into About/Why)
- IP Portfolio domain boxes: **removed** (replaced with 3 clean stats in About)
- Target markets: Consumer Electronics (incl. mobile handsets), IoT & Smart Infrastructure, Silicon for Sovereign AI
- Founder bios: no "35+ yrs" style numbers
- LinkedIn: names are clickable links (no blue buttons)
- Photos: pencil sketches from presentation, correctly mapped to each founder
- Footer: organic gold/sage/green curves
- Nav: About, Focus, Team, Get in Touch

## Founder Photo Mapping (from presentation slide 3)
| Shape ID | Position | Person             |
|----------|----------|--------------------|
| id=9     | leftmost | Parag Naik (CEO)   |
| id=12    | 2nd      | Hemant Mallapur (COO) |
| id=14    | 3rd      | Saumitra Kale (VP VLSI) |
| id=7     | 4th      | Makarand Kulkarni (VP Software) |
| id=16    | 5th      | Harish Krishnan (VP Systems) — glasses, grey hair |

## Pending Feedback Items (not yet applied)
- Bios: scrape from LinkedIn, make crisp and meaningful
- VP comma: remove comma after "VP" in titles (VP VLSI not VP, VLSI)
- Footer curves: make fixed/persistent background across entire page scroll
- CTA font: use Source Sans 3 for cleaner @ glyph in info@sampigesemi.com button

## Tech Stack
- Single-file HTML with inline CSS and JS
- Google Fonts: Playfair Display + DM Sans
- Scroll-triggered reveal animations (IntersectionObserver)
- Responsive: 5→3→2→1 column grid for founder cards
- All photos base64-encoded as data URIs (no external image files)
