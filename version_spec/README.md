# CMMS Mobile — SPEC initiale (version_spec)

Clickable reproduction of the initial mobile specification (screens + navigation diagram), shown in an iPhone frame. French UI, as in the spec.
Start at `index.html` (list of screens) or `Main.dc.html` (À faire).

Navigation (from the spec diagram)
- **À faire** (tab): KPIs À faire / En cours / En retard, intervention en cours, à faire aujourd'hui, à venir → **Intervention**.
- **Scanner** (tab, middle): QR code → **Équipement** → Voir la fiche · Déclarer un incident · Créer une intervention (OT); interventions ouvertes; documents.
- **Recherche** (tab): Interventions or Équipements results.
- **Intervention**: Résumé (checklist), Documents, Photos, Commentaires → Démarrer → **Terminer l'intervention** (compte rendu, photos finales) → **Synchronisation automatique**.
- Cloud icon in the header → Synchronisation (offline mode: data kept on the phone, sent when the connection returns).

Notes
- Fake data; photos are drawn placeholders.
- `support.js` is the Design Component runtime needed to open the screens.
