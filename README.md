# Scambait-Tools
 Windows tools for pranking technical support scammers when they are connected to your virtual machine (VM).
 
 
upNotepad

upNotepad replaces the good old Notepad.exe.
Most technical support scammers will use Notepad to describe their ‘services’, aso.
upNotepad has some neat features which make their life like hell.
Features :

    distorts typing
    replaces words
    replaces numbers
    reversed text
    disable saving/loading files
    Live Hotkeys for triggering some features: increase/decrease numbers, replace words, random numbers, reversed text,

How to install?
Before we start:

    Install this program only on a virtual machines!
    You MUST HAVE owner rights for deleting or renaming msinfo32.exe in windows/system32. See also Tip 1 below.

 
STEPS

    STEP 1: run upNotepad_Setup.exe
    STEP 2: in C:/windows/  and  C:/windows/system32/  rename notepad.exe to p.e. BAKnotepad.exe or delete them
    STEP 3:
        for Win 32bit systems: skip and goto STEP 4
        for Win 64bit systems:
            open C:/windows/sysWOW64
            copy  notepad.exe to c:/windows/system32 and C:/windows/
    STEP 4: in C:/windows/  and  C:/windows/system32/  rename upnotepad.exe to notepad.exe
    STEP 5: run the ‘new’ notepad.exe
    STEP 6: press CTRL + ALT + Q to open the settings  for tweaking upNotepad
    
TIP 1: TakeOwnershipEx is a free tool that allows you to get full access to files and folders
       get it from: https://winaero.com/download.php?view.16

TIP 2: Remove the uninstall info in the registery
