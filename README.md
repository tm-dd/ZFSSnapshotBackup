# ZFSSnapshotBackups

## ABOUT ##

The script create a new shapshot of a ZFS Volume and remove old ones.

It can be defined how many old backups should be keeped, at least:
* in the last hours
* in the last days
* in the last month
* in the last years

Useful if you want to use ZFS snapshots as a simple and extended backup solution.
Please note, ZFS snapshots can take a lot of disk space.

## Install example

Install the script on /usr/local/sbin/ and install all nessesary software.
Define a cron job every hour to run the script later.

Thomas Mueller <><
