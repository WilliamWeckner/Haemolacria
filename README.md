# Haemolacria
### malware!
**THIS REPO IS MALWARE !!! I AM NOT RESPONSIBLE FOR ANY DAMAGAE CAUSED BY IT. SEE LICENSE FOR MORE INFO**<br>
all things considered, this one isn't so bad. destructive if it starts on 03.01. where it prevents creation of threads by explorer, kills lsass and overwrites the MBR
otherwise launches a short, progressing GDI payload. operates within a DLL injected into explorer.exe and lsass.exe<br>
the injector (HaemolacriaLoader) only writes the DLL file to the disk, sets itself up to run at startup and injects the DLL into the above mentoned processes<br>
the payload (Haemolacria) is the actual payload which does all the fun stuff. it is also slightly less of a mess

oh and the code is the definition of a mess<br>

has been demonstrated in a video by Siam Alam: https://www.youtube.com/watch?v=YDUVo_4ybRU

for a more readable DLL injection implementation see my gist at https://gist.github.com/NullExceptionTSB/837fc5e76003974faaa0e11d9ede6d51

NOTE: tested only on Windows XP but most R&D was done on Windows 7 so it could possibly work there too
