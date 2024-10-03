# Help for Builtins
## Code:
```bash
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "wdCoMdq6".
hacker@man~help-for-builtins:~$ /challenge/challenge --wdCoMdq6
ssh-entrypoint: /challenge/challenge: No such file or directory
hacker@man~help-for-builtins:~$ challenge --fortune --version --secret wdCoMdq6
He who attacks the fundamentals of the American broadcasting industry
attacks democracy itself.
                -- William S. Paley, chairman of CBS
hacker@man~help-for-builtins:~$ challenge --secret wdCoMdq6
Correct! Here is your flag!
pwn.college{wdCoMdq6MyZ2LN3jtUPSJC0kyzB.dRTM5QDL0kTN0czW}
```
## Learnings:
i got it after trying some wrong codes as u can see in code section
## References:
