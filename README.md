# Trello Property Data Power-Up

Read-only card-back panel that parses the `### Property Research` block in a card description and shows each field on its own line with colored source tags ([PA], [Sunbiz], [Reonomy], [Reonomy – unconfirmed]).

- `index.html` — iframe connector (set this as the Power-Up's Iframe connector URL)
- `section.html` — the panel rendered on the back of each card

Capability used: **card-back-section** only. No REST token, no writes; it never changes card data.
