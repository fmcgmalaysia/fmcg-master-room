# fmcg-master-room

Independent Master Purchase UX with fictional browser data. Current public release remains v11; this v12 candidate is unpublished.

## Current candidate

Build:`2026-10-09-master-company-dashboard-v12`. Task branch:`feat/company-dashboard-ux-20261009`, draft PR12.

NCT/GHR workspaces are separate; supplier profiles are shared. Menu:Dashboard, Purchase Order, Payment Follow-up and History. Customer entries open Purchase Room; its stage icons sit above count circles.

A shared Segoe UI11px workbench theme uses dark operating text, bold titles/names/headers, Microsoft-blue count bubbles and red Risk. Dashboard directories have32px rows and balanced name/date/count/action columns, independent scrolling and sticky headers. Overview statistics retain large46px bubbles. Payment Requests uses a dollar sign. Supplier Edit uses a person-and-pencil icon.

Payment Follow-up and History use compact ledgers with search and original payment/Path actions. Payment amounts, separate requests and every history event remain intact. Supplier Risk counts receipt differences or negative external GP once per active task, scoped by company.

Supplier Edit has Company Info, Sales Contacts and Brands tabs. Company Name and Short Name share the first row. Purchase Room options and filters show the short name with a full-name fallback; canonical supplier IDs and PO links remain unchanged. Contacts have equal-height fields and Role dropdown choices:Sales Representative, Sales Manager, Director, Account Dept., Warehouse and Others. Existing nonstandard role values are retained.

Ordinary supplier text uppercases while email case, exact URL paths and canonical brand values remain intact. Brand search/multiple selection preserves existing entries. POINTBASE remains the planned brand authority; no real source connection is implemented.

Validation:32 focused checks pass, including200 suppliers/50customers, over50brands, risk scope, uppercase/caret/email/URL preservation, Short Name identity separation, independent payment amounts and complete history. Actual browser validation is recorded locally; credentials/screenshots/private diagnostics are excluded from this repository.

CMS, real staff authorization, Pointbase and cross-site receiving remain unconnected. GP is read-only external projection. No new Pages/Wix deployment or public acceptance, no main merge or verified tag; user review is pending.
