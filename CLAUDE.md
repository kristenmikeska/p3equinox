# CLAUDE.md: Persona 3: Equinox's site (pages only)

This repo is only Equinox's three pages (`femc-equinox.html`, `femc-equinox-game.html`, `femc-equinox.webmanifest`) and an
`index.html` that opens the title. Everything else, the engine, Equinox's story, links, art, tools, docs and hidden plot
files, lives in the sibling repo **`../p3solstice`** (each page has `<base href="../p3solstice/">`). **Read
`../p3solstice/CLAUDE.md` first; its ground rules apply here** (push only when Kat says "push", no spoilers, never commit
`DO-NOT-OPEN-*`, commits end with `Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com>`).
When bumping a `?v=` for an Equinox script, the `<script>` tag is in this repo's `femc-equinox-game.html` even though the
file is in p3solstice. Local testing: serve the parent folder (see p3solstice's CLAUDE.md), open http://localhost:8000/p3equinox/ .
