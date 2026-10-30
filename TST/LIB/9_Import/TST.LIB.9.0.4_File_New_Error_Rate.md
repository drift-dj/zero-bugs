## TST.LIB.9.0.4
**New file - Error - Unsupported Sample Rate**<br>
Import a single audio file with an unsupported sample rate

| PASS | FAIL | Build # | Timestamp | User |
| :--: | :--: | :------ | :-------- | :--- |
|  ✅   |      |         |           |      |

| Pass | ID              |      Action | Reference                                                                                                                                                           |
| :--: | :-------------- | ----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  ✅   | TST.LIB.9.0.4.0 |    Complete | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset]                                                                                        |
|  ✅   | TST.LIB.9.0.4.1 |    Navigate | Library/+Add Music/Browse Files                                                                                                                                     |
|  ✅   | TST.LIB.9.0.4.2 | File Browse | music/format/mp3/magic-48-128k-st.mp3                                                                                                                               |
|  ✅   | TST.LIB.9.0.4.3 |      Verify | ![Bad Sample Rate 1.8.3.5](images/TST.LIB.9.0.4.3.bmp)<br>[[Single File Import Error - Sample Rate](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] appears |

| Notes | 
| :--- |
|  |