# Redirecting output
## Code:
```bash
hacker@piping~redirecting-output:~$ PWN > COLLEGE
ssh-entrypoint: PWN: command not found
You have created the COLLEGE file, but you didn't write the correct value to
it. Make sure to write PWN to the COLLEGE file.
hacker@piping~redirecting-output:~$ echo PWN > COLLEGE
Correct! You successfully redirected 'PWN' to the file 'COLLEGE'! Here is your
flag:
pwn.college{grZkgwIwpxyoMyfvzY8BCbvYr8M.dRjN1QDL0kTN0czW}
```
## Learnings:
It took me two tries to get it! It was a good question
## References:
