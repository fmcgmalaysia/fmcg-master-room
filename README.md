# fmcg-master-room

Independent Master Purchase UX using fictional data. Production CMS and cross-site integrations are not connected.

## UX candidate v12

Build: `2026-10-09-master-company-dashboard-v12`.

Company selector opens separate NCT/GHR demo workspaces with shared supplier profiles. Menu has Dashboard, Purchase Order, Payment Follow-up and History. Customer entries open their Purchase Room. Dashboard has no progress track; room icons sit above their corresponding count circles.

Customer and supplier directories use compact 40px rows, independent scrolling, sticky headers and search. Suppliers show a compact brand preview, company-specific active task counts and profile/add/edit dialogs with Company Info, Sales Contacts and searchable multi-brand tabs. Brand matches rank first without hiding other suppliers. Description remains23% and Supplier8% in the product table. Existing PO, pricing, quantity and draft handlers are preserved.

Validation:27 focused automated checks passed, including200suppliers/50customers structure. Local Chrome verified compact directories, NCT/GHR task counts, vertical track icons and required supplier-name validation. Candidate remains unmerged and unpublished. No new Wix or GitHub Pages deployment; public site remains v11.

## Existing release

v11 UI source:`1e9bed791df8dc059be4fbd4ac199f18fc92cc06`; release record:`c45d4e0d1179248f3fe155c664204a7b5667b48c`. Pages/Wix/public verification previously completed. Manual Save and same-browser draft protection remain. Est. Shipment Date is unknown until its real order-level source is connected; GP remains an external read-only projection.

No verified production tag or main merge is made without independent user acceptance. Credentials, screenshots and private diagnostics are not included in this repository.
 
Latest supplier UX:the Dashboard Brands column is removed and a direct Edit button opens company information, contacts and brand selection. The brand tab supports search, selected-only view and bulk selection;60demo options were selected and cancelled in local Chrome. POINTBASE remains the planned canonical brand source; no real brand-source or CMS integration was added.

Dashboard presentation now uses a compact overview strip and aligned directories with uniform11px/600-weight entity names,40px rows, matching search/table/footer styles and company-scoped supplier Risk beside Tasks. Risk combines receipt issues and negative external GP once per task; counts open affected rows. Supplier company/contact text normalizes to uppercase while email case, exact URL paths and canonical brand values are preserved. Website/brand labels display uppercase without rewriting their identifiers. No business flow, CMS or production deployment changes.

Dashboard directory names/body/search use11px. Numeric counts use solid blue bubbles with white figures; Risk uses solid red bubbles. Larger overview figures retain visual hierarchy. Only presentation changed;40px rows and existing actions/data remain intact.
