# Groups and files
## Code:
```bash
hacker@permissions~groups-and-files:~$ ls -l /flag
-r--r----- 1 root root 58 Oct  8 10:51 /flag
hacker@permissions~groups-and-files:~$ chgrp hacker /flag
hacker@permissions~groups-and-files:~$ ls -l /flag
-r--r----- 1 root hacker 58 Oct  8 10:51 /flag
hacker@permissions~groups-and-files:~$ cat /flag
pwn.college{oapYEWHr4pNlXSdb3khVv8rc9B_.dFzNyUDL0kTN0czW}
```
## Learnings:
Now i know how to change file wonership and even grp ownership!
## References:
