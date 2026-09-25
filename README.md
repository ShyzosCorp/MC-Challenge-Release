# MC-Challenge-Release

Public releases of **MC Challenge Plugin** (Paper).

This repository only contains the `.jar` files published automatically by GitHub Actions. The source code is private.

## Requirements

- [PacketEvents](https://modrinth.com/plugin/packetevents) 2.14.0 or newer (used to display block values in item tooltips).

## Installation

1. Download the `.jar` from the [latest release](https://github.com/ShyzosCorp/MC-Challenge-Release/releases/latest).
2. Put it and PacketEvents in the server's `plugins/` directory, then restart.

## Updates

On startup, the plugin checks this repository and automatically downloads new versions into `plugins/update/`. They are applied on the next restart.

Commands (OP): `/update check`, `/update download`.
