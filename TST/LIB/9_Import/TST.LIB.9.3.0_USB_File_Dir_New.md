## TST.LIB.9.3.0

**Dir of New Files - USB Drive**<br>
Import a directory of audio files from a USB Drive into an empty Library

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | TST.LIB.9.3.0.0 | Complete | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset] |
|  | TST.LIB.9.3.0.1 | Complete | [[CONF.USB.3](../../../CONF/USB/CONF.USB.3_Host_Mode.md) Set USB Host Mode] |
|  | TST.LIB.9.3.0.2 | Attach | USB drive with QA files [[CONF.FILE.5](../../../CONF/FILE/CONF.FILE.5_QA_Files_USB.md)]  |
|  | TST.LIB.9.3.0.3 | Navigate | Library/+Add Music/Browse Files  |
|  | TST.LIB.9.3.0.4 | File Browse | [USB Drive]/music/merge/dir_set_a/ |
|  | TST.LIB.9.3.0.5 | Verify | ![New](images/TST.LIB.9.2.0.3.bmp)<br>[[New Import Options](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears |
|  | TST.LIB.9.3.0.6 | Select | ![New](images/TST.LIB.9.2.0.4.bmp) [[Dir Import Start Button](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)] |
|  | TST.LIB.9.3.0.7 | Navigate | Library/Artists |
|  | TST.LIB.9.3.0.8 | Verify | Menu Contents (all items appear only once):<ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Magic</li></ul></li></ul> | 

| Notes | 
| :--- |
|  |