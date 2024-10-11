# Executable shell scripts
## Code:
```bash
hacker@chaining~executable-shell-scripts:~$ touch solve.sh
hacker@chaining~executable-shell-scripts:~$ echo "/challenge/solve" >> solve.sh
hacker@chaining~executable-shell-scripts:~$ ls -l solve.sh
-rw-r--r-- 1 hacker hacker 17 Oct 11 11:43 solve.sh
hacker@chaining~executable-shell-scripts:~$ chmod +x solve.sh
hacker@chaining~executable-shell-scripts:~$ ls -l solve.sh
-rwxr-xr-x 1 hacker hacker 17 Oct 11 11:43 solve.sh
hacker@chaining~executable-shell-scripts:~$ cat solve.sh
/challenge/solve
hacker@chaining~executable-shell-scripts:~$ bash solve.sh
You must make a shellscript in your home directory that will launch
/challenge/solve, make it executable, and invoke it without explicitly
specifying 'bash'!
hacker@chaining~executable-shell-scripts:~$ ./solve.sh
Congratulations on your shell script execution! Your flag:
pwn.college{43RJiOP2JcaMuxL5xDdp3EiZT6q.dRzNyUDL0kTN0czW}
```
## Learnings:
It was actually fun and tests stuff from different modules.
## References:
