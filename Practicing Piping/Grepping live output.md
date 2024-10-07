# Grepping live output
## Code:
```bash
hacker@piping~grepping-live-output:~$ echo /challenge/run | grep pwn
hacker@piping~grepping-live-output:~$ /challenge/run | grep pwn
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge checks for a specific process at the other end of stdout : grep
[INFO] - the challenge will output a reward file if all the tests pass : /challenge/.data.txt

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

[TEST] You should have redirected my stdout to another process. Checking...
[TEST] Performing checks on that process!

[INFO] The process' executable is /nix/store/xpq4yhadyhazkcsggmqd7rsgvxb3kjy4-gnugrep-3.11/bin/grep.
[INFO] This might be different than expected because of symbolic links (for example, from /usr/bin/python to /usr/bin/python3 to /usr/bin/python3.8).
[INFO] To pass the checks, the executable must be grep.

[PASS] You have passed the checks on the process on the other end of my stdout!
[PASS] Success! You have satisfied all execution requirements.
pwned
pwns
pwn
pwn.college{kxadj5cdkHOjhSDmzOv4IQYQS8R.dlTM4QDL0kTN0czW}
pwning
```
## Learnings:
it was difficult to understand the question first then i used chat gpt to understand the concept well and then i got it!
## References:
