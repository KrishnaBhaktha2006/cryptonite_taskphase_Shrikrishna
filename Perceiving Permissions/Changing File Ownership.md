# Changing File ownership
## Code:
```bash
hacker@permissions~changing-file-ownership:~$ ls -l /flag
-r-------- 1 root root 58 Oct  8 10:49 /flag
hacker@permissions~changing-file-ownership:~$ chown hacker /flag
hacker@permissions~changing-file-ownership:~$ ls -l /flag
-r-------- 1 hacker root 58 Oct  8 10:49 /flag
hacker@permissions~changing-file-ownership:~$ cat /flag
pwn.college{sWetjGxy69XOJzF0alDJ3Uoe8X1.dFTM2QDL0kTN0czW}
```
## Learnings:
it was fun knowing that thats how people prevent others from touching files and how like hackers we can change users and access their files.
## References:
