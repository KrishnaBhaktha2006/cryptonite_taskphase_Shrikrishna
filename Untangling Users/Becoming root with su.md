# Becoming root with su
## Code:
```bash
hacker@users~becoming-root-with-su:~$ chmod u+s /challenge/getroot
chmod: cannot access '/challenge/getroot': No such file or directory
hacker@users~becoming-root-with-su:~$ ls -l /challenge/getroot
ls: cannot access '/challenge/getroot': No such file or directory
hacker@users~becoming-root-with-su:~$ ls -l /challenge/run
-rwsr-xr-x 1 root root 43 Jul 17 17:18 /challenge/run
hacker@users~becoming-root-with-su:~$ chmod u+s /challenge/run
chmod: changing permissions of '/challenge/run': Operation not permitted
hacker@users~becoming-root-with-su:~$ su
Password:
root@users~becoming-root-with-su:/home/hacker# cat /flag
pwn.college{EAu6vkEupQtNd6iiw_xgWdnf5Fy.dVTN0UDL0kTN0czW}
```
## Learnings:
I understood that even been the root user u cannot change stuff unless u know the password
## References:
