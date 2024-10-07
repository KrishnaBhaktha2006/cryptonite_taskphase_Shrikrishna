# Grepping stored results
## Code:
```bash
hacker@piping~grepping-stored-results:~$ /challenge/run > /tmp/data.txt
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge will check that output is redirected to a specific file path : /tmp/data.txt
[INFO] - the challenge will output a reward file if all the tests pass : /challenge/.data.txt

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

[TEST] You should have redirected my stdout to a file called /tmp/data.txt. Checking...

[HINT] File descriptors are inherited from the parent, unless the FD_CLOEXEC is set by the parent on the file descriptor.
[HINT] For security reasons, some programs, such as python, do this by default in certain cases. Be careful if you are
[HINT] creating and trying to pass in FDs in python.

[PASS] The file at the other end of my stdout looks okay!
[PASS] Success! You have satisfied all execution requirements.
hacker@piping~grepping-stored-results:~$ grep flag /tmp/data.txt
[FLAG] Here is your flag:
flagstone's
flagstaff's
flagellation
flagon's
flagstones
flagella
camouflage
flagstaffs
persiflage's
unflagging
flagellums
camouflage's
flagrant
flagellum
flagstaff
flagging
conflagration's
flagon
flagpole
flagged
flagellates
flagellate
flagpole's
flagstone
flagellating
flagships
flag
flagellation's
camouflages
flagons
camouflaged
flag's
flagship's
conflagration
persiflage
flagship
flagellated
conflagrations
flagellum's
flagrantly
camouflaging
flagpoles
flags
hacker@piping~grepping-stored-results:~$ grep pwn /tmp/data.txt
pwning
pwn
pwned
pwn.college{4OENpdl3i7kXWCKdYUqr8Q4Uk9r.dhTM4QDL0kTN0czW}
pwns
```
## Learnings:
it was a simple question and i did exactly what they told to and i got it!
## References:
