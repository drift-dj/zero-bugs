## TST.LIB.9.1.0
**New File - USB Drive**<br>
Import a single audio file from a USB-C drive

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | TST.LIB.9.1.0.0 | Complete | [[CONF.USB.3](../../../CONF/USB/CONF.USB.3_Host_Mode.md) Set USB Host Mode] |
|  | TST.LIB.9.1.0.1 | Attach | USB drive with QA files [[CONF.FILE.5](../../../CONF/FILE/CONF.FILE.5_QA_Files_USB.md)]  |
|  | TST.LIB.9.1.0.1 | Navigate | Library/+Add Music/Browse Files  |
|  | TST.LIB.9.1.0.2 | File Browse | [USB Drive]/music/tag/t4/magic-F-123_t4.mp3 |
|  | TST.LIB.9.1.0.3 | Verify | ![[UI.LIB.X.X.X] New](images/TST.LIB.9.0.0.3.bmp)<br>[[Single File Import Options](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X)] appears |
|  | TST.LIB.9.1.0.4 | Select | ![[UI.LIB.X.X.X] New](images/TST.LIB.9.0.0.4.bmp) [[Single File Import Button](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X)] |
|  | TST.LIB.9.1.0.5 | Navigate | Library/Artists |
|  | TST.LIB.9.1.0.6 | Verify | <ul><li>Zero QA Artist<ul><li>Magic</li></ul></li></ul><ul> | 

| Notes | 
| :--- |
|  |