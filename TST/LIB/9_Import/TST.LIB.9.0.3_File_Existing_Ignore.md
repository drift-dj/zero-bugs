## TST.LIB.9.0.3
**Existing file - Ignore BPM/Key**<br>
Import a single, pre-existing audio file -- retains Library metadata

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | TST.LIB.9.0.3.0 | Complete | [[TST.LIB.9.0.2](TST.LIB.9.0.2_File_Existing_Update.md) Existing file - Update BPM/Key] |
|  | TST.LIB.9.0.3.1 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | TST.LIB.9.0.3.2 | Navigate | Library/+Add Music/Browse Files |
|  | TST.LIB.9.0.3.3 | File Browse | music/tag/t4/magic-F-123_t4.mp3 |
|  | TST.LIB.9.0.3.4 | Verify | ![[UI.LIB.X.X.X] Update File](images/TST.LIB.9.0.2.3.bmp)<br>[[Single File Update Options](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] appears |
|  | TST.LIB.9.0.3.5 | Verify | <ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag (123)</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag (F)</li></ul> |
|  | TST.LIB.9.0.3.6 | Set | ![[UI.LIB.X.X.X.1] BPM/Key Source](images/TST.LIB.9.0.2.4.bmp)<br><ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = Library (130.5)</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = Library (A)</li></ul> |
|  | TST.LIB.9.0.3.7 | Select | ![[UI.LIB.X.X.X] New File Options](images/TST.LIB.9.0.2.5.bmp) [[Single File Update Button](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X)] |
|  | TST.LIB.9.0.3.8 | Navigate | Library/Artists |
|  | TST.LIB.9.0.3.9 | Verify | <ul><li>Zero QA Artist<ul><li>Magic [130.5 : A]</li><li>Veil [125 : Ebm]</li></ul></li></ul><ul> |   

| Notes | 
| :--- |
|  |