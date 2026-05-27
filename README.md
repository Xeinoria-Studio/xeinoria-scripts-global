# xeinoria-scripts-global

Skript scripts shared across all Xeinoria Minecraft servers (crea, hub, nwland, survie, test).

Scripts in this repository are **identical or have been consolidated** across servers.
Server-specific variants live in each server's own repo.

## Usage

This folder is meant to be mounted/cloned into each server's
`plugins/Skript/scripts/global/` directory. Skript loads scripts recursively,
so any `.sk` file in that subdirectory will be picked up.

The exact sync mechanism (git submodule, periodic clone, CI deploy) is TBD.

## Contents

### Category A — Strictly identical across all servers
acguard, antireload, bring, count, enderchest, fix, god, heal, hidestaff,
motd, msg, op, physicgun, ping, portal, sculkvoice, stickpush, strike,
sudo, tab, trello

### Category B — Consolidated (most-recent version taken as canonical)
crash, disablecmdpv, fail2ban, forbidden_fruit, freeze, hammer, invframe,
item, report, translate, vanish-fixes
