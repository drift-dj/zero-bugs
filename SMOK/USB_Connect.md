## USB Connectivity Test

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  |   | **Reboot + Drive Mode** | |
|  | 1 | Reboot | Zero |
|  | 2 | Verify | No USB cable is attached |
|  | 3 | Navigate | Control Panels/USB |
|  | 4 | Verify | USB Mode = Offline |
|  | 5 | Navigate | Library/+Add Music |
|  | 6 | Verify | Drive Mode appears w/empty host<br>![Empty Host](images/.5.bmp) |
|  | 7 | Connect | USB-C cable between host and Zero |
|  | 8 | Verify | Host icon appears<br>![Empty Host](images/.7.bmp) |
|  | 9 | Verify | Zero mounts on Host OS |

**If Zero has mounted on Host, test has passed.**

**If Zero has not mounted on Host, continue to Step 10.**

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  |   | **Drive Mode Cable Polarity Check** | |
|  | 10 | Disconnect | USB-C Cable |
|  | 11 | Connect | USB-C Cable |
|  | 12 | Verify | Zero mounts on Host OS after 2 seconds |
|  | 13 | Disconnect | USB-C Cable |
|  | 14 | Rotate | USB-C Cable Plug 180 degrees |
|  | 15 | Connect | USB-C Cable |
|  | 16 | Verify | Zero mounts on Host OS after 2 seconds |

**If Zero has not mounted on Host, test has failed.**

**Continue to [USB Troubleshooting]**
