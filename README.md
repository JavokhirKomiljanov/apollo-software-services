# Apollo Software Services — company site

Single static page, published with GitHub Pages.

- Source template: `C:\Users\user\Claude\NYC-Leads-2026-10\site\index.tpl.html` (+ `brand/apollo.css`, `apollo.json` for contacts).
- Build: `python build.py` in that folder writes `index.html` here; then commit + push.
- The "Get a free mockup" form posts to the JOS bridge's public add-only `lead` op (ns `nyc`) — requests land in the NYC Leads CRM as "🌐 Website requests". No secrets in this repo.
