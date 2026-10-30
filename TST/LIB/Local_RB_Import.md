## Local Rekordbox Import

| Result | Line | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | 1 | Factory Reset | Lib |
|  | 2 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | 3 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **music/rb/rb_xml_a.xml**</li><li>*Scan Dir:* music/rb/Contents</li></ul> |
|  | 4 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |
|  | 5 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **music/rb/rb_xml_a.xml**</li><li>*Scan Dir:* music/rb/Contents</li></ul> |
|  | 6 | Set Import Option | [5 Existing] = Skip |
|  | 7 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |
|  | 8 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **music/rb/rb_xml_b.xml**</li><li>*Scan Dir:* music/rb/Contents</li></ul> |
|  | 9 | Set Import Option | [5 Existing] = Overwrite |
|  | 10 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |
|  | 11 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **music/rb/rb_xml_c.xml**</li><li>*Scan Dir:* music/rb/Contents</li></ul> |
|  | 12 | Set Import Option | [5 Existing] = Overwrite |
|  | 13 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Outside the Veil</li><li>The Legend of Pat Nice</li><li>Water (ODM Mix)</li></ul></li></ul> |


