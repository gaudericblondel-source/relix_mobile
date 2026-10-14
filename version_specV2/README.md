# Relix Mobile — initial spec V2 (version_specV2)

The initial specification (`../version_spec/`) with a first set of additions, in English, shown in an iPhone frame.
Start at `index.html` (list of screens) or `Main.dc.html` (To do).

Added compared with version_spec
- **Home:** the KPIs are replaced by three actions — **Report a problem**, **Quick intervention**, **New intervention**. Each one first asks for the asset (search, or scan its QR code), then opens the matching form.
- **Quick intervention:** asset + what's happening (one tap) + optional note → *Start now* creates the work order in progress and opens it; details can be completed at the end.
- **Intervention summary:** **spare parts** with picture (when available), quantity, shelf, stock and a *picked* tick, then **tools and equipment**, above the checklist.
- **Checklist step by step:** *Start the intervention* opens one page per step with a progress bar (tap a segment to jump), the step detail, safety notes, the parts for that step (picture, quantity, shelf, *picked* tick), a measurement with its normal range or a required photo when the step asks for it, voice notes and photos. *Next* ticks the step; the last step opens *Finish the intervention*. In progress, the intervention button becomes *Resume · step N of M*.
- **Voice input:** mic button in *Report an incident*, *Create an intervention* (description), *Finish the intervention* (report), *Comments* and the quick-intervention note; the dictated text goes into the field.
- **New intervention:** types Corrective / Preventive / Inspection / **Improvement**; **When?** not scheduled (planner backlog) or a date and time; **Assign to** a person (optional, default: the creator); real checklist picker with preview.
- **Avatar menu (PL):** my profile, availability and time off, skills, site, language, notifications, sync now, log out.

Notes
- Fake data; photos and part pictures are drawn placeholders.
- `support.js` is the Design Component runtime needed to open the screens.
