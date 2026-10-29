# WI Builder changelog

Merges one OJTI and one MOI (Word) into a draft Work Instruction in the new company format.

## 1.8 (29 Oct 2026)
- The whole maintenance record at the end of an MOI is copied to the Appendix page, not only the tick table: title, Attachment line, Inventory no. / Conducted by / Reviewed by lines, Test Conditions table, the weekly (or other) checklist and the Remarks box.
- Table columns are never narrower than a heading word (for example "Signature" no longer breaks).
- The Waste disposal bin table keeps the colours of the MOI (green, white, blue, red bin cells and their text colours). In the Environmental box each coloured cell starts with a {{cell fill text}} tag; leave it in place.
- Checklist tables in the MOI (Short Term Preventive Maintenance record, LW / CW tick columns and similar) now go to the Appendix (section 7) instead of ending up under Waste disposal.
- Blank tick rows are kept so the checklist can still be filled in. Works with and without an OJTI.
- Each checklist is put on its own page, in the same orientation (portrait or landscape) as in the MOI. In the Appendix box it is marked {{page landscape}} or {{page portrait}}; change or delete that line to override.
- Wide tables (many columns) now use a smaller font and a valid column width.

## 1.7 (28 Oct 2026)
- New icon: OJTI and MOI pages joined by an arrow into a "WI" page. Used as the browser tab icon and the window icon of the Windows app.
- Web page now uses the company Ocean colour palette (ocean-500 brand colour, ocean-700 title, ocean-100 tints, text black #1D1D1D). Malay text stays blue.

## 1.6 (28 Oct 2026)
- Section 3 sub-topics are numbered 3.1, 3.2 and so on, with items 3.1.1, 3.1.2 and so on. These use real Word numbering and continue from the section heading.
- Other lists use 1, 2, 3 numbering, restarting under each sub-topic, instead of bullets.
- The sub-topics are not added to the contents page, so the contents stay on one page.

## 1.5 (28 Oct 2026)
- Pictures are copied from the OJTI Picture column into the matching step's Picture cell in 6.1, and from the MOI workflow into 6.2.
- The review screen shows thumbnails with a Remove button.
- Embedded Excel and PowerPoint objects are not copied.
- The Picture column in 6.1 is slightly wider so screenshots stay readable.

## 1.4 (27 Oct 2026)
- MOI-only mode: with no OJTI, 6.1 shows N/A, 6.2 takes the MOI "Description of Workflow / Procedure / Method", 6.3 stays Calibration and PM, 6.4 is Equipment used and 6.5 is Material used.
- In this mode the whole document is portrait.

## 1.3 (27 Oct 2026)
- Fixed: in Word, every section started on a new page after Enable Editing. Cause: Word applied "Page break before" from its own Heading 1 style. The file no longer asks Word to update styles, and headings state no page break.
- Compact spacing: 10 pt text with explicit spacing, like the earlier version.
- Offline single-file version and a GitHub kit that builds a Windows .exe (28 Oct).

## 1.2 (27 Oct 2026)
- Header, footer and cover page (title and contents) are taken from the real Updated WI format template. The title and the footer fields (title, document number, version) are filled in.
- Contents list with page numbers; Word asks to update fields on opening (choose Yes).

## 1.1 (26 Oct 2026)
- Section 6.1 (basic operating procedure) is landscape; the other sections stay portrait.

## 1.0 (26 Oct 2026)
- First version: upload an OJTI and an MOI (.docx), review and edit each section in the browser, download the combined WI (.docx).
- English and Malay text are separated automatically; Malay is blue in the 6.1 step table.
- Merges safety, waste, definitions (abbreviations), references and appendix tables.
- Guidelines and precautions document for users.
