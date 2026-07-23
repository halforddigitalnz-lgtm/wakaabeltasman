# Waka Abel Tasman

A refreshed, movement-led marketing site for **Waka Abel Tasman** — waka hourua journeys on the water at Kaiteretere, Abel Tasman, Aotearoa New Zealand.

*Connect. Experience. Explore.*

## Overview

A single-page site (`index.html`) built with a mobile-first, high-craft approach:

- **Design language** derived from the brand's own logo palette — teal → ocean blue → coral dawn — with sand/foam neutrals.
- **Typography** pairs Fraunces (display serif) with Instrument Sans (body).
- **Motion over static**: animated flowing wave dividers, a gentle Ken Burns hero, a flowing-gradient headline, scroll-reveal transitions, count-up stats, an accreditation marquee, and layered depth — all with a `prefers-reduced-motion` fallback.
- Retains all original content: the three offerings (Public / School / Corporate), the guiding whakataukī, TripAdvisor reviews, accreditations, and full contact details.

## Tech

- Static HTML with [Tailwind CSS](https://tailwindcss.com/) via CDN — all custom styles inline.
- Google Fonts (Fraunces, Instrument Sans).
- Photography and logo assets in `images/`.

## Local preview

No build step. Serve the folder over HTTP:

```bash
python3 -m http.server 8123
# then open http://localhost:8123
```

## Structure

```
index.html      # the entire site
images/         # brand logo, photography, accreditation logos, map
```
