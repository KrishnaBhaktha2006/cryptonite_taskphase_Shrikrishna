# making directories
## Code:
```bash
hacker@commands~making-directories:~$ cd /tmp
hacker@commands~making-directories:/tmp$ mkdir pwn
hacker@commands~making-directories:/tmp$ cd pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ cd college
ssh-entrypoint: cd: college: Not a directory
hacker@commands~making-directories:/tmp/pwn$ ls
college
hacker@commands~making-directories:/tmp/pwn$ ls /tmp/pwn/college
/tmp/pwn/college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{kuJFpnCXmp1PF8QcYvsLs0Ucz3S.dFzM4QDL0kTN0czW}
```
## Learnings:
i did a mistake on checking the question again i was able to do it!
## References:
