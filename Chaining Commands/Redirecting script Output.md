# Redirecting script Output
## Code:
```bash
hacker@chaining~redirecting-script-output:~$ touch x.sh
hacker@chaining~redirecting-script-output:~$ echo "/challenge/pwn" >> x.sh
echo "/challenge/college" >> x.sh
hacker@chaining~redirecting-script-output:~$ bash x.sh | /challenge/solve
Correct! Here is your flag:
pwn.college{QoDIzbe31-xrV5pNto6kS5OnHU4.dhTM5QDL0kTN0czW}
```
## Learnings:
It was easy after my friend helped me in the last module got to learn piping and this one together!
## References:
