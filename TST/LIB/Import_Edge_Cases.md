## Import Edge Cases

| Result | Line | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | 1 | Reset to QA Lib | Library 2 - Errors |
|  |   | **Edit Filepath** |
|  | 2 | Open Song Edit View | Library/Artists/Four Foot Louise/Magic |
|  | 3 | Edit Filepath | music/dj_playback_smoke_01/music/Four Foot Louise - Pat Nice.mp3 |
|  | 4 | Verify | Filepath field = music/dj_playback_smoke_01/music/Four Foot Louise - Pat Nice.mp3 |
|  | 5 | Exit + Return to Song Edit |  |
|  | 6 | Verify | Filepath field = music/dj_playback_smoke_01/music/Four Foot Louise - Pat Nice.mp3 |
|  |   |  |
|  |   | **Sample Rate Error** |
|  | 7 | Edit Filepath | music/format/mp3/magic-48-128k-st.mp3 |
|  | 8 | Verify | Sample Rate Error appears |
|  |   |  |
|  |   | **Unsupported Codec Error** |
|  | 9 | Edit Filepath | music/format/ogg/magic-44-128k-st.ogg |
|  | 10 | Verify | Usupported Codec Error appears |
|  |   |  |
|  |   | **File Format Error** |
|  | 11 | Edit Filepath | music/format/invalid/boot.png |
|  | 12 | Verify | File Format Error appears |
|  |   |  |
|  |   | **Long ID3 Tags** |
|  | 13 | Settings | <ul><li>UI/Hide Unplayable Songs = false</li></ul> |
|  | 14 | +Add Music -> Browse Files | music/tag/t6/[Scan this Dir] |
|  | 15 | Set Import Option | [3 Existing] = Overwrite |
|  | 16 | Verify Artists Menu | [T6 - 1...] and [T6 - 2...] appear without error |
|  |   |  |
|  |   | **Long Rekordbox Strings** |
|  | 16 | +Add Music -> Rekordbox XML | <ul><li>*XML:* **music/rb/rb_xml_c.xml**</li><li>*Scan Dir:* / (Media root)</li></ul> |
|  | 17 | Set Import Option | [X Errors] = Import |
|  | 18 | Start Import | |
|  | 19 | Verify Artists Menu | [T6 - 1...] and [T6 - 2...] appear without error |
|  | 20 | Open Song Edit View | Library/Artists/[T6 - 1...] |
