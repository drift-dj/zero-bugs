## TST.LIB.9.6.0
**Fix Song Error**

| PASS | FAIL | Build # | Timestamp | User |
| :--: | :--: | :------ | :-------- | :--- |
|  ✅   |      |         |           |      |

| Pass | ID               |      Action | Reference                                                                                 |
| :--: | :--------------- | ----------: | :---------------------------------------------------------------------------------------- |
|  ✅   | TST.LIB.9.6.0.0  |   Configure | [[CONF.LIB.2](../../../CONF/LIB/CONF.LIB.2_Error_QA_Lib.md) Install QA Lib: Error Files]  |
|  ✅   | TST.LIB.9.6.0.1  |    Settings | UI/Hide Unplayable Songs = false                                                          |
|  ✅   | TST.LIB.9.6.0.2  |    Navigate | Library/Artists/Unknown Artist/Missing 44k WAV Ramp/Song Edit                             |
|  ✅   | TST.LIB.9.6.0.3  |      Verify | ![Song Edit Error](images/TST.LIB.9.6.0.3.bmp)<br>[[Song Error](xxx.md)] appears          |
|  ✅   | TST.LIB.9.6.0.4  |      Select | ![Edit Filepath](images/TST.LIB.9.6.0.4.bmp)<br>[[Filepath edit](xxx.md)]                 |
|  ✅   | TST.LIB.9.6.0.5  | File Browse | music/format/wav/ramp_st_44_f32_t0.wav                                                    |
|  ✅   | TST.LIB.9.6.0.6  |      Verify | ![Rescan](images/TST.LIB.9.6.0.6.bmp)<br>[[Rescan dialog](xxx.md)] appears                |
|  ✅   | TST.LIB.9.6.0.7  |      Select | Okay ![Okay](images/TST.LIB.9.4.0.3.bmp)                                                  |
|  ✅   | TST.LIB.9.6.0.8  |      Verify | ![Import](images/TST.LIB.9.6.0.8.bmp)<br>[[Import](xxx.md)] appears                       |
|  ✅   | TST.LIB.9.6.0.9  |      Select | Start ![Start](images/TST.LIB.9.6.0.9.bmp)                                                |
|  ✅   | TST.LIB.9.6.0.10 |      Verify | ![Song Edit No Error](images/TST.LIB.9.6.0.10.bmp)<br>Song Edit appears (without error)   |
|  ✅   | TST.LIB.9.6.0.11 |    Navigate | Library/Artists/Unknown Artist/Missiing 44k WAV Ramp                                      |
|  ⚠️  | TST.LIB.9.6.0.12 |      Verify | ![Menu Item No Error](images/TST.LIB.9.6.0.12.bmp)<br>Menu item Error flag doesn't appear |
|  ✅   | TST.LIB.9.6.0.13 | Load Deck 1 | Unknown Artist/Missing 44k WAV Ramp                                                       |
|  ✅   | TST.LIB.9.6.0.14 |      Verify | Deck 1 loads and playback functions                                                       |

| Notes | 
| :--- |
|  |