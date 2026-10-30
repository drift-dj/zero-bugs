## TST.LIB.9.4.3
**Mixed New/Existing Rekordbox XML - Merge**<br>
Import a Rekordbox XML of pre-existing audio files -- merge existing files

| PASS | FAIL | Build # | Timestamp | User |
| :--: | :--: | :------ | :-------- | :--- |
|  ✅   |      |         |           |      |

| Pass | ID               |      Action | Reference                                                                                                                                                                                                                                                |     |
| :--: | :--------------- | ----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
|  ✅   | TST.LIB.9.4.3.0  |    Complete | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset]                                                                                                                                                                             |     |
|  ✅   | TST.LIB.9.4.3.1  |    Complete | [[CONF.FILE.4](../../../CONF/FILE/CONF.FILE.4_QA_Files_Zero.md) Configure Local QA Files]                                                                                                                                                                |     |
|  ✅   | TST.LIB.9.4.3.2  |    Navigate | Library/+Add Music/Rekordbox XML                                                                                                                                                                                                                         |     |
|  ✅   | TST.LIB.9.4.3.3  |      Verify | ![[UI.LIB.9.0.0] New](images/TST.LIB.9.4.1.3.bmp)<br>[[Select RB XML](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears                                                                                                                      |     |
|  ✅   | TST.LIB.9.4.3.4  |      Select | ![[UI.LIB.9.0.0.0] Okay](images/TST.LIB.9.4.0.3.bmp) [[Okay](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)]                                                                                                                                     |     |
|  ✅   | TST.LIB.9.4.3.5  | File Browse | music/merge/rb_xml/rb_xml_b.xml                                                                                                                                                                                                                          |     |
|  ✅   | TST.LIB.9.4.3.6  |      Verify | ![[UI.LIB.9.0.0] New](images/TST.LIB.9.4.1.7.bmp)<br>[[Select RB Scan Dir](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears                                                                                                                 |     |
|  ✅   | TST.LIB.9.4.3.7  |      Select | ![[UI.LIB.9.0.0.0] Okay](images/TST.LIB.9.4.0.3.bmp) [[Okay](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)]                                                                                                                                     |     |
|  ✅   | TST.LIB.9.4.3.8  | File Browse | Contents/                                                                                                                                                                                                                                                |     |
|  ✅   | TST.LIB.9.4.3.9  |      Verify | ![[UI.LIB.9.0.0] New](images/TST.LIB.9.4.2.9.bmp)<br>[[XML Import Options](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears                                                                                                                 |     |
|  ✅   | TST.LIB.9.4.3.10 |      Select | ![[UI.LIB.9.0.0.0] New](images/TST.LIB.9.4.2.10.bmp) [[Start Button](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)]                                                                                                                             |     |
|  ✅   | TST.LIB.9.4.3.11 |    Navigate | Library/Artists                                                                                                                                                                                                                                          |     |
|  ✅   | TST.LIB.9.4.3.12 |      Verify | Menu Contents (all items appear only once):<ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Magic</li><li>Outside the Veil</li><li>Teacher</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |     |

| Notes | 
| :--- |
|  |