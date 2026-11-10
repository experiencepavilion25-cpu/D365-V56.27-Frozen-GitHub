# D365 F&O ERP Worksheet — V56.27 FROZEN

Frozen version: V56.27 — COA + Questionnaire Check Banners (Display-Only)
File: index.html — open in browser, no server needed.
Fallback: V55 — V55-D365FO-Master-Integration-2026-11-09

WHAT IS FROZEN IN V56.27:
- Worksheet / Access Control / Master Forms — 3 tabs
- Legal Entity — Companies View (Read-only) grid on top (V56.24)
- Questionnaire — Questions View (Read-only) grid on top (V56.25)
- COA — D365 Form View (Read-only) + yellow V56.27 COA CHECK banner (V56.26 + V56.27)
- Questionnaire — yellow V56.27 QUESTIONNAIRE CHECK banner
- Questionnaire RadioButton: Code (Alphanumeric) + Description (Text) + Add Code + Description Row + Attach File Word/PDF/JPEG/Video per question (expanded question, RadioButton/Dropdown/Checkbox only)
- Hide Masters from Worksheet (V56.23), MASTERS tab, Master Forms, Collapse, Summary, Module+Vertical Filter, Hide Technical Details
- Supabase wired, NOT connected — data is browser + Excel backup until you paste URL + Anon Key and Connect + Sync Now
- Integration Push simulated, not live D365. Integration Add/Delete is manual sync, not auto-sync.

DO NOT EDIT THIS ZIP:
- This is the frozen copy for sharing to customer.
- Any new fix = new version file, old file kept. Never overwrite this ZIP.
- To verify you are on V56.27: COA FastTab top must show yellow banner "V56.27 - COA CHECK" and Questionnaire top must show yellow banner "V56.27 - QUESTIONNAIRE CHECK". If banners do not show, you are on an old file.

BACKUP BEFORE SHARING TO NEW CUSTOMER:
- Open V56.27 > Top bar > Download All Masters > save as Backup_[CustomerName]_[Date].xlsx
- Share a fresh copy of this ZIP, not a copy with old customer data.

GITHUB PAGES:
- Upload this folder contents to GitHub repo, Settings > Pages > Deploy from main branch, open https://<user>.github.io/<repo>/
