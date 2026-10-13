# Relix Mobile — initial spec (version_spec)

Clickable mockup of the initial mobile specification (screens + navigation diagram), in English, shown in an iPhone frame.
Start at `index.html` (list of screens) or `Main.dc.html` (To do).

Navigation (from the spec diagram)
- **To do** (tab): Relix header, KPIs To do / In progress / Late, intervention in progress, to do today, coming up → **Intervention**.
- **Scan** (tab, middle): QR code → **Asset** → View sheet · Report an incident · Create an intervention (work order); open interventions; documents.
- **Search** (tab): Interventions or Assets results.
- **Intervention**: Summary (checklist), Documents, Photos, Comments → Start → **Finish the intervention** (report, final photos) → **automatic sync**.
- Cloud icon in the header → Sync (offline mode: data kept on the phone, sent when the connection returns).

Notes
- Fake data; photos are drawn placeholders.
- `support.js` is the Design Component runtime needed to open the screens.
