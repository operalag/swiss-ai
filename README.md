# Swiss AI — swiss-ai.operal.solutions

Sovereign AI infrastructure from Switzerland. A collaboration of **Operal AG** (Zug) and **Ovescom AG** (Weinfelden).

Static site, served via GitHub Pages under `swiss-ai.operal.solutions`.

- `/` — German homepage (primary)
- `/en/` — English homepage
- `/check/` + `/en/check/` — interactive Sovereignty Check (runs fully client-side, no data leaves the browser)

- `/assets/` — shared CSS/JS ("Perimeter" design system, sibling of Operal Atmosphere)

## Deploy
Push to `main` → GitHub Pages publishes automatically. Custom domain via `CNAME` file; DNS: CNAME `swiss-ai` → `operalag.github.io` (Infomaniak, operal.solutions zone).
