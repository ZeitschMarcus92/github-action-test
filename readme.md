# GitHub Actions Demo

Dieser Workflow zeigt den Einsatz von mehreren GitHub Actions aus dem Marketplace.

## Verwendete Actions

- `actions/checkout@v4` – checkt den Code aus
- `actions/setup-node@v4` – installiert Node.js 18
- `actions/setup-python@v4` – installiert Python 3.11
- `actions/cache@v4` – cached den Ordner `node_modules`
- `dawidd6/action-check-disks@v1` – zeigt die aktuelle Festplattennutzung der GitHub-Runner an  
  → **Nützlich**, um zu verstehen, wie viel Speicher CI-Tools wie `npm`, `pip` oder andere brauchen.
