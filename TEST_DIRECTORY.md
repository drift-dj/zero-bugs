# Smoke Tests

# Feature Tests

## Library

### TST.LIB.1 Playlists Menu
### TST.LIB.2 Artists Menu
### TST.LIB.3 Genre Menu
### TST.LIB.4 BPM Menu
### TST.LIB.5 Key Menu
### TST.LIB.6 Errors Menu
### TST.LIB.7 Add Music Menu

### TST.LIB.8 Song Edit
- [TST.LIB.8.0](TST/LIB/8_Song_Edit/TST.LIB.8_Song_Edit.md#TST.LIB.8.0) Remove Song

### TST.LIB.9 Import

#### TST.LIB.9.0 Import Local - Single File
- [TST.LIB.9.0.0](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.0) New File - Empty Library
- [TST.LIB.9.0.1](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.1) New File - Populated Library
- [TST.LIB.9.0.2](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.2) Existing file - Update BPM/Key
- [TST.LIB.9.0.3](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.3) Existing file - Ignore BPM/Key
- [TST.LIB.9.0.4](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.4) New file - Error - Unsupported Sample Rate
- [TST.LIB.9.0.5](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.5) New file - Error - Unsupported Codec
- [TST.LIB.9.0.6](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.6) New file - Error - Unsupported Filetype
- [TST.LIB.9.0.7](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.7) Existing File - Overwrite Error w/Valid File
- [TST.LIB.9.0.8](TST/LIB/9_Import/TST.LIB.9.0_Import_Local_Single_File.md#TST.LIB.9.0.8) Existing File - Change Path

#### TST.LIB.9.1 Import USB Drive - Single File

#### TST.LIB.9.2 Import Local - File Directory
- [TST.LIB.9.2.0](TST/LIB/9_Import/TST.LIB.9.2_Import_Local_File_Dir.md#TST.LIB.9.2.0) Dir of New Files
- [TST.LIB.9.2.1](TST/LIB/9_Import/TST.LIB.9.2_Import_Local_File_Dir.md#TST.LIB.9.2.1) Dir of Existing Files - Skip
- [TST.LIB.9.2.2](TST/LIB/9_Import/TST.LIB.9.2_Import_Local_File_Dir.md#TST.LIB.9.2.2) Dir of Existing Files - Overwrite
- [TST.LIB.9.2.3](TST/LIB/9_Import/TST.LIB.9.2_Import_Local_File_Dir.md#TST.LIB.9.2.3) Dir of Existing Files - Create New
- [TST.LIB.9.2.4](TST/LIB/9_Import/TST.LIB.9.2_Import_Local_File_Dir.md#TST.LIB.9.2.4) Dir of Mixed New/Existing Files
- [TST.LIB.9.2.5](TST/LIB/9_Import/TST.LIB.9.2_Import_Local_File_Dir.md#TST.LIB.9.2.5) Dir of Mixed New/Existing Files - Errors




#### TST.LIB.9.3 Import USB Drive - File Directory

#### TST.LIB.9.4 Import Local - Rekordbox XML
- New Lib XML
- Existing Lib XML
- Mixed New/Existing Lib XML

#### TST.LIB.9.5 Import USB Drive - Rekordbox XML



### TST.LIB.10 ID3 Tags
- [TST.LIB.10.0](TST/LIB/10_Tags/TST.LIB.9_Tags.md#tst.lib.9.0) No Tags (t0)
- [TST.LIB.10.1](TST/LIB/9_Tags/TST.LIB.9_Tags.md#tst.lib.9.1) Artist (t1)
- [TST.LIB.10.2](TST/LIB/9_Tags/TST.LIB.9_Tags.md#tst.lib.9.2) Title (t2)
- [TST.LIB.10.3](TST/LIB/9_Tags/TST.LIB.9_Tags.md#tst.lib.9.3) Artist+Title (t3)
- [TST.LIB.10.4](TST/LIB/9_Tags/TST.LIB.9_Tags.md#tst.lib.9.4) Playback Metadata (t4)
- [TST.LIB.10.5](TST/LIB/9_Tags/TST.LIB.9_Tags.md#tst.lib.9.5) BPM Errata 1 (t5)

### TST.LIB.11 File Formats
- [TST.LIB.10.0](TST/LIB/10_File_Formats/TST.LIB.10_File_Formats.md#tst.lib.10.0) MP3
    - Import Single
    - Import Dir
    - Playback
        - Song Edit
        - Scrub
        - Loop
- [TST.LIB.10.1](TST/LIB/10_File_Formats/TST.LIB.10_File_Formats.md#tst.lib.10.1) WAV
    - Import Single
    - Import Dir
    - Playback
        - Song Edit
        - Scrub
        - Loop
- [TST.LIB.10.2](TST/LIB/10_File_Formats/TST.LIB.10_File_Formats.md#tst.lib.10.2) AIF
    - Import Single
    - Import Dir
    - Playback
        - Song Edit
        - Scrub
        - Loop
- [TST.LIB.10.3](TST/LIB/10_File_Formats/TST.LIB.10_File_Formats.md#tst.lib.10.3) FLAC
    - Import Single
    - Import Dir
    - Playback
        - Song Edit
        - Scrub
        - Loop
- [TST.LIB.10.4](TST/LIB/10_File_Formats/TST.LIB.10_File_Formats.md#tst.lib.10.4) AAC
    - Import Single
    - Import Dir
    - Playback
        - Song Edit
        - Scrub
        - Loop
- Mixed Import

## Playback

## Mixer Panel

## USB Panel

## Settings Panel

### TST.SET.1 UI
- [TST.SET.1.0](TST/SET/TST.SET.1_UI.md#tst.set.1.0) Brightness
- [TST.SET.1.1](TST/SET/TST.SET.1_UI.md#tst.set.1.1) Refresh Rate
- [TST.SET.1.2](TST/SET/TST.SET.1_UI.md#tst.set.1.2) Hide Unplayable Songs
- [TST.SET.1.3](TST/SET/TST.SET.1_UI.md#tst.set.1.3) Show BPM
- [TST.SET.1.4](TST/SET/TST.SET.1_UI.md#tst.set.1.4) Show Key
- [TST.SET.1.5](TST/SET/TST.SET.1_UI.md#tst.set.1.5) Show Camelot



### TST.SET.2 System

#### TST.SET.2.1 Reboot
- [TST.SET.2.1](TST/SET/TST.SET.2_System.md#tst.set.2.1) Reboot

#### TST.SET.2.2 Factory Reset
- [TST.SET.2.2.0](TST/SET/TST.SET.2_System.md#tst.set.2.2.0) Full Factory Reset
- [TST.SET.2.2.1](TST/SET/TST.SET.2_System.md#tst.set.2.2.1) Library DB Reset
- [TST.SET.2.2.2](TST/SET/TST.SET.2_System.md#tst.set.2.2.2) User Settings Reset
- [TST.SET.2.2.3](TST/SET/TST.SET.2_System.md#tst.set.2.2.3) Mixer Settings Reset
- [TST.SET.2.2.4](TST/SET/TST.SET.2_System.md#tst.set.2.2.4) USB State Reset
- [TST.SET.2.2.5](TST/SET/TST.SET.2_System.md#tst.set.2.2.5) USB Device DB Reset

#### TST.SET.2.3 USB Boot Mode
- [TST.SET.2.3.0](TST/SET/TST.SET.2_System.md#tst.set.2.3.0) USB Boot Mode Retain
- [TST.SET.2.3.1](TST/SET/TST.SET.2_System.md#tst.set.2.3.1) USB Boot Mode Offline
- [TST.SET.2.3.2](TST/SET/TST.SET.2_System.md#tst.set.2.3.2) USB Boot Mode Host
- [TST.SET.2.3.3](TST/SET/TST.SET.2_System.md#tst.set.2.3.3) USB Boot Mode Gadget

#### TST.SET.2.4 Software - Install Apps
- [TST.SET.2.4.0](TST/SET/TST.SET.2_System.md#tst.set.2.4.0) Install App

#### TST.SET.2.5 Software - DriftOS
- [TST.SET.2.5.0](TST/SET/TST.SET.2_System.md#tst.set.2.5.0) Update DriftOS