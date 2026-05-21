# B&B Cockpit

Live-Dashboard der **B&B Immo GmbH** für den FireTV in der Küche.

**Daten:** Live aus Airtable (Personal Access Token im Browser-localStorage des FireTV).
**Hosting:** Vercel — Auto-Deploy bei jedem Push, ~30 Sek bis live.
**Workflow:** Edgar speichert `index.html` → Hintergrund-Skript pushed → Vercel deployed → FireTV refresht (alle 5 Min).

Tokens und sensible Daten sind **nicht** im Code, nur im Browser des FireTV.
