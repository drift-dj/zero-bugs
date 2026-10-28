NOTES: 
1. These CONF.LIB flows are essentially a shortcut to performing a Library Reset flow then importing a set of songs.
2. These CONF.LIB flows overwrite the existing library .db file and waveform directories which would be created during a normal import flow.
1. You do not need to perform Library Reset before performing a CONF.LIB flow. 
2. Importing additional music to the Library after performing a CONF.LIB flow is expected to function normally. 

## CONF.LIB.2
**Error QA Lib**
A Library with all error types present 

| ID           | Action | Reference |
| :------------------- | --------: | :------- |
| CONF.LIB.2.0 | Verify | [zero-bugs]/music/rb/Contents/ dir has been copied to [Zero]/Contents/ |
| CONF.LIB.2.0 | Verify | [zero-bugs]/music/merge/ dir has been copied to [Zero]/music/merge/ |
| CONF.LIB.2.1 | Verify | [zero-bugs]/music/lib/CONF.LIB.2/ dir has been copied to [Zero]/music/lib/CONF.LIB.2 |
| CONF.LIB.2.2 | Navigate | Control Panels/Settings/Developer/DATABASE/Install Library DB |
| CONF.LIB.2.3 | File Browse | /music/lib/CONF.LIB.2/v1/zero.db |
| CONF.LIB.2.4 | Verify | Zero Reboot |