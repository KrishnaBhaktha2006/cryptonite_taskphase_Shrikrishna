# Killing Processes
## Code:
```bash
hacker@processes~killing-processes:~$ ps -e | grep dont_run
hacker@processes~killing-processes:~$ ps -e | grep run
      7 ?        00:00:00 /run/dojo/bin/s
hacker@processes~killing-processes:~$ ps -ef | grep dont_run
hacker        73      71  0 09:23 ?        00:00:00 /challenge/dont_run
hacker        97      75  0 09:25 pts/0    00:00:00 grep --color=auto dont_run
hacker@processes~killing-processes:~$ kill 73
hacker@processes~killing-processes:~$ ps -ef | grep dont_run
hacker        99      75  0 09:26 pts/0    00:00:00 grep --color=auto dont_run
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{kYfAdc2qiV-43hIDEzjc7l0zQzC.dJDN4QDL0kTN0czW}
```
## Learnings:
It was a good question initially i had not got it because i was using only ps -e but then when i did ps -ef it worked after i understood that i got it!
## References:
