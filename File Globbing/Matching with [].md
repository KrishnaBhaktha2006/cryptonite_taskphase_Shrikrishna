# Matching with []
## Code:
```bash
hacker@globbing~matching-with-:~$ cd /challenge/files
hacker@globbing~matching-with-:/challenge/files$ file_[bash]
ssh-entrypoint: file_a: command not found
hacker@globbing~matching-with-:/challenge/files$ ls file_[bash]
file_a  file_b  file_h  file_s
hacker@globbing~matching-with-:/challenge/files$ /challenge/files file_[bash]
ssh-entrypoint: /challenge/files: Is a directory
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bash]
You got it! Here is your flag!
pwn.college{EZkJj8X8he0VsvtV6BfoAcqgsfo.dNjM4QDL0kTN0czW}
```
## Learnings:
it took some time but got it. its really nice way to learn stuff.
## References:
