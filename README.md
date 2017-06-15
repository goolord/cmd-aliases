# cmd-aliases
Adds aliases to cmd.

INSTALLATION: 

Place autorun.bat and doskey.txt into %USERPROFILE% and run autorun.reg
Important: this will replace HKEY_CURRENT_USER\Software\Microsoft\Command Processor "AutoRun" which is used by some terminal emulators, I reccomend adding the string to your autoexec.bat before running.
Type alias help for help.


This script doesn't allow whitespace in directories, so here's an alias/script for getting the ms-dos 8 character version of the current directory

alias dirnws=%USERPROFILE%\dirnws.bat

@echo off
for %%I in (.) do echo %%~sI
