# Split-piping stderr and stdout
## Code:
```bash
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > >( /challenge/planet ) 2>( /challenge/the )
You must redirect my standard error into '/challenge/the'!
Are you sure you're properly redirecting /challenge/hack's standard error into
'/challenge/the'?
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > >( /challenge/planet ) 2> >( /challenge/the )
Congratulations, you have learned a redirection technique that even experts
struggle with! Here is your flag:
pwn.college{UEQVfJeSjLGUU1tz8VEh7qokLMt.dFDNwYDL0kTN0czW}
```
## Learnings:
It was a beautiful question though piping is not completely clear to me but still it was noice!!
## References:
