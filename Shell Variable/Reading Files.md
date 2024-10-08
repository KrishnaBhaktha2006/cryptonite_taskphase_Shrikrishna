# Reading Files
## Code:
```bash
hacker@variables~reading-files:~$ echo /challenge/read_me > PWN
hacker@variables~reading-files:~$ echo $PWN

hacker@variables~reading-files:~$ PWN=$(cat some_file)
You appear to be invoking a subshell. This could be, for example, because you
are doing something like `PWN=$(echo COLLEGE)`. Instead, you must use `read` to
set the PWN variable.
hacker@variables~reading-files:~$ read PWN < some_file
You invoked 'read', but it looks like you didn't redirect the
/challenge/read_me file to it!
ssh-entrypoint: some_file: No such file or directory
hacker@variables~reading-files:~$ read PWN < /challenge/read_me
You've set the PWN variable properly! As promised, here is the flag:
pwn.college{88dccPZnFbQHRsiJLCuMHNZGDUh.dBjM4QDL0kTN0czW}
```
## Learnings:
It was a good question i enjoyed it it took some time but got it!
## References:
