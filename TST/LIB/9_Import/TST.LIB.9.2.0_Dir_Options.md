## TST.LIB.9.2.0
**Directory Import Options Menu**<br>
Cycle through all the UI permutations of merge settings and data sources to verify all options are available

| PASS | FAIL | Build # | Timestamp | User |
| :--: | :--: | :------ | :-------- | :--- |
|  ✅   |      |         |           |      |

| Pass | ID               |      Action | Reference                                                                                                                                                                                 |
| :--: | :--------------- | ----------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  ✅   | TST.LIB.9.2.0.0  |    Complete | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset]                                                                                                              |
|  ✅   | TST.LIB.9.2.0.1  |    Complete | [[TST.LIB.9.2.1](TST.LIB.9.2.1_Dir_New.md) Dir of New Files]                                                                                                                              |
|  ✅   | TST.LIB.9.2.0.3  |    Navigate | Library/+Add Music/Browse Files                                                                                                                                                           |
|  ✅   | TST.LIB.9.2.0.4  | File Browse | music/merge/dir_set_b/                                                                                                                                                                    |
|  ✅   | TST.LIB.9.2.0.5  |      Verify | ![Dir Import Options](images/TST.LIB.9.2.1.4.bmp)<br>[[Dir Import Options](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears                                                  |
|  ✅   | TST.LIB.9.2.0.6  |         Set | ![Merge Setting](images/TST.LIB.9.2.0.6.bmp)<br>[[Merge Setting](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.1)] = Overwrite                                                      |
|  ✅   | TST.LIB.9.2.0.7  |      Verify | <ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag</li></ul> |
|  ✅   | TST.LIB.9.2.0.8  |         Set | ![Merge Setting](images/LIB.9.2.0.8.bmp)<br>[[Merge Setting](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.1)] = Create New                                                         |
|  ✅   | TST.LIB.9.2.0.9  |      Verify | <ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag</li></ul> |
|  ✅   | TST.LIB.9.2.0.10 |         Set | ![Merge Setting](images/TST.LIB.9.2.0.10.bmp)<br>[[Merge Setting](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.1)] = Merge                                                         |
|  ✅   | TST.LIB.9.2.0.11 |      Verify | <ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag</li></ul> |
|  ✅   | TST.LIB.9.2.0.12 |         Set | <ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = Library</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = Library</li></ul> |
|  ✅   | TST.LIB.9.2.0.13 |         Set | ![Merge Setting](images/TST.LIB.9.2.0.13.bmp)<br>[[Merge Setting](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.1)] = Skip                                                          |
|  ✅   | TST.LIB.9.2.0.14 |      Verify | <ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = N/A</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = N/A</li></ul>         |

| Notes | 
| :--- |
|  |