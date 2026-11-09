# PolyWriter

[Download PolyWriter 0.5.0 for Windows](https://downloads.polystudio.tools/polywriter/0.5.0/PolyWriter-0.5.0-setup.exe) or [get the portable ZIP](https://downloads.polystudio.tools/polywriter/0.5.0/PolyWriter-0.5.0-win-x64.zip).
Choose the `-setup.exe` asset for a conventional installation, or the `-win-x64.zip` portable package.
Version 0.3.1 bridges older GitHub-based installations to the signed PolyStudio
update channel. Later in-app updates use updates.polystudio.tools and verified
packages from downloads.polystudio.tools. See docs/UPDATES.md.

Version 0.5.0. A local document workspace for 64-bit Windows 10 (2004+) and Windows 11.
Free to use. English interface, light and dark themes, no account or subscription.

Create and format everyday documents, find/replace text, preview pages and print.
New documents default to DOCX. Existing .polyw files keep their format on Save.
When PolyWriter can reproduce every part of a DOCX, it can edit and save that
file directly. Other Word files open as editable copies. Import warnings list
recognised content that may be simplified or omitted. Save a copy under a new
name to preserve the Word original. Save As also offers the PolyWriter format.
Export DOCX, TXT or basic RTF from View.

Use Insert to add PNG or JPEG images, resize an image while keeping its aspect
ratio, add or edit HTTP/HTTPS links, and work with rectangular tables. Edit table
changes the selected cell's column width, rows, columns, or table borders.
Table cells support ordinary paragraphs. DOCX supports single-level lists,
A4 or Letter with equal margins, and one repeating plain-text header and footer.
Merged cells, floating objects, comments and tracked changes are outside this
edition's editing support. Layout can differ between word processors.
DOCX round-trip testing for 0.5.0 used LibreOffice. Microsoft Word was unavailable for hands-on testing.

Use Layout for manual page breaks, headers, footers and page numbers. Editing
is continuous. Print preview and print share the same paginator. Use View > Write
to return to editing. Paste inserts plain text.

Use View > Spelling to select a proofing language. Suggestions depend on the
dictionaries Windows makes available to WPF. F6 moves focus between the editor,
toolbar and document tabs.

The compact toolbar uses vector icons with descriptive tooltips. Home groups
Clipboard, Font and Paragraph tools; active formatting is highlighted. When a
group cannot fit, open More to access it. Font, size and style keep visible values.

Use Layout > Page setup for paper and margins. For PDF output choose Print,
then Microsoft Print to PDF if installed. This is not a built-in PDF export engine.

Unsaved work is checkpointed locally every 15 seconds and encrypted for your
Windows account. After an interrupted session, recovery is offered as a new
unsaved document. Recovery is best effort and does not replace saving files.

Version 0.2 adds Find/Replace (Ctrl+H), Match case and Whole words. Search uses
literal text within paragraphs, including text split across different formatting.
Replace all can be undone in one step. Empty replacement deletes matched text.

Home includes Normal, Heading 1 and Heading 2 paragraph presets. They apply fixed
font and paragraph formatting to the touched paragraphs. Manual formatting may
show Custom. Their formatting is preserved in existing .polyw format 1; document-wide
editable style definitions are reserved for later. Existing .polyw files still open.

Use Font for exact font sizes from 6 to 144 pt, including decimals. Paragraph
accepts decimal before/after spacing in points and line-spacing values from 1 to 3.
Blank mixed-value fields keep their existing formatting. Line spacing uses the
editor's minimum line-height baseline; larger fonts may increase actual line height.
The status bar shows document words and the number of words in a text selection.

Keyboard: Ctrl+N, Ctrl+O, Ctrl+S, Ctrl+Shift+S, Ctrl+P, Ctrl+F, Ctrl+H,
Ctrl+Z/Y, Ctrl+B/I/U, Ctrl+X/C/V. Ctrl+W closes the active tab; Ctrl+Tab and
Ctrl+Shift+Tab switch documents.

Version 0.3 adds document tabs. New and Open keep other documents open, with
independent formatting, paper, selection, undo history, zoom and unsaved indicators.
Open can select several files. Opening a file already in this window selects its
tab. Closing the window or preparing to apply an update checks all unsaved tabs;
Cancel keeps the window open. Closing the final tab creates a fresh document.

Recent lists up to 20 successfully opened or saved paths on this PC. Use Clear
recent list to remove the history without deleting documents. Missing files can
be moved or unavailable; opening one does not erase any open work.

Each dirty tab has its own encrypted recovery checkpoint, including inactive tabs.
After an interrupted session, accepted recovery copies open in separate unsaved
tabs. Save them explicitly. This is crash recovery, not automatic reopening of a
cleanly closed session. Print, preview, Find/Replace and export apply to the active
document; switching tabs returns to writing. Earlier .polyw files remain readable.
New features use .polyw format 2 when saved in the native format.

See docs/INSTALLATION.md and docs/UPDATES.md. Licenses are included in the package.
