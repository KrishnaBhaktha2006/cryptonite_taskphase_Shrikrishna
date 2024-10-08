# Suspending Processes
## Code:
```bash
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root          84      66  0 09:33 pts/0    00:00:00 bash /challenge/run
root          91      66  0 09:33 pts/0    00:00:00 bash /challenge/run
root          93      91  0 09:33 pts/0    00:00:00 ps -f

Yay, I found another version of me! Here is the flag:
pwn.college{YSz246McgwTCjWwPMZl0_Vwku3M.dVDN4QDL0kTN0czW}
```
## Learnings:
this is similar to the one before so i got it
## References:
