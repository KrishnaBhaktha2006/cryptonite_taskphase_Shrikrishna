# Reading Manuals
## Code:
```bash
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                  Challenge Commands                  CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --oxvoxi NUM
              print the flag if NUM is 359

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The  repository for this dojo: <https://github.com/pwncollege/linux-lu‐
       minarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                        May 2024                       CHALLENGE(1)
hacker@man~reading-manuals:~$ cd /challenge/pwn.college
ssh-entrypoint: cd: /challenge/pwn.college: No such file or directory
hacker@man~reading-manuals:~$ man pwn.college
No manual entry for pwn.college
hacker@man~reading-manuals:~$ /challenge/pwn.college
ssh-entrypoint: /challenge/pwn.college: No such file or directory
hacker@man~reading-manuals:~$ /challenge/challenge - print the flag!
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                 Challenge Commands                CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --oxvoxi NUM
              print the flag if NUM is 359

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The  repository for this dojo: <https://github.com/pwncollege/linux-
       luminarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                       May 2024                     CHALLENGE(1)
hacker@man~reading-manuals:~$ /challenge/challenge --oxvoxi 359
Correct usage! Your flag: pwn.college{oxv3oxiGm5lsIKNbAsWSbtY9-70.dRTM4QDL0kTN0czW}
```
## Learnings:
It worked after a long time i read it multiple times but i didnt get idea but then after using chat gpt i got an idea then i did it!
## References:
chat gpt
