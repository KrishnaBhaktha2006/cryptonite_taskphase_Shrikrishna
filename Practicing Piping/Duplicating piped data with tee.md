# Duplicating piped data with tee
## Code:
```bash
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee out | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat out
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "EkXU85uR"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --EkXU85uR | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret [EkXU85uR] | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret [EkXU85uR]
Processing...
You must pipe the output of /challenge/pwn into /challenge/college (or 'tee'
for debugging).
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret [EkXU85uR] | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret EkXU85uR | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{EkXU85uRDmBVkOZtz15Wg1sjdM2.dFjM5QDL0kTN0czW}
```
## Learnings:
This was a bit confusing and little too much to understand because there were multiple pipes(|) ANYWAYS got it 
## References:
