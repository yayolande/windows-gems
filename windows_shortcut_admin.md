# Windows Useful Shortcut For Advanced Users


## Custom install path

The other day, I downloaded *cmder* and was wandering where to store it so that it can in a predictable place and safe from accidental deletion.
Here come, `%localappdata%\Programs`. Just like `%programfiles%`, which is a global location (accessible by all users), you can install programs there. However, the difference is in the fact that `%localappdata%\Programs` is only accessible by a single user.


## How to run a custom commander inside "RUN" dialob box

To access an app from "RUN", just add the path of the executable to the PATH environment variable.
For this, apon "RUN", then type "ms-settings:". Then follow Settings->System->About->Device Specifications->Advanced System Settings
->Environment variable
Once reached, modify the "PATH" variable.



## How to create a keyboard shortcut for PowerShell and Cmd and Cmder

To create a keyboard shortcut, first create a shortcut to the application if it doesn't exist already.
Don't keep that shortcut into the desktop, move them to "%appdata%\Microsoft\Windows\Start Menu\" and place it to new directory.
Once done, right-click on the shortcut and open "Properties (Alt + Enter)". 
Once the "properties" dialog open, it should do it on the "Shortcut" tab, then look for "Shortcut Key" field. 
Inside it, type your shortcut keyboard combination.

**NB**: Powershell and Cmd already have a pre-existing shortcut inside "%appdata%\Microsoft\Windows\Start Menu\Programs\Windows PowerShell" and "C:\Users\SDjumo\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\System Tools" respectively


Reference:
* [launch command prompt win 10](https://www.windowscentral.com/how-launch-command-prompt-standard-and-admin-windows-10)



## Shell commands

On Windows, the shell commands are shortcut to a few useful location that some power users may need.
They make it easy to access deeply buried system folders.
Launch it, you need to call the "RUN" Dialog Box then :

* shell:history
* shell:userprofiles
* shell:startup
* shell:profile
* shell:recent
* shell:templates
* shell:user pinned
* shell:downloads
* shell:programs
* shell:fonts
* shell:Screenshots
* shell:appdata
* shell:appsfolder



Reference:
* [Windows shell commands](https://windowsloop.com/windows-shell-commands/)


## Environment Variable List

* %homedrive%
* %systemdrive%
* %systemroot%
* %windir%
* %temp%
* %userprofile%
* %homepath%
* %appdata%

Reference:
* [Environment Variable](https://windowsloop.com/list-of-all-environment-variables-in-windows-10/)


## Simple (Built-in) App accessible fom RUN Dialog Box


* ms-clock:
* calculator:
* ms-settings:
* ms-availablenetworks:
* ms-paint:
* ms-photos:




Reference:
* [URI commands app windows 10](https://windowsloop.com/list-of-app-uri-commands-windows-10/)


## Very useful RUN Commands

* msconfig
* services.msc
* control
* netplwiz
* chrome
* taskmgr
* .
* ..
* \
* recent
* downloads
* documents
* favorites
* shutdown
* optionalfeatures
* https:://google.com
* calc
* winver
* dxdiag
* control printers


Reference:
* [Run commands list](https://allthings.how/windows-11-run-commands-list/)