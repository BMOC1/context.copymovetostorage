# context.copymovetostorage

Idea originated from AbelTesfaye /context.copytostorage.  Didn't work in latest Kodi.  With AbelTesfay original code and the assistance of AI and my coding knowledge, i upgraded/rewrote to handle the latest KODI as of March of 2026.  This is designed to copy/move files from one SMB path to another, and then update the library for the destination folder.

I use this because i have a path that is outside of the normal library.  Where the files originate from.  I wanted to be able to copy them to my smb paths where the kodi library scan within KODI.  After the copy is succesful, it will give you a query as to whether you wish to delete the source.  

Zip up the files/folders and import as a .zip addon package.
Once installed, the option to copy/move appears in the context menu of video files.

I am not going to bother with updating this so its published for KODI.  But, i did want to fork this and make it public so others can benifit from my initial work.

The copying is moved out of PHP and into the KODI xbmcvfs.  You get a progress update.
