# Changing Permissions
## Code:
```bash
hacker@permissions~changing-permissions:~$ ls -l /flag
-r-------- 1 root root 58 Oct  8 11:04 /flag
hacker@permissions~changing-permissions:~$ chmod o+r /flag
hacker@permissions~changing-permissions:~$ ls -l /flag
-r-----r-- 1 root root 58 Oct  8 11:04 /flag
hacker@permissions~changing-permissions:~$ cat /flag
pwn.college{YoBwB5X1fwDCdY_F5iFc0EUda5e.dNzNyUDL0kTN0czW}
```
## Learnings:
This was a good question i enjoyed it.
## References:
