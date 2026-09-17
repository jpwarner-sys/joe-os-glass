# Joe OS glass

Rename-only port of the upstream glass, pass 2.
Parser and chrome are unchanged. Labels and bind target say Joe OS.

The upstream cabinet stays on its own Drive. This copy does not phone that folder.

## URL

Repo: `https://github.com/jpwarner-sys/joe-os-glass`

After GitHub Pages is on for `jpwarner-sys/joe-os-glass` (Settings → Pages → branch `main` / root):

`https://jpwarner-sys.github.io/joe-os-glass/` (or a custom subdomain like `joe-glass.ontologyhome.ca` to avoid origin storage collisions with other apps)

`?demo=1` wakes on fixture files. `?react=1` shows the void against a Joe-OS-shaped listing.

## Local

From this folder:

`python3 -m http.server 8765`

- `/` — black, tiny JOE OS, unbound
- `/?demo=1` — fixture NOW + project tiles (cabinet schema, Joe words)
- `/?react=1` — file names shaped like live Joe OS (no NOW.md) → void

Folder bind (Chrome / Edge): point at `fixtures/cabinet` to wake tiles, or at a live Joe_OS / Joe_OS_2 tree to watch the schema miss.

## Bind

- **Folder** — directory picker. Dump writes `dump/YYYY-MM-DDTHHMMSSZ.md`.
- **Drive** — needs `GOOGLE_CLIENT_ID` in `config.js`. Searches folders named `Joe_OS` or `Joe_OS_2`. Without the id the Drive control stays dark.

## Contract

Same as the upstream packet's `SCHEMA.md`. Parser is `parse.js`.
Looks for `NOW.md`, `PROJECTS.md`, `VESSELS.md`, `modules/*.md`.
Ignored: dotfiles, `*.keep`, `README.md`, `artifacts/`.
Workshop halt if the bound folder has Brainstorm/Build/Design and no `NOW.md`.

Joe OS / Ontology Lab is **not** that schema. Binding the live tree should stay void, not invent tiles.

## Chrome

Two glyphs: fill rectangle, split rectangle. Four density pips.
Click a tile to focus. Double-click to cycle size. Dump line does not reply.

## Not this

Walker. Native `.app`. Chat on the glass. Live 6_APP clasp. The upstream cabinet. Sample modules as if they were his.
