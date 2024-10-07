# Printing Exported Variables
## Code:
```bash
hacker@variables~printing-exported-variables:~$ env pwn
usage: pwn [-h]
           {asm,checksec,constgrep,cyclic,debug,disasm,disablenx,elfdiff,elfpatch,errno,hex,libcdb,phd,pwnstrip,scramble,shellcraft,template,unhex,update,version}
           ...
hacker@variables~printing-exported-variables:~$ pwn -h
usage: pwn [-h]
           {asm,checksec,constgrep,cyclic,debug,disasm,disablenx,elfdiff,elfpatch,errno,hex,libcdb,phd,pwnstrip,scramble,shellcraft,template,unhex,update,version}
           ...

Pwntools Command-line Interface

positional arguments:
  {asm,checksec,constgrep,cyclic,debug,disasm,disablenx,elfdiff,elfpatch,errno,hex,libcdb,phd,pwnstrip,scramble,shellcraft,template,unhex,update,version}
    asm                 Assemble shellcode into bytes
    checksec            Check binary security settings
    constgrep           Looking up constants from header files. Example: constgrep -c freebsd -m ^PROT_ '3 + 4'
    cyclic              Cyclic pattern creator/finder
    debug               Debug a binary in GDB
    disasm              Disassemble bytes into text format
    disablenx           Disable NX for an ELF binary
    elfdiff             Compare two ELF files
    elfpatch            Patch an ELF file
    errno               Prints out error messages
    hex                 Hex-encodes data provided on the command line or stdin
    libcdb              Print various information about a libc binary
    phd                 Pretty hex dump
    pwnstrip            Strip binaries for CTF usage
    scramble            Shellcode encoder
    shellcraft          Microwave shellcode -- Easy, fast and delicious
    template            Generate an exploit template
    unhex               Decodes hex-encoded data provided on the command line or via stdin.
    update              Check for pwntools updates
    version             Pwntools version

options:
  -h, --help            show this help message and exit
hacker@variables~printing-exported-variables:~$ env flag
env: ‘flag’: No such file or directory
hacker@variables~printing-exported-variables:~$ env pwn
usage: pwn [-h]
           {asm,checksec,constgrep,cyclic,debug,disasm,disablenx,elfdiff,elfpatch,errno,hex,libcdb,phd,pwnstrip,scramble,shellcraft,template,unhex,update,version}
           ...
hacker@variables~printing-exported-variables:~$ cat pwnstrip
cat: pwnstrip: No such file or directory
hacker@variables~printing-exported-variables:~$ env pwnstrip
usage: pwn pwnstrip [-h] [-b] [-p FUNCTION] [-o OUTPUT] file
pwn pwnstrip: error: the following arguments are required: file
hacker@variables~printing-exported-variables:~$ pwn pwnstrip -o
usage: pwn pwnstrip [-h] [-b] [-p FUNCTION] [-o OUTPUT] file
pwn pwnstrip: error: argument -o/--output: expected one argument
hacker@variables~printing-exported-variables:~$ env | grep pwn
FLAG=pwn.college{4JZYd_mlijWVZgJyvCerxsnj9Ja.dhTN1QDL0kTN0czW}
```
## Learnings:
this was a good question but i feel they should have mentioned the syntax to use env so i didnt get for many tries as u can see in the code section then when i used chat gpt i got it!
## References:
chat gpt
## References:
