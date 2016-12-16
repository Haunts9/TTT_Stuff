Hello this is the help for GmadConvGUI.

Now what this program does is converts gma files in to files/folders.
The source code is written in C# and is based on the C++ command line program available
on this thread http://www.facepunch.com/showthread.php?t=1173875. 
So all credit for showing me how to read the file goes to SiPlus.



==Using in a batch file==

This program is not just for GUI, you can use it to automatically convert entire folders
simply by adding a start argument to it, using either a batch file or a shortcut.

GmadConvGUI.exe [FolderPath] [-delete_gma or FolderToPutGMA]

if -delete_gma is specified it will delete GMA files that it converts.
or if FolderToPutGMA is specified it will move the GMA files to that folder.
Please note that you should specifiy the FULL PATH, or it will be relative to the .exe file

The program will then close after 10 seconds, you can hold down escape to cancel closing