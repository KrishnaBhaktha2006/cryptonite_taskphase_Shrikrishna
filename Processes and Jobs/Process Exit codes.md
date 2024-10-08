# Process Exit codes
## Code:
```bash
hacker@processes~process-exit-codes:~$ /challenge/get-code
Exiting with an error code!
hacker@processes~process-exit-codes:~$ echo $?
27
hacker@processes~process-exit-codes:~$ /challenge/submit-code
You must run /challenge/submit-code with the exit code you retrieved from
/challenge/get-code as the first argument:

Usage: /challenge/submit-code [EXIT_CODE]
hacker@processes~process-exit-codes:~$ /challenge/submit-code 27
CORRECT! Here is your flag:
pwn.college{syTf4Hb9qyjzNiEvu_H-WAb85hN.dljN4UDL0kTN0czW}
```
## Learnings:
This was a bit good question i didnt get what it meant first but then i got it!!
## References:
