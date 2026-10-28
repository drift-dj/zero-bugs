## CONF.FILE.2
**Format FAT32 Drive MacOS**

| ID           | Action |
| :------------------- | :-------- |
| CONF.FILE.2.0 | Attach USB-C thumb drive to MacOS host computer |
| CONF.FILE.2.1 | Launch Disk Utility App |
| CONF.FILE.2.2 | Enable menu item **View** > **Show All Devices** |
| CONF.FILE.2.3 | <ul><li>Select the top-level device of thumb drive</li><li>Click Erase</li></ul><br>![Top Level](images/macos-disk_util-select_drive.png)<br>![Top Level](images/macos-disk_util-erase.png) |
| CONF.FILE.2.4 | <ul><li>Enter a name</li><li>Set Format = **MS-DOS (FAT)**</li><li>Set Scheme = Master Boot Record</li><li>Click Erase</li></ul><br>![Top Level](images/macos-disk_util-fat32.png) |
| CONF.FILE.2.5 | Verify empty USB drive mounts in Finder |
