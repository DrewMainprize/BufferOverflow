# BufferOverflow

•Demonstrated a buffer overflow exploit on a vulnerable C program and exploited environment variables
to gain root access to the system.

buf_exploit.c
Contains the code to perform a buffer overflow exploit on a vulnerable linux system. The program writes past
the end of the buffer in the program and overwrites it with code to execute a root shell on the system.

env_exploit.c
Contains code to perform environment variable exploit on vulnerable system by creating new 'rm'
command and changing the path to look at the new command. The new command spawns a root shell 
instead of removing the given file.


