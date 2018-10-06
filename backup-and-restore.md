---
---
# Backup and restore

- [Making a backup](#backup)
- [Restoring a backup](#restore)

<a name="backup"></a>
## Making a backup

An unmodified version of ULX stores its data in `data/ulx`. ULX also relies on data from ULib, which is stored in `data/ulib` and the `ulib_bans` table in `sv.db`.

1. Shut down your server.
2. Make a copy of the following files and directories in a safe location:
    - `<garrysmod>/data/ulx`
    - `<garrysmod>/data/ulib`
    - `<garrysmod>/sv.db`

<a name="restore"></a>
## Restoring a backup

1. Shut down your server
2. Put backed up files and directories back in their original location.
3. Restart your server.
