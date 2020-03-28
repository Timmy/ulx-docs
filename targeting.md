---
description: >
  The ULX admin mod for Garry’s Mod makes it easy to run commands on a specific
  (group of) players. This tutorial will teach you how target with keywords.
---
# Keyword targeting

- [Summary](#summary)

## Summary

| Keyword    | Meaning                                   |
|------------|-------------------------------------------|
| `^`        | yourself                                  |
| `*`        | everyone                                  |
| `@`        | player in front of you                    |
| `$<id>`    | target by SteamID, UniqueID, UserID or IP |
| `#<group>` | target by group                           |
| `%<group>` | target by group (inheritance counts)      |

Precede a keyword with `!` to negate it.

Multiple keywords can be combined with the `,` operator, which works as a [set union](https://en.wikipedia.org/wiki/Union_set_theory).

**Examples**

- Slap yourself: `ulx slap ^`
- Slap everyone: `ulx slap *`
- Slap everyone except yourself: `ulx slap !^`
- Slap person in front of you: `ulx slap @`
- Slap players in the admin usergroup: `ulx slap #admin`
