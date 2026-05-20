# Terminrechner Pro V2.3

Lieferterminberechnung für **Manfred Sickinger GmbH** — interne + externe Prozesse, Stückzahl-Skalierung, Baugruppen.

## Features
- Automatische BW-Feiertage (Gauss-Algorithmus für Ostern, alle beweglichen Feiertage)
- Live-Berechnung (Werktage / Kalendertage)
- 12 BW-Feiertage automatisch (Neujahr, Hl. Drei Könige, Karfreitag, Ostermontag, 1. Mai, Christi Himmelfahrt, Pfingstmontag, Fronleichnam, 3. Oktober, Allerheiligen, 1./2. Weihnachtstag)
- Wartung: keine — Feiertage werden für jeden Aufruf neu berechnet

## Hosting
- Live: https://terminrechner-pro.pages.dev
- Repo: https://github.com/hasi-elektronic/terminrechner-pro
- Stack: Static HTML/CSS/JS (single-file, kein Build-Schritt)

## Deploy
```bash
CLOUDFLARE_API_TOKEN=$CF_TOKEN wrangler pages deploy . --project-name=terminrechner-pro --branch=main --commit-dirty=true
```

Erstellt von Hasi Elektronic — https://hasi-elektronic.de
