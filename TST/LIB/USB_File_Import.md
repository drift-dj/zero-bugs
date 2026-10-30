## USB File Import

| Result | Line | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | 1 | Factory Reset | Lib |
|  | 2 | USB Setup | Set Host Mode + Attach Drive |
|  | 3 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | 4 | +Add Music -> Browse Files | [USB Drive]/music/tag/t4/magic-F-123_t4.mp3 |
|  | 5 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic 123 : F</li></ul></li></ul><ul> |
|  | 6 | +Add Music -> Browse Files | music/tag/t4/veil-Ebm-125_t4.mp3 |
|  | 7 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic 123 : F</li><li>Outside the Veil 125 : Ebm</li></ul></li></ul><ul> |
|  | 8 | +Add Music -> Browse Files | music/tag/t4/magic-A-130_t4.mp3 |
|  | 9 | Set Import Options | <ul><li>BPM Source = ID3 Tag (130.5)</li><li>Key Source = ID3 Tag (A)</li></ul> |
|  | 10 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic **130.5 : A**</li><li>Outside the Veil 125 : Ebm</li></ul></li></ul><ul> |
|  | 11 | +Add Music -> Browse Files | music/tag/t4/magic-F-123_t4.mp3 |
|  | 12 | Set Import Options | <ul><li>BPM Source = Library (130.5)</li><li>Key Source = Library (A)</li></ul> |
|  | 13 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic **130.5 : A**</li><li>Outside the Veil 125 : Ebm</li></ul></li></ul><ul> |




## USB Directory Import

| Result | Line | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | 1 | Factory Reset | Lib |
|  | 2 | USB Setup | Set Host Mode + Attach Drive |
|  | 3 | +Add Music -> Browse Files | [USB Drive]/music/merge/dir_set_a/[Scan this Dir] |
|  | 4 | Start Import |  |
|  | 5 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Magic</li></ul></li></ul> |
|  | 6 | +Add Music -> Browse Files | [USB Drive]/music/merge/dir_set_c/[Scan this Dir] |
|  | 7 | Start Import |  |
|  | 8 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix) [126.2 : Bb]</li><li>Kerri Chandler [122 : Fm]</li><li>Magic [125 : C]</li><li>Outside the Veil [250 : Ebm]</li><li>Teacher [124 : Db]</li><li>The Legend of Pat Nice [123 : Am]</li><li>Water (ODM Mix) [124 : Ab]</li></ul></li></ul> |



| Notes | 
| :--- |
|  |