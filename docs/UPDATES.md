# PolyWriter updates

Installed copies check at startup (optional in Settings). Use About > Updates
or Settings > Check for updates to check manually. Update available opens release notes.
Update now downloads the package inside PolyWriter, verifies its SHA-256 and
prepares a separate helper. Unsaved work must be saved or explicitly discarded
before restart. Every unsaved tab is checked; Cancel keeps all documents open. Cancellation or failed verification
does not replace the installed version.

The helper checks the registered installation, waits for all PolyWriter windows
to close, stages and verifies the new files, preserves unrelated files and then
replaces the application. A maintenance failure rolls back to the previous folder.
Backups are retained; About > Updates > Manage update storage supports safe cleanup.
After a successful restart, the offline changelog is shown. Failed updates are reported.

From 0.3.1 the application checks https://updates.polystudio.tools/polywriter/stable.json.
The channel is digitally signed with PolyStudio update keys and identifies PolyWriter.
Packages come only from https://downloads.polystudio.tools/polywriter/ with verified sizes and hashes.
Automatic checks run at most once every 24–30 hours, including after a failed check;
manual checks remain immediately available. Redirects and untrusted origins are rejected.
Version 0.3.1 is also available on GitHub as a one-time bridge for older installations.
No private repository credentials are used by the application. Downloads contain
binary packages, customer documentation and notices, never source or debug symbols.

## Optional PolyHUB integration

This release supports the local PolyHUB protocol for coordinated updates. PolyHUB requests the existing application updater; download controls, save prompts, deltas/full fallback and rollback remain in this application. It also verifies the installed result. The app remains fully usable without PolyHUB. Setup, uninstall and update helpers coordinate maintenance to avoid concurrent changes.
