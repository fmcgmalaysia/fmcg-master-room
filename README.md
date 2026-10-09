# fmcg-master-room

Independent Master Purchase UX with fictional browser data. Public UX release: v12. Published to GitHub Pages and the independent Wix Master test page on 2026-10-09.

## Current release

Build:`2026-10-09-master-company-dashboard-v12`. Task branch:`feat/company-dashboard-ux-20261009`, draft PR12.

NCT/GHR workspaces are separate; supplier profiles are shared. Menu:Dashboard, Purchase Order, Payment Follow-up and History. Customer entries open Purchase Room; its stage icons sit above count circles.

A shared Segoe UI11px workbench theme uses dark operating text, bold titles/names/headers, Microsoft-blue count bubbles and red Risk. Dashboard directories have32px rows and balanced name/date/count/action columns, independent scrolling and sticky headers. Overview statistics retain large46px bubbles. Payment Requests uses a dollar sign. Supplier Edit uses a person-and-pencil icon.

Payment Follow-up and History use compact ledgers with search and original payment/Path actions. Payment amounts, separate requests and every history event remain intact. Supplier Risk counts receipt differences or negative external GP once per active task, scoped by company.

Supplier Edit has Company Info, Sales Contacts and Brands tabs. Company Name and Short Name share the first row. Purchase Room options and filters show the short name with a full-name fallback; canonical supplier IDs and PO links remain unchanged. Contacts have equal-height fields and Role dropdown choices:Sales Representative, Sales Manager, Director, Account Dept., Warehouse and Others. Existing nonstandard role values are retained.

Ordinary supplier text uppercases while email case, exact URL paths and canonical brand values remain intact. Brand search/multiple selection preserves existing entries. POINTBASE remains the planned brand authority; no real source connection is implemented.

Validation:32 focused checks pass, including200 suppliers/50customers, over50brands, risk scope, uppercase/caret/email/URL preservation, Short Name identity separation, independent payment amounts and complete history. Actual browser validation is recorded locally; credentials/screenshots/private diagnostics are excluded from this repository.

CMS, real staff authorization, Pointbase and cross-site receiving remain unconnected. GP is read-only external projection. Four release stages passed: code 91fe724, Pages run 37884175989 with the v12 marker and all four public assets matching source, Wix Studio live publication receipt with exact published HTML readback, and force-refreshed public browser validation. Dashboard, NCT/GHR switch, supplier company/Short Name/contacts/six Role options/brands, Payment Follow-up, History and Purchase Room were checked. Existing 30 task IDs, order, five price fields and P.O. values match the recorded v11 public proof; supplier forms were cancelled without saving. Independent user acceptance is pending; no main merge or verified tag.

## Pending display adjustment

Dashboard Tasks and Risk show a plain dash at zero; positive counts retain their existing solid bubbles and click actions. This isolated display patch passed the existing 32 checks and direct zero/positive renderer checks. It is not deployed to GitHub Pages or Wix; public release remains the v12 version described above.

## Pending summary alignment

The Dashboard overview uses centered horizontal icon/title/count groups, preserving the46px bubbles, dark semibold labels and zero Tasks/Risk dashes. Dividers are36px high. At narrower widths the overview forms two columns. Only summary CSS changes; JavaScript and other views are unchanged. Actual local Chrome NCT/GHR desktop previews were inspected. This layout adjustment is not deployed to Pages or Wix.

## Display release candidate

Build: `2026-10-09-master-dashboard-display-v13`. Combines the approved zero-count display and horizontal overview alignment. Fresh Wix v12 snapshot matches the recovery file exactly; the prepared five-region patch preserves the complete Purchase operation script. Pages/Wix publication and public verification are still pending.
