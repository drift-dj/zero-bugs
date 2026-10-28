## TST.LIB.9.5.0
**New Rekordbox XML - USB Drive**<br>
Import a Rekordbox XML into an empty Library

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | TST.LIB.9.5.0.0 | Complete | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset] |
|  | TST.LIB.9.5.0.1 | Complete | [[CONF.USB.3](../../../CONF/CONF.USB.md#conf.usb.3) Set USB Host Mode] |
|  | TST.LIB.9.5.0.2 | Attach | USB drive with QA files [[CONF.FILE.5](../../../CONF/FILE/CONF.FILE.5_QA_Files_USB.md)]  |
|  | TST.LIB.9.5.0.3 | Navigate | Library/+Add Music/Rekordbox XML  |
|  | TST.LIB.9.5.0.4 | Verify | ![[UI.LIB.9.0.0] New](images/TST.LIB.9.4.1.3.bmp)<br>[[Select RB XML](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears |
|  | TST.LIB.9.5.0.5 | Select | ![[UI.LIB.9.0.0.0] Okay](images/TST.LIB.9.4.0.3.bmp) [[Okay](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)] |
|  | TST.LIB.9.5.0.6 | File Browse | [USB Drive]/music/merge/rb_xml/rb_xml_a.xml |
|  | TST.LIB.9.5.0.7 | Verify | ![[UI.LIB.9.0.0] New](images/TST.LIB.9.4.1.7.bmp)<br>[[Select RB Scan Dir](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears |
|  | TST.LIB.9.5.0.8 | Select | ![[UI.LIB.9.0.0.0] Okay](images/TST.LIB.9.4.0.3.bmp) [[Okay](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)] |
|  | TST.LIB.9.5.0.9 | File Browse | [USB Drive]/Contents/ |
|  | TST.LIB.9.5.0.10 | Verify | ![[UI.LIB.9.0.0] New](images/TST.LIB.9.4.1.9.bmp)<br>[[XML Import Options](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears |
|  | TST.LIB.9.5.0.11 | Select | ![[UI.LIB.9.0.0.0] New](images/TST.LIB.9.4.1.10.bmp) [[Start Button](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)] |
|  | TST.LIB.9.5.0.12 | Navigate | Library/Artists |
|  | TST.LIB.9.5.0.13 | Verify | Menu Contents (all items appear only once):<ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> | 

| Notes | 
| :--- |
|  |