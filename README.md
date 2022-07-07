# Mac - Disk IO speed test

Bash script for Mac OS X test SSD/HDD/SDHC or network storage's read and write speeds of devices on or connected to your mac.

Usage:
```
$ bash storage_speedtest.sh /Volumes/Data/
```
i.e., use: `/Volumes/Data` and not `/dev/disk2`


Note: administrator password is necessary for sudo to reset file system cache (using sync & purge command). This is because the Read speed results are incorrect when performed without a cache reset.
