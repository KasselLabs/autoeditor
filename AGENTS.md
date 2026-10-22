# Repository instructions

## Node runtime security

Use Node.js 22.23.4 or a newer security patch within major 22 for
local builds (see `.nvmrc`). Exact runtime inputs address CVE-2026-111497;
keep the pins aligned and rebuild artifacts after runtime updates.
