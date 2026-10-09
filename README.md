# fmcg-master-room

Independent Master Purchase UX with fictional browser data. Public UX release: v13. Published to GitHub Pages and the independent Wix Master test page on 2026-10-09.

## Current release

Build:`2026-10-09-master-dashboard-display-v13`. Release branch:`style/dashboard-summary-alignment-20261009`, PR14.

NCT/GHR workspaces are separate; supplier profiles are shared. Menu:Dashboard, Purchase Order, Payment Follow-up and History. Customer entries open Purchase Room; its stage icons sit above count circles.

A shared Segoe UI11px workbench theme uses dark operating text, bold titles/names/headers, Microsoft-blue count bubbles and red Risk. Dashboard directories have32px rows and balanced name/date/count/action columns, independent scrolling and sticky headers. Overview statistics retain large46px bubbles. Payment Requests uses a dollar sign. Supplier Edit uses a person-and-pencil icon.

Payment Follow-up and History use compact ledgers with search and original payment/Path actions. Payment amounts, separate requests and every history event remain intact. Supplier Risk counts receipt differences or negative external GP once per active task, scoped by company.

Supplier Edit has Company Info, Sales Contacts and Brands tabs. Company Name and Short Name share the first row. Purchase Room options and filters show the short name with a full-name fallback; canonical supplier IDs and PO links remain unchanged. Contacts have equal-height fields and Role dropdown choices:Sales Representative, Sales Manager, Director, Account Dept., Warehouse and Others. Existing nonstandard role values are retained.

Ordinary supplier text uppercases while email case, exact URL paths and canonical brand values remain intact. Brand search/multiple selection preserves existing entries. POINTBASE remains the planned brand authority; no real source connection is implemented.

Validation:32 focused checks pass, including200 suppliers/50customers, over50brands, risk scope, uppercase/caret/email/URL preservation, Short Name identity separation, independent payment amounts and complete history. Actual browser validation is recorded locally; credentials/screenshots/private diagnostics are excluded from this repository.

CMS, real staff authorization, Pointbase and cross-site receiving remain unconnected. GP is read-only external projection. Four release stages passed: code 91fe724, Pages run 37884175989 with the v12 marker and all four public assets matching source, Wix Studio live publication receipt with exact published HTML readback, and force-refreshed public browser validation. Dashboard, NCT/GHR switch, supplier company/Short Name/contacts/six Role options/brands, Payment Follow-up, History and Purchase Room were checked. Existing 30 task IDs, order, five price fields and P.O. values match the recorded v11 public proof; supplier forms were cancelled without saving. Those v12 checks remain the prior baseline; see the user-verified v13 release below.

## User-verified v13 display release

Dashboard Tasks/Risk at zero show plain dashes. Positive counts retain solid bubbles and original actions. The overview has centered horizontal icon/title/count groups,46px bubbles and36px dividers, with two columns at narrower widths.

Code: `012e797c665fc6e8b6653606ba25faca5fc502a5`. Pages run `37887895331` succeeded and the v13 marker plus all four public assets match source. Wix complete HTML readback matches the release package and Studio confirmed the site live. After a transient Wix base-script network timeout, the user refreshed the public page and confirmed normal operation on2026-10-09. No network code workaround or business data edits were applied.

Acceptance covers these Dashboard display changes only. Earlier32 checks and zero/positive renderer checks pass; the complete Purchase operation script is unchanged from v12. Exact recovery files and acceptance evidence are preserved locally; private diagnostics/credentials are not uploaded. No main merge.

Annotated recovery tag: `verified/dashboard-display-v13-20261009` -> exact user-accepted code `012e797c665fc6e8b6653606ba25faca5fc502a5`.
