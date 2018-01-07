# libserialport-lw
persional repo from official website:http://sigrok.org/wiki/Libserialport. Make it stable in product running on win32 &amp; linux(arm/x86).

1. fix sp_nonblocking_write on win32.
2. fix sp_close on win32. call CancelIo to release pending event before close file.
