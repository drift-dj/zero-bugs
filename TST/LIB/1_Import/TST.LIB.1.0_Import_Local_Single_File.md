#### TST.LIB.1.0.0
**New File - No Errors - Empty Library**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| ✅ | | 0.6.1 r6 | 2026-10-16T17:49:58+00:00 |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
| ✅ | TST.LIB.1.0.0.0 | Complete: | [[TST.SET.2.2.1](../../SET/TST.SET.2_System#tst.set.2.2.1) Library DB Reset] |
| ✅ | TST.LIB.1.0.0.1 | Navigate: | Library/+Add Music/Browse Files  |
| ✅ | TST.LIB.1.0.0.2 | File Browse: | music/tag/magic-F-123.mp3 |
| ✅ | TST.LIB.1.0.0.3 | Verify: | ![[UI.LIB.9.0.0] New](../../../UI/LIB/UI.LIB.9.0.0.bmp)<br>[[UI.LIB.9.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0) New Import Options] appears |
| ✅ | TST.LIB.1.0.0.4 | Select: | ![[UI.LIB.9.0.0.0] New](../../../UI/LIB/UI.LIB.9.0.0.0.bmp)<br>[[UI.LIB.9.0.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0) Start Button] |
| ✅ | TST.LIB.1.0.0.5 | Navigate: | Library/Artists |
| ✅ | TST.LIB.1.0.0.6 | Verify: | `[Zero QA Artist - Magic]` appears only once in Artists Menu [[UI.LIB.3](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.3)] | 

| Notes | 
| :--- |
|  |

#### TST.LIB.1.0.1
**New File - No Errors - Populated Library**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.1.0.1.0 | Complete: | [[TST.LIB.1.0.0](#tst.lib.1.0.0) New File - No Errors - Empty Library] |
|  | TST.LIB.1.0.1.1 | Navigate: | Library/+Add Music/Browse Files |
|  | TST.LIB.1.0.1.2 | File Browse: | music/tag/veil-Ebm-125.mp3 |
|  | TST.LIB.1.0.0.3 | Verify: | ![[UI.LIB.9.0.0] New](../../../UI/LIB/UI.LIB.9.0.0.bmp)<br>[[UI.LIB.9.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0) New Import Options] appears |
|  | TST.LIB.1.0.0.4 | Select: | ![[UI.LIB.9.0.0.0] New File Options](../../../UI/LIB/UI.LIB.9.0.0.0.bmp)<br>[[UI.LIB.9.0.0.0](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.9.0.0.0) Start Button] |
|  | TST.LIB.1.0.1.5 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.0.6 | Verify: | `[Zero QA Artist - Veil]` appears only once in Artists Menu [[UI.LIB.3](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.3)] | 
|  | TST.LIB.1.0.0.6 | Verify: | `[Zero QA Artist - Magic]` appears only once in Artists Menu [[UI.LIB.3](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.3)] | 

| Notes | 
| :--- |
|  |

#### TST.LIB.1.0.2
**Existing file - No Errors - BPM from File ID3 Tag**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.1.0.2.0 | Complete: | [[TST.LIB.1.0.1](#tst.lib.1.0.1) New File - No Errors - Populated Library] |
|  | TST.LIB.1.0.2.1 | Navigate: | Library/+Add Music/Browse Files |
|  | TST.LIB.1.0.2.2 | File Browse: | music/tag/magic-F-130.mp3 |
|  | TST.LIB.1.0.2.3 | Verify: | [UI.LIB.1.8.0.3 Exists] appears |
|  | TST.LIB.1.0.2.4 | Set: | [UI.LIB.1.8.0.0.1 BPM Source] = ID3 Tag |
|  | TST.LIB.1.0.2.6 | Select: | [UI.LIB.1.8.0.0.0 Start Button] |
|  | TST.LIB.1.0.2.7 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.0.6 | Verify: | `[Zero QA Artist - Veil]` appears only once in Artists Menu [[UI.LIB.3](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.3)] | 
|  | TST.LIB.1.0.0.6 | Verify: | `[Zero QA Artist - Magic]` appears only once in Artists Menu [[UI.LIB.3](../../../UI/LIB/UI.LIB.Library_Menu.md#ui.lib.3)] | 
|  | TST.LIB.1.0.2.10 | Load Deck 1: | `[Zero QA Artist - Magic]` |
|  | TST.LIB.1.0.2.11 | Verify: | `[Zero QA Artist - Magic]` appears in Deck 1 [UI.LIB.2.0.1 Deck 1 Loaded] |
|  | TST.LIB.1.0.2.12 | Verify: | BPM value in [UI.LIB.2.1.0 Deck 1 Only] is 130 |      

| Notes | 
| :--- |
|  |

#### TST.LIB.1.0.3
**Existing file - No Errors - BPM from Library**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.1.0.3.0 | Complete: | [[TST.LIB.1.0.2](#tst.lib.1.0.2) Merge file - No Errors - BPM Use File] |
|  | TST.LIB.1.0.3.1 | Navigate: | Library/+Add Music/Browse Files |
|  | TST.LIB.1.0.3.2 | File Browse: | music/tag/magic-F-123.mp3 |
|  | TST.LIB.1.0.3.3 | Verify: | [UI.LIB.1.8.0.3 Exists] appears |
|  | TST.LIB.1.0.3.4 | Set: | [UI.LIB.1.8.0.0.1 BPM Source] = Library |
|  | TST.LIB.1.0.3.6 | Select: | [UI.LIB.1.8.0.0.0 Start Button] |
|  | TST.LIB.1.0.3.7 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.3.8 | Verify: | Dialect - Sitting in the Sun appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.3.9 | Verify: | Four Foot Louise - Water appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.2.10 | Load Deck 1: | Dialect - Sitting in the Sun |
|  | TST.LIB.1.0.2.11 | Verify: | Dialect - Sitting in the Sun appears in Deck 1 [UI.LIB.2.0.1 Deck 1 Loaded] |
|  | TST.LIB.1.0.2.12 | Verify: | BPM value in [UI.LIB.2.1.0 Deck 1 Only] is 110 |

| Notes | 
| :--- |
|  |

#### TST.LIB.1.0.4
**Existing file - No Errors - Key from File ID3 Tag**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.1.0.4.0 | Settings: | UI/Library Menu/Show Key = true |
|  | TST.LIB.1.0.4.1 | Complete: | [[TST.LIB.1.0.3](#tst.lib.1.0.3) Existing file - No Errors - BPM from Library] |
|  | TST.LIB.1.0.4.2 | Navigate: | Library/+Add Music/Browse Files |
|  | TST.LIB.1.0.4.3 | File Browse: | [1_0_local_single_file/music/merge/Dialect - Sitting in the Sun - d#.mp3] |
|  | TST.LIB.1.0.4.4 | Verify: | [UI.LIB.1.8.0.3 Exists] appears |
|  | TST.LIB.1.0.4.5 | Set: | [UI.LIB.1.8.0.0.2 KEY Source] = ID3 Tag |
|  | TST.LIB.1.0.4.6 | Select: | [UI.LIB.1.8.0.0.0 Start Button] |
|  | TST.LIB.1.0.4.7 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.4.8 | Verify: | Dialect - Sitting in the Sun appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.4.9 | Verify: | Four Foot Louise - Water appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.4.10 | Load Deck 1: | Dialect - Sitting in the Sun |
|  | TST.LIB.1.0.4.11 | Verify: | Dialect - Sitting in the Sun appears in Deck 1 [UI.LIB.2.0.1 Deck 1 Loaded] |
|  | TST.LIB.1.0.4.12 | Verify: | BPM value in [UI.LIB.2.1.0 Deck 1 Only] is 120 |
|  | TST.LIB.1.0.4.13 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.4.14 | Verify: | [UI.LIB.x.x.x Song Key Annotation] appears as D# |

| Notes | 
| :--- |
|  |

#### TST.LIB.1.0.5
**Existing file - No Errors - Key from Library**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.1.0.5.0 | Settings: | UI/Library Menu/Show Key = true |
|  | TST.LIB.1.0.5.1 | Complete: | [[TST.LIB.1.0.4](#tst.lib.1.0.4) Existing file - No Errors - Key from File ID3 Tag] |
|  | TST.LIB.1.0.5.2 | Navigate: | Library/+Add Music/Browse Files |
|  | TST.LIB.1.0.5.3 | File Browse: | [1_0_local_single_file/music/merge/Dialect - Sitting in the Sun - 110BPM.mp3] |
|  | TST.LIB.1.0.5.4 | Verify: | [UI.LIB.1.8.0.3 Exists] appears |
|  | TST.LIB.1.0.5.5 | Set: | [UI.LIB.1.8.0.0.2 KEY Source] = Library |
|  | TST.LIB.1.0.5.6 | Select: | [UI.LIB.1.8.0.0.0 Start Button] |
|  | TST.LIB.1.0.5.7 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.5.8 | Verify: | Dialect - Sitting in the Sun appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.5.9 | Verify: | Four Foot Louise - Water appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.5.10 | Load Deck 1: | Dialect - Sitting in the Sun |
|  | TST.LIB.1.0.5.11 | Verify: | Dialect - Sitting in the Sun appears in Deck 1 [UI.LIB.2.0.1 Deck 1 Loaded] |
|  | TST.LIB.1.0.5.12 | Verify: | BPM value in [UI.LIB.2.1.0 Deck 1 Only] is 110 |
|  | TST.LIB.1.0.5.13 | Navigate: |Library/Artists |
|  | TST.LIB.1.0.5.14 | Verify: | [UI.LIB.x.x.x Song Key Annotation] appears as F#m |

| Notes | 
| :--- |
|  |

#### TST.LIB.1.0.6
**New file - Error - Bad Sample Rate**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.1.0.6.0 | Complete: | [TST.SET.1.0.0.1 Reset Lib Only] |
|  | TST.LIB.1.0.6.1 | Settings: | UI/Library Menu/|  | Hide Unplayable Songs = false |
|  | TST.LIB.1.0.6.2 | Navigate: | Library/+Add Music/Browse Files |
|  | TST.LIB.1.0.6.3 | File Browse: | [1_0_local_single_file/music/error/Dialect - Sitting in the Sun - 48k.mp3] |
|  | TST.LIB.1.0.6.4 | Verify: | [Bad Sample Rate 1.8.3.5] appears |
|  | TST.LIB.1.0.6.5 | Select: | [UI.LIB.1.8.0.0.0 Start Button] |
|  | TST.LIB.1.0.6.6 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.6.7 | Verify: | Dialect - Sitting in the Sun appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.6.8 | Verify: | [Alert Annotation 1.7.1.0] appears on scroll-over |
|  | TST.LIB.1.0.6.9 | Verify: | Four Foot Louise - Water appears only once in [UI.LIB.1.2] Artists |

| Notes | 
| :--- |
|  |

#### TST.LIB.1.0.7
**New file - Error - Bad Codec/Format**

| PASS | FAIL | Build # | Timestamp |
| :---: | :---: | :--- | :--- |
| | | | |

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | :-------- | :------- |
|  | TST.LIB.1.0.7.0 | Complete: | [TST.SET.1.0.0.1 Reset Lib Only] |
|  | TST.LIB.1.0.7.1 | Settings: | UI/Library Menu/Hide Unplayable Songs = false |
|  | TST.LIB.1.0.7.2 | Navigate: | Library/+Add Music/Browse Files |
|  | TST.LIB.1.0.7.3 | File Browse: | [1_0_local_single_file/music/error/Dialect - Sitting in the Sun.m4a] |
|  | TST.LIB.1.0.7.4 | Verify: | [Bad Format 1.8.3.6] appears |
|  | TST.LIB.1.0.7.5 | Select: | [UI.LIB.1.8.0.0.0 Start Button] |
|  | TST.LIB.1.0.7.6 | Navigate: | Library/Artists |
|  | TST.LIB.1.0.7.7 | Verify: | Dialect - Sitting in the Sun appears only once in [UI.LIB.1.2] Artists |
|  | TST.LIB.1.0.7.8 | Verify: | [Alert Annotation 1.7.1.0] appears on scroll-over |
|  | TST.LIB.1.0.7.9 | Verify: | Four Foot Louise - Water appears only once in [UI.LIB.1.2] Artists |

| Notes | 
| :--- |
|  |

✅ ❌
