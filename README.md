# LAB-9-OOPS-JAVA: README

**Name:** Punith.C  **USN:** 1BF25CS196
**Program:** StringHandling.java (Java String methods on an email address)

## Files delivered
| File | Description |
|------|-------------|
| `LAB-9-OOPS-JAVA.docx` | Word document: cropped code screenshots, simple explanations, output screenshot, verification table, quick reference, conclusion. Header "LAB 5", footer "Punith.C(1BF25CS196)" with page numbers on every page. |
| `LAB-9-OOPS-JAVA-Images.zip` | The 5 trimmed screenshots, named by their content and numbered in document order. |
| `README.md` | This file. |

## Images in the zip (in document order)
| # | File name | What it shows |
|---|-----------|---------------|
| 1 | `01_StringHandling_Code_Part1_Lines1-29_Input_Length_Trim_Username.png` | Code lines 1-29: Scanner, valid domain, input, length(), trim(), username |
| 2 | `02_StringHandling_Code_Part2_Lines28-55_Domain_Lowercase_Prefix.png` | Code lines 28-55: domain check, invalid email case, toLowerCase(), startsWith() |
| 3 | `03_StringHandling_Code_Part3_Lines56-83_EndsWith_Replace_Contains.png` | Code lines 56-83: endsWith(), replace(), contains(), second email input |
| 4 | `04_StringHandling_Code_Part4_Lines75-93_EqualsIgnoreCase_Close.png` | Code lines 75-93: equalsIgnoreCase() comparison, sc.close() |
| 5 | `05_StringHandling_Output_Terminal_Run.png` | Terminal output of the compiled and executed program |

## How the images were prepared
- Cropped to the code editor / terminal only (file explorer, status bar and window controls removed).
- Original screenshots: `IMG-20261112-WA0003`, `WA0002`, `WA0001`, `WA0000` (code, parts 1 to 4) and `WA0004` (output).

## Date and time of the screenshots
- **Date:** 12-Nov-2026, taken from the file names (`IMG-20261112-...`).
- **Time:** not available. The image files contain no EXIF/capture-time data, so the exact time could not be read. If your teacher needs the time, add it by hand under each caption.

## Program test input used
- Email: `1bf25cs196@bmsce.ac.in`
- Prefix: `1bf25cs`
- Sequence: `2025`
- Second email: `1BF25CS196@BMSCE.AC.IN`

## Results (all verified correct)
Length 22, username `1bf25cs196`, domain `bmsce.ac.in` (belongs to BMSCE), starts with prefix, ends with `bmsce.ac.in`, updated email `1bf25cs196@cse.bmsce.ac.in`, sequence `2025` not found, both emails identical.

## Notes
- The header reads **LAB 5** exactly as requested, while the file and title say **LAB 9**. To change the header, open the document, double-click the header and edit it.
