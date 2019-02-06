---
description: >
  The ULX admin mod for Garry’s Mod allows for a high level of customization.
  This page covers prominent settings that are not customizable through XGUI.
---
# Configuration

- [Introduction](#introduction)
- [Forced downloads](#downloads)
- [Ban reasons](#ban-reasons)
- [Per-gamemode/per-map configuration](#per-gamemode-per-map-configuration)

<a name="introduction"></a>
## Introduction

ULX allows for a high level of customization. Most settings can be changed from XGUI by typing `!xgui settings` in chat.

Prominent settings that are not customizable in XGUI are covered on this page.

<a name="downloads"></a>
## Forced downloads

| File    | `<garrysmod>/data/ulx/downloads.txt`                |
| Format  | Flat-file database                                  |
| Purpose | Files and directories that clients should download. |

Forced downloads allow you to specify paths to files and directories that should be downloaded by the client.

<a name="ban-reasons"></a>
## Ban reasons

| File    | `<garrysmod>/data/ulx/banreasons.txt` |
| Format  | Flat-file database                    |
| Purpose | Store default ban reasons.            |

Default ban reasons are displayed as suggestions when trying to kick or ban a user from XGUI. ULX will also autocomplete default ban reasons from the developer console.

<a name="per-gamemode-per-map-configuration"></a>
## Per-gamemode/per-map configuration

ULX can load different configurations depending on the current gamemode or map.

Create files using the following directory structure:
- `<garrysmod>/data/ulx/maps/<mapname>/config.txt`
- `<garrysmod>/data/ulx/gamemodes/<gamemodename>/config.txt`

This feature is compatible with all ULX configuration files (`config.txt`, `downloads.txt`, `gimps.txt`, `adverts.txt`, `votemaps.txt`, `banreasons.txt`, `motd.txt` and `banmessage.txt`).

All configurations add to each other except gimps and votemaps, which takes the most specific configuration only.
