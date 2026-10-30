## TST.LIB.9.0.5
**New file - Error - Unsupported Codec**<br>
Import a single audio file with an unsupported Codec format

| PASS | FAIL | Build # | Timestamp | User |
| :--: | :--: | :------ | :-------- | :--- |
|  ✅   |      |         |           |      |

| Pass | ID              |      Action | Reference                                                                                                                                                      |
| :--: | :-------------- | ----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  ✅   | TST.LIB.9.0.5.0 |    Complete | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset]                                                                                   |
|  ✅   | TST.LIB.9.0.5.1 |    Navigate | Library/+Add Music/Browse Files                                                                                                                                |
|  ✅   | TST.LIB.9.0.5.2 | File Browse | music/format/ogg/magic-44-128k-st.ogg                                                                                                                          |
|  ✅   | TST.LIB.9.0.5.3 |      Verify | ![Unsuppored Codec 1.8.3.5](images/TST.LIB.9.0.5.3.bmp)<br>[[Single File Import Error - Codec](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] appears |

| Notes | 
| :--- |
|  |