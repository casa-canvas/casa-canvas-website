# Casa Canvas

Static HTML/CSS site for casa-canvas.de.

- No build step, no framework, no external requests (fonts are self-hosted in `fonts/`; the only exception is the map — self-hosted Leaflet in `vendor/leaflet/`, tiles from OpenStreetMap/CARTO — which loads after an explicit consent click).
- The design is deliberate and final — don't redesign or "improve" it.
- Web-optimized images live in `images/`.
