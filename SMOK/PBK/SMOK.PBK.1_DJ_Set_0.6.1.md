## SMOK.PBK.1
**DJ Set (0.6.1)**

| PASS | FAIL | Build # | Timestamp | User |
| :---: | :---: | :--- | :--- | :--- |
| | | | | |


**SMK.PBK.1.0** Configure

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.0.0 | Configure | [[CONF.LIB.3](../../CONF/LIB/CONF.LIB.3_DJ_Smoke_Test_Lib.md)] DJ Smoke Test Lib (0.6.1) |
|  | SMOK.PBK.1.0.1 | Complete | [[TST.MIX.1](../../TST/MIX/TST.MIX.1_Preset.md)] Load Headphone DJ Preset |
|  | SMOK.PBK.1.0.2 | Connect | Stereo headphones or speaker to [[Output 1](xxx.md)] |
|  | SMOK.PBK.1.0.3 | Deploy<br>Widget | [[Memory Debug](xxx.md)] - monitor throughout test for steady-state memory leak |

**SMK.PBK.1.1** Load Track 1

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.1.0 | Load | Deck 1: Water (ODM Mix) |
|  | SMOK.PBK.1.1.1 | Control | [[Deck 1 Fader](xxx.md)] Full up |
|  | SMOK.PBK.1.1.2 | Control | [[Deck 2 Fader](xxx.md)] Full up |
|  | SMOK.PBK.1.1.3 | Control | [[Crossfade](xxx.md)] Centered |
|  | SMOK.PBK.1.1.4 | Control | Deck 1 Play |
|  | SMOK.PBK.1.1.5 | Verify | Stereo audio signal is present at [[Output 1](xxx.md)] |
|  | SMOK.PBK.1.1.6 | Control | Deck 1 Activate Cuepoint #2  |
|  | SMOK.PBK.1.1.7 | Control | Repeatedly Press Cue |
|  | SMOK.PBK.1.1.8 | Control | Deck 1 Activate Cuepoint #1  |
|  | SMOK.PBK.1.1.9 | Control | Deck 1 Play |
|  | SMOK.PBK.1.1.10 | Control | Deck 1 Adjust EQ - Lo/Mid/Hi |

**SMK.PBK.1.2** Load Track 2

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.2.0 | Load | Deck 2: Cornell West (ODM Mix) |
|  | SMOK.PBK.1.2.1 | Control | Deck 2 Activate Cuepoint #1  |
|  | SMOK.PBK.1.2.2 | Control | Deck 2 Play |
|  | SMOK.PBK.1.2.3 | Control | Deck 2 Nudge to beatmatch with Deck 1 |
|  | SMOK.PBK.1.2.4 | Control | [[Crossfade](xxx.md)] Full left, then full right, then center |
|  | SMOK.PBK.1.2.5 | Control | [[Deck 1 Fader](xxx.md)] Full down, then full up |
|  | SMOK.PBK.1.2.6 | Control | [[Deck 2 Fader](xxx.md)] Full down, then full up |

**SMK.PBK.1.3** Check Tempo Adjust

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.3.0 | Control | Set BPM to 100 |
|  | SMOK.PBK.1.3.1 | Control | Set BPM to 150 |
|  | SMOK.PBK.1.3.2 | Control | Set BPM to 124 |

**SMK.PBK.1.4** Check Loop/Skip

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.4.0 | Control | Deck 2 Enable Loop |
|  | SMOK.PBK.1.4.1 | Control | Deck 2 Adjust Loop Length |
|  | SMOK.PBK.1.4.2 | Control | Deck 2 Adjust Loop Start |
|  | SMOK.PBK.1.4.3 | Control | Deck 2 Adjust Loop Skip |
|  | SMOK.PBK.1.4.4 | Control | Deck 2 Disable Loop |
|  | SMOK.PBK.1.4.5 | Control | Deck 2 Adjust Beat Skip |
|  | SMOK.PBK.1.4.6 | Control | Deck 2 Reset Beat Skip |

**SMK.PBK.1.5** Check Headphone Cue & Deck Gain

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.5.0 | Control | [[Deck 1 Fader](xxx.md)] Full down |
|  | SMOK.PBK.1.5.1 | Control | [[Deck 2 Fader](xxx.md)] Full down |
|  | SMOK.PBK.1.5.2 | Verify | No audio signal is present at [[Output 1](xxx.md)] |
|  | SMOK.PBK.1.5.3 | Control | Deck 1 Enable Headphone Cue |
|  | SMOK.PBK.1.5.4 | Control | Deck 2 Enable Headphone Cue |
|  | SMOK.PBK.1.5.5 | Verify | Deck 1 & Deck 2 audio signals are present at [[Output 1](xxx.md)] |
|  | SMOK.PBK.1.5.6 | Control | Deck 1 Adjust Headphone Cue Gain |
|  | SMOK.PBK.1.5.7 | Control | Deck 2 Adjust Headphone Cue Gain |
|  | SMOK.PBK.1.5.8 | Verify | Deck 1 & Deck 2 audio signals respond to gain adjustment |
|  | SMOK.PBK.1.5.9 | Connect | Stereo headphones or speaker to [[Output 2](xxx.md)] |
|  | SMOK.PBK.1.5.10 | Verify | No audio signal is present at [[Output 2](xxx.md)] |
|  | SMOK.PBK.1.5.11 | Control | [[Deck 1 Fader](xxx.md)] Full up |
|  | SMOK.PBK.1.5.12 | Control | [[Deck 2 Fader](xxx.md)] Full up |
|  | SMOK.PBK.1.5.13 | Verify | Deck 1 & Deck 2 audio signals are present at [[Output 2](xxx.md)] |
|  | SMOK.PBK.1.5.14 | Control | Deck 1 Adjust Track Gain |
|  | SMOK.PBK.1.5.15 | Control | Deck 2 Adjust Track Gain |
|  | SMOK.PBK.1.5.16 | Verify | Deck 1 & Deck 2 audio signals respond to gain adjustment |
|  | SMOK.PBK.1.5.17 | Connect | Stereo headphones or speaker to [[Output 1](xxx.md)] |
|  | SMOK.PBK.1.5.18 | Control | Deck 1 Disable Headphone Cue |
|  | SMOK.PBK.1.5.19 | Control | Deck 2 Disable Headphone Cue |

**SMK.PBK.1.6** Load Track 3

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.6.0 | Load | Deck 1: Outside the Veil (ODM Mix) |
|  | SMOK.PBK.1.6.1 | Control | Deck 1 Set Sync Mult to x2 |
|  | SMOK.PBK.1.6.2 | Control | Deck 1 Play |
|  | SMOK.PBK.1.6.3 | Control | Deck 1 Nudge to beatmatch with Deck 2 |
|  | SMOK.PBK.1.6.4 | Control | [[Crossfade](xxx.md)] Centered |

**SMK.PBK.1.7** Momentary Deck Select

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.7.0 | Control | Deck 1 Btn Press |
|  | SMOK.PBK.1.7.1 | Control | Deck 2 Btn Hold |
|  | SMOK.PBK.1.7.2 | Control | Deck 2 Adjust EQ |
|  | SMOK.PBK.1.7.3 | Control | Deck 2 Nudge Playback |
|  | SMOK.PBK.1.7.4 | Control | Deck 2 Pause |
|  | SMOK.PBK.1.7.5 | Control | Deck 2 Play |
|  | SMOK.PBK.1.7.6 | Control | Deck 2 Btn Release |
|  | SMOK.PBK.1.7.7 | Verify | Deck 1 is Current Deck |

**SMK.PBK.1.8** Filter

| Pass |          ID           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
|  | SMOK.PBK.1.8.0 | Control | Deck 1 Adjust Bi-modal Filter |
|  | SMOK.PBK.1.8.1 | Control | Deck 1 Reset Bi-modal Filter |



| Notes | 
| :--- |
|  |