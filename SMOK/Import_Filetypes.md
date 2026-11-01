## Import Filetypes

| Result | Line | Action | Reference |
| :---: | :- | --------: | :------- |
|  |  | **Single File Import** | |
|  | 1 | Factory Reset | Lib |
|  | 2 | Settings | Hide Unplayable Songs = false |
|  | 3 | Import | music/format/mp3/ramp_st_44_320.mp3 |
|  | 4 | Import | music/format/wav/ramp_st_44_f32_t0.wav |
|  | 5 | Import | music/format/aif/ramp_st_44_f32_t0.aif |
|  | 6 | Import | music/format/flac/ramp_st_44_f32_t0.flac |
|  | 7 | Verify Artists Menu | <ul><li>No Artist<ul><li>ramp_st_44_320.mp3</li><li>ramp_st_44_f32_t0.aif</li><li>ramp_st_44_f32_t0.flac</li><li>ramp_st_44_f32_t0.wav</li></ul></li></ul> |
|  | | | |
|  |  | **Invalid Imports** | |
|  | 8 | Import | music/format/aac/ramp_s_44_192k_t0.m4a |
|  | 9 | Verify | Invalid Codec appears |
|  | 10 | Import | music/format/wav/ramp_st_48_f32_t0.wav |
|  | 11 | Verify | Invalid Sample Rate appears |
|  | 12 | Import | music/format/invalid/boot.png |
|  | 13 | Verify | Invalid Filetype appears |
|  | | | |
|  |  | **Directory Import** | |
|  | 14 | Factory Reset | Lib |
|  | 15 | Settings | Hide Unplayable Songs = true |
|  | 16 | +Add Music -> Browse Files | music/format/[Scan this dir] |
|  | 17 | Set Import Options | [4 Errors] = Import |
|  | 18 | Verify | Import total = [18 songs] |
|  | 19 | Start Import | |
|  | 20 | Verify Artists Menu | <ul><li>No Artist<ul><li>ramp_jst_44_320.mp3</li><li>ramp_m_44_320.mp3</li><li>ramp_m_44_f32_t0.aif</li><li>ramp_m_44_f32_t0.flac</li><li>ramp_m_44_f32_t0.wav</li><li>ramp_st_44_320.mp3</li><li>ramp_st_44_f32_t0.aif</li><li>ramp_st_44_f32_t0.flac</li><li>ramp_st_44_f32_t0.wav</li><li>ramp_st_44_s16_t0.aif</li><li>ramp_st_44_s16_t0.flac</li><li>ramp_st_44_s16_t0.wav</li></ul></li></ul> |
|  | 21 | Settings | Hide Unplayable Songs = false |
|  | 22 | Verify Errors Menu | <ul><li>No Artist<ul><li>44k AAC Ramp</li><li>Zero QA Artist - Magic</li><li>ramp_s_44_192k_t0.m4a</li><li>ramp_st_48_f32_t0.wav</li></ul></li></ul> |
|  | | | |
|  |  | **Rekordbox Import** | |
|  | 23 | Factory Reset | Lib |
|  | 24 | Settings | Hide Unplayable Songs = true |
|  | 25 | +Add Music -> Rekordbox XML | <ul><li>*XML:* music/rb/rb_long_string.xml</li><li>*Scan Dir:* music/edge_cases/long_filename</li></ul> |
|  | 26 | Set Import Options | [1 Error] = Import |
|  | 27 | Verify | Import total = [15 songs] |
|  | 28 | Start Import | |
|  | 29 | Verify Artists Menu | <ul><li>No Artist<ul><li>ramp_jst_44_320.mp3</li><li>ramp_m_44_320.mp3</li><li>ramp_m_44_f32_t0.aif</li><li>ramp_m_44_f32_t0.flac</li><li>ramp_m_44_f32_t0.wav</li><li>ramp_st_44_320.mp3</li><li>ramp_st_44_f32_t0.aif</li><li>ramp_st_44_f32_t0.flac</li><li>ramp_st_44_f32_t0.wav</li><li>ramp_st_44_s16_t0.aif</li><li>ramp_st_44_s16_t0.flac</li><li>ramp_st_44_s16_t0.wav</li></ul></li></ul> |