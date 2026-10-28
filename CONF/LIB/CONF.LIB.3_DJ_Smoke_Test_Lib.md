NOTES: 
1. These CONF.LIB flows are essentially a shortcut to performing a Library Reset flow then importing a set of songs.
2. These CONF.LIB flows overwrite the existing library .db file and waveform directories which would be created during a normal import flow.
1. You do not need to perform Library Reset before performing a CONF.LIB flow. 
2. Importing additional music to the Library after performing a CONF.LIB flow is expected to function normally. 

## CONF.LIB.3
**DJ Smoke Test Lib (0.6.1)**
A Library of mixable tracks for running DJ Playback smoke tests

| ID           | Action | Reference |
| :------------------- | --------: | :------- |
| CONF.LIB.3.0 | Verify | [zero-bugs]/music/rb/Contents/ dir has been copied to [Zero]/Contents/ |
| CONF.LIB.3.1 | Verify | [zero-bugs]/music/lib/CONF.LIB.3/ dir has been copied to [Zero]/music/lib/CONF.LIB.3 |
| CONF.LIB.3.2 | Navigate | Control Panels/Settings/Developer/DATABASE/Install Library DB |
| CONF.LIB.3.3 | File Browse | /music/lib/CONF.LIB.3/v1/zero.db |
| CONF.LIB.3.4 | Verify | Zero Reboot |