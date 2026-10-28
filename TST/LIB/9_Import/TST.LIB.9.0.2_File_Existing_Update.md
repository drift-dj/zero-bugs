## TST.LIB.9.0.2
**Existing file - Update BPM/Key**<br>
Import a single, pre-existing audio file -- overwrite Library metadata with file's metadata

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | TST.LIB.9.0.2.0 | Complete | [[TST.LIB.9.0.1](TST.LIB.9.0.1_File_New_Pop_Lib.md) New File - Populated Library] |
|  | TST.LIB.9.0.2.1 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | TST.LIB.9.0.2.2 | Navigate | Library/+Add Music/Browse Files |
|  | TST.LIB.9.0.2.3 | File Browse | music/tag/t4/magic-A-130_t4.mp3 |
|  | TST.LIB.9.0.2.4 | Verify | ![[UI.LIB.X.X.X] Update File](images/TST.LIB.9.0.2.3.bmp)<br>[[Single File Update Options](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] appears |
|  | TST.LIB.9.0.2.5 | Set | ![[UI.LIB.X.X.X.1] BPM/Key Source](images/TST.LIB.9.0.2.4.bmp)<br><ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag (130.5)</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag (A)</li></ul> |
|  | TST.LIB.9.0.2.6 | Select | ![[UI.LIB.X.X.X] New File Options](images/TST.LIB.9.0.2.5.bmp) [[Single File Update Button](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X)] |
|  | TST.LIB.9.0.2.7 | Navigate | Library/Artists |
|  | TST.LIB.9.0.2.8 | Verify | <ul><li>Zero QA Artist<ul><li>Magic [130.5 : A]</li><li>Veil [125 : Ebm]</li></ul></li></ul><ul> |   

| Notes | 
| :--- |
|  |