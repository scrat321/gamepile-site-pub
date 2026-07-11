# Gamepile v1.0.0-alpha.17 — Known Issues

Issues confirmed in this release. All are queued as immediate follow-ups
for the next update. None of them put your game data at risk.

## Assistant Access (AI)

- **One-click "Install for Claude Code" can fail** with an
  "Invalid environment variable format" error. **Workaround:** use the
  **Copy command** option on the same card and run it in a terminal
  yourself — the copied command registers the server correctly.

## Library Health — Asset Integrity

- The results area is not scrollable, so long result sets get cut off.
- Findings are only reported as totals (for example "6 corrupt" or a
  number of "unverifiable" assets) without naming the affected files or
  games. A per-file detail view is planned.
- The panel's **Refresh** behavior is unclear, and there is no
  clear/reset control or filtering yet.
- The health icon does not turn to its warning/error color when an
  asset-integrity scan finds problems.

## Performance

- Selecting a large number of games at once (multi-select) can lag when
  many games are on screen.
- The Acquisitions tab can stall briefly on large libraries while totals
  are calculated. The calculation will be made asynchronous with a
  "calculating…" indicator.

## Settings

- Wallpaper adjustments are disabled while the default wallpaper is
  selected; they will be enabled for it in a follow-up.
- Turning off Dynamic Effects applies immediately without a
  confirmation prompt.

## Backups

- The **Backup Sets** tab badge shows the total number of backups
  instead of the number of sets. Display-only — backups themselves are
  unaffected.
