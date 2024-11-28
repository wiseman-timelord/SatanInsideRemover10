# DisableSatanInside-10
Status: Working

### Description
This is a simple program to disable all Windows 10 services related to Active Directory, that are not specifically required for, Internet or Games or Media. I have tested it, and my, Laptop and Desktop, seemed ok, and could connect to wireless network to use internet fine. This program is one of those things you would do last when installing a windows 10 computer, probably after using (multiple) privacy related programs, as well as, my other program [AntiMsVirus](https://github.com/wiseman-timelord/AntiMsVirus). My own philosophy is people should be using, Windows 10 based PC for the Games/Media/Offline and Ubuntu 24.10 for Work/Web. See below in preview if you are interested in which services are affected, and do it manually if you only want some of the tweaks. Also you should, research and know, what each of the ones below actually does, in brief, copy the list and ask GPT for an explanation.

### Features
- Glorified menu with simple interface.
- Admin and OS, check at start.
- Confirmations of each modification.
- Pause at end of Enable/Disable for review.

### Preview
- Main Menu...
```
========================================================================================================================
    Disable Satan Inside 10
========================================================================================================================

    Affected Services:
    - Netlogon
    - Windows Time
    - Remote Desktop Configuration
    - Remote Desktop Services
    - Remote Registry
    - IP Helper
    - SSDP Discovery
    - Function Discovery Provider Host
    - Function Discovery Resource Publication
    - Windows Error Reporting Service
    - Diagnostic Policy Service
    - Windows Update

------------------------------------------------------------------------------------------------------------------------
Selection; Disable All = D, Enable All = E, Exit Program = X: 
```
- Disable Processes...
```
========================================================================================================================
    Disabling Services...
========================================================================================================================
Processing service: Netlogon
Service Netlogon disabled successfully.
Processing service: W32Time
Service W32Time disabled successfully.
Processing service: SessionEnv
Service SessionEnv disabled successfully.
Processing service: TermService
Service TermService disabled successfully.
Processing service: RemoteRegistry
Service RemoteRegistry disabled successfully.
Processing service: iphlpsvc
Service iphlpsvc disabled successfully.
Processing service: SSDPSRV
Service SSDPSRV disabled successfully.
Processing service: fdPHost
Service fdPHost disabled successfully.
Processing service: FDResPub
Service FDResPub disabled successfully.
Processing service: WerSvc
Service WerSvc disabled successfully.
Processing service: DPS
Service DPS disabled successfully.
Processing service: wuauserv
Service wuauserv disabled successfully.

Please restart your computer after exiting the program.
```

## Requirements
- Windows 10 - Pretty sure any variant of 10 will wodk.
- Batch Support - Scripting Host Enabled.
- Administrator Account - You have Admin rights.

### Instructions
1. Create restore point from `Control Panel>System>System Restore>Create`.
2. Right click on the batch, then select "Run as Administrator".
3. Choose Disable All from menu with `D` key, and check feedback on screen.
4. Restart computer, and test everything you intend to use still works.
- If you get, errors or issues, just re-enable, the relevant or all affected, services; it wont affect boot unless you are doing something like network boot or rely upon network resources/sharing.

## Notation
- Lore: Active Directory (AD) used to be known as ADAM, and while the closet case Satanists may claim Adam is the first man, in actual historic recording, Adamu was a deity that was smashed into 1000s of slave beings, becaues he subversively, manipulated and turned, the gods on one another alike a Rupert Murdock, and so, the ADAMU is by definition SATAN. Depends what you believe; did you do your own comprehensive research or did a slaver organizations controlled by false archons just hand you their approved version of history.
- Its interesting as a concept, because a pro Windows home user of many years experience will know some of those services should definately be disabled unless you specifically need to use them, especially after the bulk of the install process is done, but how ALL of them pretty much are falling within AD, albeit can you argue about the "Devil/Satan Inside" meme could logically have correlation with these services.
- I did a session with GPT4o1-Mini and figured out ALL the services related to Active Directory, that I could safely disable, while still being able to access the internet, as well as play, games and movies and music. I then did the modifications manually to my Desktop, and my Windows 10 Desktop PC still booted fine, I then used a combination of, GPT4o1 and GPT4o1-Mini, to relevantly, create and complete, the script, I then tested the script on my Windows 10 Laptop, with the results shown above in preview.

## Warnings
- You should know what you are doing, and research what each one does. 
- I say again do not use this script, unless you have backed up your settings.  
