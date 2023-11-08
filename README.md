# Shell-Icons-307
Change all default folder icons in Windows 10/11 to icon 307

Using the tutorial :
https://www.winhelponline.com/blog/change-open-folder-icon-explorer-and-registry-editor/

Or my tutorial here:

download the .dll file from THIS REPOSITORY and put the s_foldericon file at C:\s_foldericon

Otherwise , make a new registry key at HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer 
Call "Shell Icons"

So you will be at HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Shell Icons

And create two new strings, 3, and 4, and have their values point the s_foldericon.dll

Type in the path inside the value data box.

Or replace with a cusotom icon.ico ... *Will only work on some versions of windows 10 as an icon file*

Refresh (And restart) and you're done.
