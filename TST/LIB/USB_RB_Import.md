## Local Rekordbox Import

| Result | Line | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | 1 | Factory Reset | Lib |
|  | 2 | USB Setup | Set Host Mode + Attach Drive |
|  | 3 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | 4 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **[USB Drive]/music/rb/rb_xml_a.xml**</li><li>*Scan Dir:* [USB Drive]/music/rb/Contents</li></ul> |
|  | 5 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |
|  | 6 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **[USB Drive]/music/rb/rb_xml_a.xml**</li><li>*Scan Dir:* [USB Drive]/music/rb/Contents</li></ul> |
|  | 7 | Set Import Option | [5 Existing] = Skip |
|  | 8 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |
|  | 9 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **[USB Drive]/music/rb/rb_xml_b.xml**</li><li>*Scan Dir:* [USB Drive]/music/rb/Contents</li></ul> |
|  | 10 | Set Import Option | [5 Existing] = Overwrite |
|  | 11 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |
|  | 12 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **[USB Drive]/music/rb/rb_xml_c.xml**</li><li>*Scan Dir:* [USB Drive]/music/rb/Contents</li></ul> |
|  | 13 | Set Import Option | [5 Existing] = Overwrite |
|  | 14 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |


