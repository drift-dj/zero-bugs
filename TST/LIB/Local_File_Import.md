## Local File Import

| Result | Line | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | 1 | Factory Reset | Lib |
|  | 2 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | 3 | +Add Music -> Browse Files | music/tag/t4/magic-F-123_t4.mp3 |
|  | 4 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic 123 : F</li></ul></li></ul><ul> |
|  | 5 | +Add Music -> Browse Files | music/tag/t4/veil-Ebm-125_t4.mp3 |
|  | 6 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic 123 : F</li><li>Outside the Veil 125 : Ebm</li></ul></li></ul><ul> |
|  | 7 | +Add Music -> Browse Files | music/tag/t4/magic-A-130_t4.mp3 |
|  | 8 | Set Import Options | <ul><li>BPM Source = ID3 Tag (130.5)</li><li>Key Source = ID3 Tag (A)</li></ul> |
|  | 9 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic **130.5 : A**</li><li>Outside the Veil 125 : Ebm</li></ul></li></ul><ul> |
|  | 10 | +Add Music -> Browse Files | music/tag/t4/magic-F-123_t4.mp3 |
|  | 11 | Set Import Options | <ul><li>BPM Source = Library (130.5)</li><li>Key Source = Library (A)</li></ul> |
|  | 12 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Magic **130.5 : A**</li><li>Outside the Veil 125 : Ebm</li></ul></li></ul><ul> |
|  | 13 | +Add Music -> Browse Files | music/format/mp3/magic-48-128k-st.mp3 |
|  | 14 | Verify | Bad Sample Rate appears |
|  | 15 | +Add Music -> Browse Files | music/format/ogg/magic-44-128k-st.ogg |
|  | 16 | Verify | Unsupported Codec appears |
|  | 17 | +Add Music -> Browse Files | music/format/invalid/boot.png |
|  | 18 | Verify | Bad Filetype appears |


## Local Directory Import

| Result | Line | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | 1 | Factory Reset | Lib |
|  | 2 | Settings | <ul><li>UI/Library Menu/Show BPM = true</li><li>UI/Library Menu/Show Key = true</li></ul> |
|  | 3 | +Add Music -> Browse Files | music/merge/dir_set_a/[Scan this Dir] |
|  | 4 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix)</li><li>Kerri Chandler</li><li>Magic</li></ul></li></ul> |
|  | 5 | +Add Music -> Browse Files | music/merge/dir_set_b/[Scan this Dir] |
|  | 6 | Set Import Option | [3 Existing] = Overwrite |
|  | 7 | Verify Import Options Menu | <ul><li>BPM Source = ID3 Tag</li><li>Key Source = ID3 Tag</li></ul> |
|  | 8 | Set Import Option | [3 Existing] = Create New |
|  | 9 | Verify Import Options Menu | <ul><li>BPM Source = ID3 Tag</li><li>Key Source = ID3 Tag</li></ul> |
|  | 10 | Set Import Option | [3 Existing] = Skip |
|  | 11 | Verify Import Options Menu | <ul><li>BPM Source = N/A</li><li>Key Source = N/A</li></ul> |
|  | 12 | Start Import |  |
|  | 13 | Verify Artists Menu | <ul><li>Cornell West (ODM Mix) 126.2 : Bb</li><li>Kerri Chandler 122 : Fm</li><li>Magic 125 : C</li></ul></li></ul> |
|  | 14 | +Add Music -> Browse Files | music/merge/dir_set_b/[Scan this Dir] |
|  | 15 | Set Import Option + Start  | [3 Existing] = Overwrite |
|  |  | Verify Artists Menu | <ul><li>Cornell West (ODM Mix) 124 : Ab</li><li>Kerri Chandler 61.5 : Bbm</li><li>Magic 123 : F</li></ul></li></ul> |
|  | 16 | +Add Music -> Browse Files | music/merge/dir_set_a/[Scan this Dir] |
|  | 17 | Set Import Option + Start  | [3 Existing] = Create New |
|  | 18 | Verify Artists Menu | <ul><li>Cornell West (ODM Mix) 126.2 : Bb</li><li>Cornell West (ODM Mix) 124 : Ab</li><li>Kerri Chandler 122 : Fm</li><li>Kerri Chandler 61.5 : Bbm</li><li>Magic 125 : C</li><li>Magic 123 : F</li></ul></li></ul> |
| | | |
|  | 19 | Factory Reset | Lib |
|  | 20 | +Add Music -> Browse Files | music/merge/dir_set_a/[Scan this Dir] |
|  | 21 | Start Import |  |
|  | 22 | +Add Music -> Browse Files | music/merge/dir_set_c/[Scan this Dir] |
|  | 23 | Start Import |  |
|  | 24 | Verify Artists Menu | <ul><li>Zero QA Artist<ul><li>Cornell West (ODM Mix) [126.2 : Bb]</li><li>Kerri Chandler [122 : Fm]</li><li>Magic [125 : C]</li><li>Outside the Veil [250 : Ebm]</li><li>Teacher [124 : Db]</li><li>The Legend of Pat Nice [123 : Am]</li><li>Water (ODM Mix) [124 : Ab]</li></ul></li></ul> |



| Notes | 
| :--- |
|  |