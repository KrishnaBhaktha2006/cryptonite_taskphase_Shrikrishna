# Redirecting input
## Code:
```bash
hacker@piping~redirecting-input:~$ COLLEGE > PWN
ssh-entrypoint: COLLEGE: command not found
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ rev < PWN
EGELLOC
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{E6W5n5FkzYiBtO669GnC-dZJpKW.dBzN1QDL0kTN0czW}
```
## Learnings:
It was a good question and i did a few mistakes initially but then got it right eventually!
## References:
