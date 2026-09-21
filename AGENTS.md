# Project notes

## Source of truth
Pulse is an attached local codebase folder (`Pulse/`), not a GitHub repo. Browse with the
`local_*` tools (`local_ls`, `local_read`, `local_grep`). Key docs:

- `Pulse/docs/ARCHITECTURE.md` — layers, record spine, module contract, permissions, Helios chain
- `Pulse/docs/HELIOS.md` — tools, effects (read/write/external), confirmation hashes, channels
- `Pulse/packages/core/src/domain/core-module.ts` — core routes + navigation (sections: primary, work, data, admin)
- `Pulse/apps/demo/pulse.config.ts` — client config: branding, terminology, modules, home widgets, features
- `Pulse/packages/modules/site-visits` — the reusable module fixture

## Mockup files
- `Pulse v4 Glass.dc.html` — the live client build: **McGrane Precast**, a family-owned precast
  manufacturer. Dark liquid glass on graphite `#363D45` with signal blue `#2F6FBF` as the single
  accent, icon rail with hover labels, Home = Helios chat + right rail, plus the real page set
  (inbox, work queues, approvals, records, universal record page, insights, automations, system
  health, modules, notifications, settings).
  Client-specific modules: **Pipeline** (Enquiries, Quotes, Follow-ups, Win/Loss), **Yard**
  (Records › Yard Stock and Production) and **Dispatch** (Work › Loading).
- `Pulse v2.dc.html`, `Pulse v3 Apple.dc.html`, `Pulse v3 Console.dc.html`, `Pulse Home.dc.html` — earlier directions, keep.

## Conventions the mockups should keep
- Helios never executes write/external tools; it proposes and waits for a confirmation bound to hashed arguments.
- The action inbox answers three things per item: what happened, why it matters, what I can do.
- Metrics, nav, pages and Helios tools all come from the registry — module contributions are labelled as the module's.
- Every mock number is generated once in the `MP` block at the top of the logic script and then
  normalised onto the headline totals, so a badge is always the length of the list under it and a
  euro figure is always the sum of the rows behind it. Change the story by changing `MP`, never by
  typing a number beside a table.
