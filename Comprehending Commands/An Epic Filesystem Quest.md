# An Epic Filesystem Quest
## Code:
```bash
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
WHISPER  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin      challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat WHISPER
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/include/dt-bindings/leds

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ cd /opt/linux/linux-5.4/include/dt-bindings/leds
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/dt-bindings/leds$ ls
LEAD  common.h  leds-netxbig.h  leds-ns2.h  leds-pca9532.h  leds-pca955x.h
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/dt-bindings/leds$ cat LEAD
Tubular find!
The next clue is in: /opt/angr-management/_internal/pypcode/processors/SuperH/data/languages

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/dt-bindings/leds$ cd /opt/angr-management/_internal/pypcode/processors/SuperH/data/languages
hacker@commands~an-epic-filesystem-quest:/opt/angr-management/_internal/pypcode/processors/SuperH/data/languages$ ls -a
.   .BLUEPRINT  sh-1.slaspec  sh-2.slaspec  sh-2a.slaspec  superh.ldefs  superh.sinc
..  sh-1.sla    sh-2.sla      sh-2a.sla     superh.cspec   superh.pspec  superh2a.cspec
hacker@commands~an-epic-filesystem-quest:/opt/angr-management/_internal/pypcode/processors/SuperH/data/languages$ cat .BLUEPRINT
Lucky listing!
The next clue is in: /opt/linux/linux-5.4/tools/testing/selftests/memfd
hacker@commands~an-epic-filesystem-quest:/opt/angr-management/_internal/pypcode/processors/SuperH/data/languages$ cd /opt/linux/linux-5.4/tools/testing/selftests/memfd
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ ls
MEMO      common.c  config      fuse_test.c   run_fuse_test.sh
Makefile  common.h  fuse_mnt.c  memfd_test.c  run_hugetlbfs_test.sh
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ cat MEMO
Lucky listing!
The next clue is in: /opt/linux/linux-5.4/include/config/hvc

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ ls /opt/linux/linux-5.4/include/config/hvc/TRACE-TRAPPED
/opt/linux/linux-5.4/include/config/hvc/TRACE-TRAPPED
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ ls -a /opt/linux/linux-5.4/include/config/hvc/TRACE-TRAPPED
/opt/linux/linux-5.4/include/config/hvc/TRACE-TRAPPED
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ cp /opt/linux/linux-5.4/include/config/hvc/TRACE-TRAPPED /tmp/TRACE-TRAPPED
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ cat /temp/TRACE-TRAPPED
cat: /temp/TRACE-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ cat /tmp/TRACE-TRAPPED
Yahaha, you found me!
The next clue is in: /opt/linux/linux-5.4/include/config/strict/kernel

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/testing/selftests/memfd$ cd /opt/linux/linux-5.4/include/config/strict/kernel
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/strict/kernel$ ls -a
.  ..  .BRIEF  rwx.h
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/strict/kernel$ cat .BRIEF
Lucky listing!
The next clue is in: /opt/linux/linux-5.4/scripts/genksyms

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/strict/kernel$ cd /opt/linux/linux-5.4/scripts/genksyms
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/scripts/genksyms$ ls
Makefile  TEASER  genksyms.c  genksyms.h  keywords.c  lex.l  parse.y
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/scripts/genksyms$ cat TEASER
Congratulations, you found the clue!
The next clue is in: /usr/local/lib/python3.8/dist-packages/future/moves/urllib

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/scripts/genksyms$ ls /usr/local/lib/python3.8/dist-packages/future/moves/urllib
INSIGHT-TRAPPED  __init__.py  __pycache__  error.py  parse.py  request.py  response.py  robotparser.py
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/scripts/genksyms$ cp /usr/local/lib/python3.8/dist-packages/future/moves/urllib /tmp/INSIGHT-TRAPPED
cp: -r not specified; omitting directory '/usr/local/lib/python3.8/dist-packages/future/moves/urllib'
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/scripts/genksyms$ cp /usr/local/lib/python3.8/dist-packages/future/moves/urllib/INSIGHT-TRAPPED /tmp/INSIGHT-TRAPPED
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/scripts/genksyms$ cat /tmp/INSIGHT-TRAPPED
Tubular find!
The next clue is in: /opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qlcnic
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/scripts/genksyms$ cd /opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qlcnic
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qlcnic$ ls
INFO              qlcnic_83xx_hw.h    qlcnic_dcb.c      qlcnic_hw.c    qlcnic_main.c          qlcnic_sriov_pf.c
Makefile          qlcnic_83xx_init.c  qlcnic_dcb.h      qlcnic_hw.h    qlcnic_minidump.c      qlcnic_sysfs.c
qlcnic.h          qlcnic_83xx_vnic.c  qlcnic_ethtool.c  qlcnic_init.c  qlcnic_sriov.h
qlcnic_83xx_hw.c  qlcnic_ctx.c        qlcnic_hdr.h      qlcnic_io.c    qlcnic_sriov_common.c
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qlcnic$ cat INFO
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{YiKy1LtaFtSdofCQHxeT2Zs_4WR.dljM4QDL0kTN0czW}
```
## Learnings:
this was a beautiful question!!!!! i loved the whole process of the question but i was stuck at one place of how to read read file without cding it that i learnt from chat gpt that u can use cp command or else i did it on my own.
## References:
learnt how to use cp command from chat gpt
