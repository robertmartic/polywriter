# PolyWriter changelog

## 0.5.1
- Fix a crash when applying a new image width or alternative text. Undo and Redo preserve the image and its settings.
- Use vector icons for Insert, Layout, View and other toolbar actions. Tooltips and accessible names describe each action.

## 0.5.0
- Save new documents as DOCX by default. Keep saving existing PolyWriter documents in their original format and open unverified Word files as copies.
- Insert and resize PNG or JPEG images, edit web links, and insert and edit simple tables.
- Add page breaks, repeating headers and footers, and page numbers. Preview and printing use the same pagination.
- Choose a proofing language and press F6 to move between the toolbar, tabs, and editor.

## 0.4.0
- Open basic Word documents as editable copies, with warnings when unsupported content or formatting may be omitted.
- Export a new DOCX from View, with basic fonts, formatting, paragraph alignment and spacing, simple lists, and supported paper settings.
- Keep .polyw as the default Save format and preserve the original Word file.

## 0.3.1
- Updates now use PolyStudio's signed update channel and verified downloads, with the same in-app download, retry and rollback experience.
- Automatic checks run at most once every 24–30 hours. Manual checks remain available immediately.
- This is the final GitHub bridge update for older installations; subsequent updates are delivered through PolyStudio.

## 0.3.0
- Work with multiple documents in tabs. New and Open preserve other documents and their undo history, selection and paper settings.
- Open several files at once and return to an existing tab when opening the same file again.
- Access up to 20 recent documents from Recent, or clear the local history without deleting files.
- Keep separate unsaved-change indicators and encrypted recovery checkpoints for every document, including inactive tabs.
- Recover interrupted work into separate unsaved tabs. Closing the window or applying an update checks every document first.
- Close a tab with Ctrl+W and switch tabs with Ctrl+Tab or Ctrl+Shift+Tab. Closing the last tab opens a fresh document.

## 0.2.3
- Fixed hard-to-read tooltips in the dark theme. Tooltip text, background and border now follow the active application theme, including when switching themes.

## 0.2.2
- Compact vector icons for file, clipboard, formatting, alignment, list and navigation tools, with descriptive tooltips and accessible names.
- Organised Home tools into Clipboard, Font and Paragraph groups, with visible active formatting and alignment states.
- Added a More menu for groups that do not fit the available toolbar width.
- Fixed saving newly created bulleted and numbered lists with automatic paragraph spacing.

## 0.2.1
- Fixed missing page margins when starting the application with a blank document. The caret and typed text now start at the same position as documents created with New.

## 0.2.0
- Find and replace text with match-case and whole-word options; undo Replace all in one step.
- Apply Normal, Heading 1 and Heading 2 paragraph presets.
- See word counts for the document and selected text.
- Set precise font sizes and paragraph spacing in points, with decimal values and mixed-format support.
- Continue opening and saving existing PolyWriter documents in the same file format.
- Fixed paginated print preview and returning to writing when finding or replacing text.

## 0.1.2

- Added optional PolyHUB integration for coordinated updates while preserving application save prompts.
- Coordinated setup, uninstall and update locking.



## 0.1.1
- New PolyWriter logo in the application, Windows shortcuts, document icons and installer.

## 0.1.0
- Write and format local documents with fonts, paragraph spacing, alignment and simple lists.
- Save PolyWriter documents; import text and supported RTF content, and export TXT or RTF copies.
- Find text, zoom, preview pages and print using configurable paper and margins.
- Recover unsaved work after an interrupted session.
- Use light and dark themes, offline release notes and integrated update downloads for installed copies.
