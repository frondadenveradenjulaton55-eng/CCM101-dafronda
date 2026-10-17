
# Backup Script Guide

## Purpose

The backup script creates a compressed archive of the `app-data` folder. A timestamp is included in the filename so each backup can be identified by its creation date and time.

## Bash Script

```bash
#!/bin/bash
# Automated Application Backup

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Starting backup process..."

# Prepare the destination folder
mkdir -p "$BACKUP_DIR"

# Create a compressed backup
tar -czf "$BACKUP_DIR/backup_$TIMESTAMP.tar.gz" "$SOURCE_DIR"

echo "Backup process finished."
```

## File Permissions

The command `chmod +x backup.sh` allows the script to be executed directly. After setting the permission, run it using `./backup.sh` from the directory where the script is saved.

## Cron Schedule

The following Cron expression schedules the backup:

```cron
0 2 * * * /root/backup.sh
```

This configuration runs the script every day at 2:00 AM according to the system's time zone.

| Field | Value | Description |
|---|---|---|
| Minute | `0` | At the start of the hour |
| Hour | `2` | At 2 AM |
| Day of Month | `*` | Every day |
| Month | `*` | Every month |
| Day of Week | `*` | Every day of the week |

The path `/root/backup.sh` must be replaced if the script is stored in a different location.

## Verification

Use the following command to view the backup files:

```bash
ls -l backups/
```

To check the files stored inside an archive, run:

```bash
tar -tzf backups/backup_FILENAME.tar.gz
```

Replace `backup_FILENAME.tar.gz` with the actual backup filename. These commands help verify that an archive exists and inspect its contents.
