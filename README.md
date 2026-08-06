# Casa Canvas — casa-canvas.de

Statische HTML/CSS-Website. Kein Build-Schritt, kein Framework, keine
externen Requests — einfach den Ordner auf einen beliebigen Static-Host
legen. (Einzige Ausnahme: die Karte auf der Startseite — selbst gehostetes
Leaflet mit Kacheln von OpenStreetMap/CARTO — wird erst nach einem
ausdrücklichen Klick der Besucher geladen.)

## Struktur

| Pfad | Inhalt |
|---|---|
| `index.html` | Startseite (One-Pager mit Anker-Navigation) |
| `impressum.html`, `datenschutz.html`, `agb.html` | Rechtsseiten |
| `css/style.css` | Gesamtes Styling |
| `fonts/` | Selbst gehostete Webfonts (WOFF2 + `fonts.css`, alle SIL OFL) — DSGVO-freundlich, kein Google-CDN |
| `images/` | Weboptimierte Bilder |
| `vendor/leaflet/` | Selbst gehostete Leaflet-Bibliothek für die Karte |

## Deployment

Beliebiger Static-Host (GitHub Pages, Cloudflare Pages, Netlify, eigener
Webserver). Danach die DNS-Einträge von casa-canvas.de auf den neuen Host
zeigen lassen.
