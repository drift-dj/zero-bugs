## TST.LIB.9.2.3
**Dir of Existing Files - Overwrite**<br>
Import a directory of pre-existing audio files -- overwrite metadata of existing files

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | TST.LIB.9.2.3.0 | Complete | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset] |
|  | TST.LIB.9.2.3.1 | Complete | [[TST.LIB.9.2.1](TST.LIB.9.2.1_Dir_New.md) Dir of New Files] |
|  | TST.LIB.9.2.3.2 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | TST.LIB.9.2.3.3 | Navigate | Library/+Add Music/Browse Files  |
|  | TST.LIB.9.2.3.4 | File Browse | music/merge/dir_set_b/ |
|  | TST.LIB.9.2.3.5 | Verify | ![Dir Import Options](images/TST.LIB.9.2.1.4.bmp)<br>[[Dir Import Options](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0)] appears |
|  | TST.LIB.9.2.3.6 | Set | ![Merge Setting](images/TST.LIB.9.2.2.5.bmp)<br>[[Merge Setting](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.1)] = Overwrite |
|  | TST.LIB.9.2.3.7 | Select | ![New](images/TST.LIB.9.2.2.6.bmp) [[Dir Import Start Button](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0)] |
|  | TST.LIB.9.2.3.8 | Navigate | Library/Artists |
|  | TST.LIB.9.2.3.9 | Verify | Menu Contents (all items appear only once):<ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix) [124 : Ab]</li><li>Kerri Chandler [61.5 : Bbm]</li><li>Magic [123 : F]</li></ul></li></ul> | 

| Notes | 
| :--- |
|  |