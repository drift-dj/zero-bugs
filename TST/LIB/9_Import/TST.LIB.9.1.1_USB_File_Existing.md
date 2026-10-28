## TST.LIB.9.1.1
**Existing file - USB Drive**<br>
Import a single, pre-existing audio file -- overwrite Library metadata with file's metadata

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | TST.LIB.9.1.1.0 | Complete | [[TST.LIB.9.1.0](TST.LIB.9.1.0_USB_File_New.md) New File - USB Drive] |
|  | TST.LIB.9.1.1.1 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | TST.LIB.9.1.1.2 | Navigate | Library/+Add Music/Browse Files |
|  | TST.LIB.9.1.1.3 | File Browse | [USB Drive]/music/tag/t4/magic-A-130_t4.mp3 |
|  | TST.LIB.9.1.1.4 | Verify | ![[UI.LIB.X.X.X] Update File](images/TST.LIB.9.0.2.3.bmp)<br>[[Single File Update Options](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] appears |
|  | TST.LIB.9.1.1.5 | Set | ![[UI.LIB.X.X.X.1] BPM/Key Source](images/TST.LIB.9.0.2.4.bmp)<br><ul><li>[[BPM Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag (130.5)</li><li>[[Key Source](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X.1)] = ID3 Tag (A)</li></ul> |
|  | TST.LIB.9.1.1.6 | Select | ![[UI.LIB.X.X.X] New File Options](images/TST.LIB.9.0.2.5.bmp) [[Single File Update Button](../../../UI/LIB/UI.LIB.Library_Menu.md#UI.LIB.X.X.X)] |
|  | TST.LIB.9.1.1.7 | Navigate | Library/Artists |
|  | TST.LIB.9.1.1.8 | Verify | <ul><li>Zero QA Artist<ul><li>Magic [130.5 : A]</li><li>Veil [125 : Ebm]</li></ul></li></ul><ul> |   

| Notes | 
| :--- |
|  |