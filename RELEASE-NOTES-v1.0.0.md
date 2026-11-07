# 👻🌈 NIGHTFINDER v1.0.0 · Release Notes

**GlitchByte Phantom Labs // GHOSTROOT**  
**Status:** Public browser application available; separately packaged GitHub Release not yet published.

## ✨ What is available

- Public static neon showcase at https://hellfire13666.github.io/GHOSTROOT-NIGHTFINDER/
- Working local-first browser app at https://hellfire13666.github.io/GHOSTROOT-NIGHTFINDER/NIGHTFINDER-HOME.html
- Approved original NIGHTFINDER artwork, preserved in `nightfinder-approved-art.png`
- Manual Quick Add, attributed sources, keyword filtering, CSV/JSON import, filtered exports, portable full backup, and optional browser-local Vault Memory

## ✅ QA performed

- User-confirmed public showcase and browser application opening in Firefox
- Synthetic JSON record imported through the backup restore control
- Record marked `UNVISITED` with original source attribution
- Browser-local save followed by successful restoration after refresh
- Test workspace cleared, saved empty, and confirmed empty again
- Empty-workspace filtered JSON export user-confirmed
- CSV/JSON import and export flows previously user-tested in the isolated local build
- Static source review found no explicit `fetch()`, `XMLHttpRequest`, or `WebSocket` calls in the application HTML

This is a record of manual user-observed tests and static review, **not** a claim that every behavior or network request was independently audited.

## 🛡️ Privacy and limitations

- No private research vaults, credentials, QA fixture records, or recovery archives are bundled in the public repository.
- Records persist in the current browser profile only if the user clicks `Save locally`. Browser storage is not a durable backup.
- The hosted GitHub Pages app has a different storage origin from the `file://` local app.
- The organizer does not automatically visit or verify onion addresses; ordinary HTTPS provider links open using the browser's configured connection.
- Images and labels are illustrative. The showcase is static; launch the app to use the research controls.

## 📦 Download and packaging

The working HTML and approved image can be downloaded individually from the repository for offline use. A separately packaged, version-tagged GitHub Release with the optional icon and archive checksum has **not yet been published**.

Keep `NIGHTFINDER-HOME.html` and `nightfinder-approved-art.png` in the same directory when running the downloaded app locally.

## 🔐 Historical commit note

An earlier Git commit included a local filesystem path in its message. The active `main` branch was rewritten to use a clean commit. The orphaned old commit has previously remained available by its direct URL; removal from GitHub's retained objects is not guaranteed. No credential was present in that message.

---

**Find the signal. Protect the vault.** 👻💚
