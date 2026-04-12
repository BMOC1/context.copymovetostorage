# context.copytostorage

This is a KODI context menu plugin to copy files from one Local/SMB path to another.

Idea originated from AbelTesfaye /context.copytostorage.  Didn't work in latest Kodi.  With AbelTesfay original code and the assistance of AI and my coding knowledge, i rewrote to handle the latest KODI as of March of 2026.  This is designed to copy files from one Local/SMB path to another, and after successful copy give the option to delete the source.  It then updates the library for the new copied file (movie/etc)

I use this because i have a path that is outside of the normal library.  Where the files originate from.  I wanted to be able to copy them to my smb paths where the kodi library paths are active.  After the copy is succesful, it will give you a query as to whether you wish to delete the source.  The movie is then updated in the kodi library movie database and available for watching.

This can be used for any files, music etc, but my application was for movies.

Zip up the files/folders and import as a .zip addon package.
Once installed, the option to copy/move appears in the context menu of video files. Once you choose the copy/move context item, you will be prompted to select a destination path.  It will then start the transfer process giving you transfer progress .

I am not going to bother with updating this so its published for KODI.  But, i did want to fork this and make it public so others can benifit from my work.

Technical :
The copying functionality was moved out of PHP and into the KODI xbmcvfs.  
You get a progress updates.
Option to delete source after succesful copy.
