#### TST.LIB.9.2.0
**Dir of New Files**

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.9.2.0.0 | Complete: | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset] |
|  | TST.LIB.9.2.0.1 | Navigate: | Library/+Add Music/Browse Files  |
|  | TST.LIB.9.2.0.2 | File Browse: | music/merge/dir_set_a/ |
|  | TST.LIB.9.2.0.3 | Verify: | ![[UI.LIB.9.0.0] New](../../../UI/LIB/UI.LIB.9.0.0.bmp)<br>[[UI.LIB.9.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0) New Import Options] appears |
|  | TST.LIB.9.2.0.4 | Select: | ![[UI.LIB.9.0.0.0] New](../../../UI/LIB/UI.LIB.9.0.0.0.bmp)<br>[[UI.LIB.9.0.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0) Start Button] |
|  | TST.LIB.9.2.0.5 | Navigate: | Library/Artists |
|  | TST.LIB.9.2.0.6 | Verify: | Menu Contents (all items appear only once):<ul><li>QA Artist<ul><li>Cornell West</li><li>Magic</li><li>Kerri Chandler</li></ul></li></ul> | 



#### TST.LIB.9.2.1
**Dir of Existing Files - Skip**

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.9.2.0.0 | Complete: | [[TST.LIB.9.2.0](tst.lib.9.2.0) Dir of New Files] |
|  | TST.LIB.9.2.0.1 | Navigate: | Library/+Add Music/Browse Files  |
|  | TST.LIB.9.2.0.2 | File Browse: | music/merge/dir_set_b/ |
|  | TST.LIB.9.2.0.3 | Verify: | ![[UI.LIB.9.0.0] New](../../../UI/LIB/UI.LIB.9.0.0.bmp)<br>[[UI.LIB.9.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0) New Import Options] appears |
|  | TST.LIB.9.2.0.4 | Select: | ![[UI.LIB.9.0.0.0] New](../../../UI/LIB/UI.LIB.9.0.0.0.bmp)<br>[[UI.LIB.9.0.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0) Start Button] |
|  | TST.LIB.9.2.0.5 | Navigate: | Library/Artists |
|  | TST.LIB.9.2.0.6 | Verify: | Menu Contents<ul><li>All items appear only once</li><li>Menu Items have correct BPM/Key values</li></ul><ul><li>QA Artist<ul><li>Cornell West [123][Ab]</li><li>Magic</li><li>Kerri Chandler</li></ul></li></ul> | 

- +Add Files
- /music/import/set_b
- List:
    - Kerri Chandler
    - Magic
    - Pat Nice
- Artist Key/BPM changes


#### TST.LIB.9.2.2
**Dir of Existing Files - Overwrite**

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |

- +Add Files
- /music/import/set_b
- List:
    - Kerri Chandler
    - Magic
    - Pat Nice
- Artist Key/BPM changes

#### TST.LIB.9.2.3
**Dir of Existing Files - Create New**

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |

- +Add Files
- /music/import/set_b
- List:
    - Kerri Chandler
    - Kerri Chandler
    - Magic
    - Magic
    - Pat Nice
    - Pat Nice
- Artist Key/BPM changes

#### TST.LIB.9.2.4
**Dir of Mixed New/Existing Files**

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |

- +Add Files
- /music/import/set_b
- List:
    - Kerri Chandler
    - Magic
    - Pat Nice
    - The Veil
    - Cornell West


#### TST.LIB.9.2.5
**Dir of Mixed New/Existing Files - Errors**

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |

- +Add Files
- /music/import/set_c
- List:
    - Kerri Chandler
    - Magic
    - Pat Nice
    - The Veil
    - Cornell West
    - Water
    - Teacher

✅ ❌