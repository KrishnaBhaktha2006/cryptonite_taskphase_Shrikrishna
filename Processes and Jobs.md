# Processes and Jobs
## Code:
```bash
hacker@processes~listing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 09:07 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /ru
root           7       1  0 09:07 ?        00:00:00 /run/dojo/bin/sleep 6h
root          68       1  0 09:07 ?        00:00:00 /challenge/20940-run-18413
root          72      68  0 09:07 ?        00:00:00 sleep 6h
hacker        73       0  0 09:07 pts/0    00:00:00 /run/dojo/bin/ssh-entrypoint
hacker        93      73  0 09:13 pts/0    00:00:00 /run/dojo/bin/ssh-entrypoint
hacker       105      93  0 09:14 pts/0    00:00:00 ps -ef
hacker@processes~listing-processes:~$ /challenge/20940-run-18413
Yahaha, you found me! Here is your flag:
pwn.college{YFJijRRGY_GtVzME9Lp1sG52K_b.dhzM4QDL0kTN0czW}
```
## Learnings:
Damn i got to learn something new and this seems fun every module i move ahead!
## References:
