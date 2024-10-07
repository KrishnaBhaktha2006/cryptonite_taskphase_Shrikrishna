# Writing to multiple programs
## Code:
```bash
hacker@piping~writing-to-multiple-programs:~$ echo /challenge/hack | /challenge/the
echo /challenge/hack | /challenge/planet
Are you sure you're properly redirecting input into '/challenge/the'?
Are you sure you're properly redirecting input into '/challenge/planet'?
hacker@piping~writing-to-multiple-programs:~$ echo /challenge/hack | tee /challenge/the > /challenge/planet
ssh-entrypoint: /challenge/planet: Permission denied
hacker@piping~writing-to-multiple-programs:~$ echo /challenge/hack | tee /challenge/the
WARNING: it looks like you passed the path /challenge/the, instead of the
substituted process, to tee. This will cause tee to try to write to the
/challenge/the file, rather than have the shell launch the /challenge/the
command and redirect tee's output to it.
/usr/bin/tee: /challenge/the: Permission denied
/challenge/hack
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack > >(/challenge/the|/challenge/planet)
Are you sure you're properly redirecting input into '/challenge/planet'?
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | tee >/challenge/the >/challenge/planet
ssh-entrypoint: /challenge/the: Permission denied
Congratulations, you have duplicated data into the input of two programs! Here
is your flag:
pwn.college{IPPeVL0aFgU2CJKjs37A04G-ijq.dBDO0UDL0kTN0czW}
```
## Learnings:
Initially i was doing it wrong but after taking a bit help from chat gpt i got it!
## References:
Chat gpt
