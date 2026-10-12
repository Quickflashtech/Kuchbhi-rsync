# Kuchbhi-rsync

## What is rsync?

`rsync` is a fast and reliable command-line tool for copying and synchronizing files between locations.  
It can sync files locally (between folders on the same machine) or remotely (between different machines over SSH), while transferring only the differences to save time and bandwidth.

Common uses include:
- Backups
- Mirroring directories
- Incremental file transfers

Example:

```bash
rsync -avz source/ user@host:/path/to/destination/
```