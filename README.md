# Lottolosa v3.8 – Gray–Orange

Installierbare Lotto-Simulator-PWA (12 Tipps, Zusatzzahl, realistische Payouts).
- **Installieren-Button** (PWA)
- **Top 6 häufigste Zahlen** + separate **ZZ-Kugel**
- **„Solange bis 6 Richtige“**-Button
- **Statistik** inkl. *6 Richtige + ZZ*
- **Offlinefähig** via Service Worker

## GitHub Pages Deployment
1. Repository erstellen (Branch `main`).
2. Dateien aus diesem Ordner pushen.
3. In den Repo-Settings → **Pages** → Source: „GitHub Actions“.
4. Nach dem Push läuft der Workflow `.github/workflows/deploy.yml` automatisch.
5. Die App ist dann erreichbar unter: `https://<deinname>.github.io/<repo>/`.
