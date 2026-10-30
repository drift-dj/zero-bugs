## Smoke Test: DJ Set (0.6.1)

| Result |          Step           | Action | Reference |
| :---: | :------------------- | --------: | :------- |
| | | **Configure** | |
|  | 1 | Configure | [[CONF.LIB.3](../../CONF/LIB/CONF.LIB.3_DJ_Smoke_Test_Lib.md)] DJ Smoke Test Lib (0.6.1) |
|  | 2 | Navigate | Control Panels/Mixer/Load/Headphone DJ |
|  | 3 | Connect | Stereo headphones or speaker to [[Output 1](xxx.md)] |
|  | 4 | Deploy<br>Widget | [[Memory Debug](xxx.md)] - monitor throughout test for steady-state memory leak |
| | |  | |
| | | **Load Track 1** | |
|  | 5 | Load | Deck 1: Water (ODM Mix) |
|  | 6 | Control | [[Deck 1 Fader](xxx.md)] Full up |
|  | 7 | Control | [[Deck 2 Fader](xxx.md)] Full up |
|  | 8| Control | [[Crossfade](xxx.md)] Centered |
|  | 9 | Control | Deck 1 Play |
|  | 10 | Verify | Stereo audio signal is present at [[Output 1](xxx.md)] |
|  | 11 | Control | Deck 1 Activate Cuepoint #2  |
|  | 12 | Control | Repeatedly Press Cue |
|  | 13 | Control | Deck 1 Activate Cuepoint #1  |
|  | 14 | Control | Deck 1 Play |
|  | 15 | Control | Deck 1 Adjust EQ - Lo/Mid/Hi |
| | |  | |
| | | **Load Track 2** | |
|  | 16 | Load | Deck 2: Cornell West (ODM Mix) |
|  | 17 | Control | Deck 2 Activate Cuepoint #1  |
|  | 18 | Control | Deck 2 Play |
|  | 19 | Control | Deck 2 Nudge to beatmatch with Deck 1 |
|  | 20 | Control | [[Crossfade](xxx.md)] Full left, then full right, then center |
|  | 21 | Control | [[Deck 1 Fader](xxx.md)] Full down, then full up |
|  | 22 | Control | [[Deck 2 Fader](xxx.md)] Full down, then full up |
| | |  | |
| | | **Check Tempo Adjust** | |
|  | 23 | Control | Set BPM to 100 |
|  | 24 | Control | Set BPM to 150 |
|  | 25 | Control | Set BPM to 124 |
| | |  | |
| | | **Check Loop + Skip** | |
|  | 26 | Control | Deck 2 Enable Loop |
|  | 27 | Control | Deck 2 Adjust Loop Length |
|  | 28 | Control | Deck 2 Adjust Loop Start |
|  | 29 | Control | Deck 2 Adjust Loop Skip |
|  | 30 | Control | Deck 2 Disable Loop |
|  | 31 | Control | Deck 2 Adjust Beat Skip |
|  | 32 | Control | Deck 2 Reset Beat Skip |
| | |  | |
| | | **Check Headphone Cue + Deck Gain** | |
|  | 33 | Control | [[Deck 1 Fader](xxx.md)] Full down |
|  | 34 | Control | [[Deck 2 Fader](xxx.md)] Full down |
|  | 35 | Verify | No audio signal is present at [[Output 1](xxx.md)] |
|  | 36 | Control | Deck 1 Enable Headphone Cue |
|  | 37 | Control | Deck 2 Enable Headphone Cue |
|  | 38 | Verify | Deck 1 & Deck 2 audio signals are present at [[Output 1](xxx.md)] |
|  | 39 | Control | Deck 1 Adjust Headphone Cue Gain |
|  | 40 | Control | Deck 2 Adjust Headphone Cue Gain |
|  | 41 | Verify | Deck 1 & Deck 2 audio signals respond to gain adjustment |
|  | 42 | Connect | Stereo headphones or speaker to [[Output 2](xxx.md)] |
|  | 43 | Verify | No audio signal is present at [[Output 2](xxx.md)] |
|  | 44 | Control | [[Deck 1 Fader](xxx.md)] Full up |
|  | 45 | Control | [[Deck 2 Fader](xxx.md)] Full up |
|  | 46 | Verify | Deck 1 & Deck 2 audio signals are present at [[Output 2](xxx.md)] |
|  | 47 | Control | Deck 1 Adjust Track Gain |
|  | 48 | Control | Deck 2 Adjust Track Gain |
|  | 49 | Verify | Deck 1 & Deck 2 audio signals respond to gain adjustment |
|  | 50 | Connect | Stereo headphones or speaker to [[Output 1](xxx.md)] |
|  | 51 | Control | Deck 1 Disable Headphone Cue |
|  | 52 | Control | Deck 2 Disable Headphone Cue |
| | |  | |
| | | **Load Track 3** | |
|  | 53 | Load | Deck 1: Outside the Veil (ODM Mix) |
|  | 54 | Control | Deck 1 Set Sync Mult to x2 |
|  | 55 | Control | Deck 1 Play |
|  | 56 | Control | Deck 1 Nudge to beatmatch with Deck 2 |
|  | 57 | Control | [[Crossfade](xxx.md)] Centered |
| | |  | |
| | | **Check Tempo Adjust** | |
|  | 58 | Control | Deck 1 Btn Press |
|  | 59 | Control | Deck 2 Btn Hold |
|  | 60 | Control | Deck 2 Adjust EQ |
|  | 61 | Control | Deck 2 Nudge Playback |
|  | 62 | Control | Deck 2 Pause |
|  | 63 | Control | Deck 2 Play |
|  | 64 | Control | Deck 2 Btn Release |
|  | 65 | Verify | Deck 1 is Current Deck |
| | |  | |
| | | **Filter** | |
|  | 66 | Control | Deck 1 Adjust Bi-modal Filter |
|  | 67 | Control | Deck 1 Reset Bi-modal Filter |



| Notes | 
| :--- |
|  |