# FINOVA-TASKPHASE-
## OVERTHEWIRE Challenge (Level 0-5)
### **Level 0**

Prompt:-
C:\Users\Asus>ssh bandit0@bandit.labs.overthewire.org -p 2220
bandit0@bandit.labs.overthewire.org's password: bandit0
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
Congratulations on your first steps into the bandit game!!
The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

bandit0@bandit:~$ exit
logout
Connection to bandit.labs.overthewire.org closed.

**Level 1**
C:\Users\Asus>ssh bandit1@bandit.labs.overthewire.org -p 2220
bandit1@bandit.labs.overthewire.org's password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
bandit1@bandit:~$ exit
logout
Connection to bandit.labs.overthewire.org closed.

**Level 2**
C:\Users\Asus>ssh bandit2@bandit.labs.overthewire.org -p 2220
bandit2@bandit.labs.overthewire.org's password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
bandit2@bandit:~$ ls
--spaces in this filename--
bandit2@bandit:~$ cat -- "--spaces in this filename--"
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
bandit2@bandit:~$ exit
logout
Connection to bandit.labs.overthewire.org closed

**Level 3**
C:\Users\Asus>ssh bandit3@bandit.labs.overthewire.org -p 2220
bandit3@bandit.labs.overthewire.org's password:MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
bandit3@bandit:~$ ls
inhere
bandit3@bandit:~$ cd inhere/
bandit3@bandit:~/inhere$ pwd
/home/bandit3/inhere
bandit3@bandit:~/inhere$ ls
bandit3@bandit:~/inhere$ ls -ahl
total 12K
drwxr-xr-x 2 root    root    4.0K Oct 14 09:26 .
drwxr-xr-x 3 root    root    4.0K Oct 14 09:26 ..
-rw-r----- 1 bandit4 bandit3   33 Oct 14 09:26 ...Hiding-From-You
bandit3@bandit:~/inhere$ cat ...Hiding-From-You
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
bandit3@bandit:~/inhere$ exit
logout
Connection to bandit.labs.overthewire.org closed.

**Level 4**
C:\Users\Asus>ssh bandit4@bandit.labs.overthewire.org -p 2220
bandit4@bandit.labs.overthewire.org's password:2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
bandit4@bandit:~$ ls
inhere
bandit4@bandit:~$ cd inhere/
bandit4@bandit:~/inhere$ ls
-file00  -file02  -file04  -file06  -file08
-file01  -file03  -file05  -file07  -file09
bandit4@bandit:~/inhere$ ls -ahl
total 48K
drwxr-xr-x 2 root    root    4.0K Oct 14 09:26 .
drwxr-xr-x 3 root    root    4.0K Oct 14 09:26 ..
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file00
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file01
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file02
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file03
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file04
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file05
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file06
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file07
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file08
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file09
bandit4@bandit:~/inhere$ file ./-file0*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@bandit:~/inhere$ cat ./-file07
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
bandit4@bandit:~/inhere$ exit
logout
Connection to bandit.labs.overthewire.org closed.

**Level 5**
C:\Users\Asus>ssh bandit5@bandit.labs.overthewire.org -p 2220
bandit5@bandit.labs.overthewire.org's password:4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
bandit5@bandit:~$ ls
inhere
bandit5@bandit:~$ cd inhere/
bandit5@bandit:~/inhere$ ls
maybehere00  maybehere04  maybehere08  maybehere12  maybehere16
maybehere01  maybehere05  maybehere09  maybehere13  maybehere17
maybehere02  maybehere06  maybehere10  maybehere14  maybehere18
maybehere03  maybehere07  maybehere11  maybehere15  maybehere19
bandit5@bandit:~/inhere$ find /-type f -size 1033c ! -executable
find: ‘/-type’: No such file or directory
find: ‘f’: No such file or directory
bandit5@bandit:~/inhere$ find / -type f -size 1033c ! -executable
find: ‘/proc/tty/driver’: Permission denied
find: ‘/proc/1/task/1/fd’: Permission denied
find: ‘/proc/1/task/1/fdinfo’: Permission denied
find: ‘/proc/1/task/1/ns’: Permission denied
find: ‘/proc/1/fd’: Permission denied
find: ‘/proc/1/map_files’: Permission denied
find: ‘/proc/1/fdinfo’: Permission denied
find: ‘/proc/1/ns’: Permission denied
find: ‘/proc/2/task/2/fd’: Permission denied
find: ‘/proc/2/task/2/fdinfo’: Permission denied
find: ‘/proc/2/task/2/ns’: Permission denied
find: ‘/proc/2/fd’: Permission denied
find: ‘/proc/2/map_files’: Permission denied
find: ‘/proc/2/fdinfo’: Permission denied
find: ‘/proc/2/ns’: Permission denied
find: ‘/proc/20/task/20/fdinfo/6’: No such file or directory
find: ‘/proc/20/fdinfo/5’: No such file or directory
find: ‘/lost+found’: Permission denied
find: ‘/var/tmp’: Permission denied
find: ‘/var/spool/bandit24’: Permission denied
find: ‘/var/spool/cron/crontabs’: Permission denied
find: ‘/var/spool/rsyslog’: Permission denied
find: ‘/var/lib/update-notifier/package-data-downloads/partial’: Permission denied
find: ‘/var/lib/apt/lists/partial’: Permission denied
find: ‘/var/lib/polkit-1’: Permission denied
find: ‘/var/lib/chrony’: Permission denied
find: ‘/var/lib/udisks2’: Permission denied
find: ‘/var/lib/snapd/cookie’: Permission denied
find: ‘/var/lib/snapd/void’: Permission denied
find: ‘/var/lib/private’: Permission denied
find: ‘/var/lib/ubuntu-advantage/apt-esm/var/lib/apt/lists/partial’: Permission denied
find: ‘/var/lib/amazon’: Permission denied
find: ‘/var/crash’: Permission denied
find: ‘/var/cache/apt/archives/partial’: Permission denied
find: ‘/var/cache/pollinate’: Permission denied
find: ‘/var/cache/private’: Permission denied
find: ‘/var/cache/apparmor/208b6430.0’: Permission denied
find: ‘/var/cache/apparmor/0fb44ac6.0’: Permission denied
find: ‘/var/cache/ldconfig’: Permission denied
find: ‘/var/log’: Permission denied
find: ‘/sys/kernel/tracing/osnoise’: Permission denied
find: ‘/sys/kernel/tracing/hwlat_detector’: Permission denied
find: ‘/sys/kernel/tracing/instances’: Permission denied
find: ‘/sys/kernel/tracing/trace_stat’: Permission denied
find: ‘/sys/kernel/tracing/per_cpu’: Permission denied
find: ‘/sys/kernel/tracing/options’: Permission denied
find: ‘/sys/kernel/tracing/rv’: Permission denied
find: ‘/sys/kernel/debug’: Permission denied
find: ‘/sys/fs/pstore’: Permission denied
find: ‘/sys/fs/bpf’: Permission denied
find: ‘/drifter/drifter14_src/axTLS’: Permission denied
find: ‘/tmp’: Permission denied
find: ‘/snap’: Permission denied
find: ‘/home/bandit31-git’: Permission denied
find: ‘/home/leviathan4/.trash’: Permission denied
find: ‘/home/drifter8/chroot’: Permission denied
find: ‘/home/bandit29-git’: Permission denied
find: ‘/home/bandit27-git’: Permission denied
find: ‘/home/drifter6/data’: Permission denied
/home/bandit5/inhere/maybehere07/.file2
find: ‘/home/bandit28-git’: Permission denied
find: ‘/home/leviathan0/.backup’: Permission denied
find: ‘/home/ubuntu’: Permission denied
find: ‘/home/bandit30-git’: Permission denied
find: ‘/boot/efi’: Permission denied
find: ‘/boot/lost+found’: Permission denied
/usr/share/man/man1/git-mktree.1.gz
/usr/share/terminfo/x/xnuppc-m-f2
/usr/share/terminfo/x/xtalk
/usr/src/linux-aws-6.14-headers-6.14.0-1014/tools/power/acpi/tools/acpidump/Makefile
/usr/src/linux-aws-6.14-headers-6.14.0-1014/drivers/gpu/drm/solomon/Kconfig
find: ‘/run/pam_pidns’: Permission denied
find: ‘/run/udisks2’: Permission denied
find: ‘/run/chrony’: Permission denied
find: ‘/run/user/11010’: Permission denied
find: ‘/run/user/12001’: Permission denied
find: ‘/run/user/11011’: Permission denied
find: ‘/run/user/11004’: Permission denied
find: ‘/run/user/11003’: Permission denied
find: ‘/run/user/11025’: Permission denied
find: ‘/run/user/12006’: Permission denied
find: ‘/run/user/11023’: Permission denied
find: ‘/run/user/11014’: Permission denied
find: ‘/run/user/11019’: Permission denied
find: ‘/run/user/11008’: Permission denied
find: ‘/run/user/11005/systemd/inaccessible/dir’: Permission denied
find: ‘/run/user/11024’: Permission denied
find: ‘/run/user/11009’: Permission denied
find: ‘/run/user/11013’: Permission denied
find: ‘/run/user/11007’: Permission denied
find: ‘/run/user/11016’: Permission denied
find: ‘/run/user/11002’: Permission denied
find: ‘/run/user/11020’: Permission denied
find: ‘/run/user/11000’: Permission denied
find: ‘/run/user/11001’: Permission denied
find: ‘/run/user/11006’: Permission denied
find: ‘/run/user/11012’: Permission denied
find: ‘/run/sudo’: Permission denied
find: ‘/run/screen/S-bandit24’: Permission denied
find: ‘/run/screen/S-bandit25’: Permission denied
find: ‘/run/screen/S-bandit23’: Permission denied
find: ‘/run/screen/S-bandit21’: Permission denied
find: ‘/run/screen/S-bandit18’: Permission denied
find: ‘/run/screen/S-bandit19’: Permission denied
find: ‘/run/screen/S-bandit16’: Permission denied
find: ‘/run/screen/S-bandit20’: Permission denied
find: ‘/run/multipath’: Permission denied
find: ‘/run/cryptsetup’: Permission denied
find: ‘/run/log/journal/ec2a9205573e9719662ab1a1baf96c71’: Permission denied
find: ‘/run/lvm’: Permission denied
find: ‘/run/systemd/propagate/fwupd.service’: Permission denied
find: ‘/run/systemd/propagate/ModemManager.service’: Permission denied
find: ‘/run/systemd/propagate/polkit.service’: Permission denied
find: ‘/run/systemd/propagate/chrony.service’: Permission denied
find: ‘/run/systemd/propagate/systemd-logind.service’: Permission denied
find: ‘/run/systemd/propagate/irqbalance.service’: Permission denied
find: ‘/run/systemd/propagate/systemd-networkd.service’: Permission denied
find: ‘/run/systemd/propagate/systemd-resolved.service’: Permission denied
find: ‘/run/systemd/propagate/systemd-udevd.service’: Permission denied
find: ‘/run/systemd/inaccessible/dir’: Permission denied
find: ‘/run/lock/lvm’: Permission denied
find: ‘/etc/multipath’: Permission denied
find: ‘/etc/stunnel’: Permission denied
find: ‘/etc/credstore.encrypted’: Permission denied
find: ‘/etc/sudoers.d’: Permission denied
find: ‘/etc/xinetd.d’: Permission denied
find: ‘/etc/polkit-1/rules.d’: Permission denied
find: ‘/etc/credstore’: Permission denied
find: ‘/etc/ssl/private’: Permission denied
find: ‘/root’: Permission denied
/opt/radare2/subprojects/sdb/test/fuzz/minimized_second/out/id_000039.out
/opt/pwndbg/.venv/lib/python3.12/site-packages/jedi/third_party/django-stubs/django-stubs/conf/urls/__init__.pyi
/opt/pwndbg/.venv/lib/python3.12/site-packages/ziglang/lib/libc/include/any-linux-any/linux/hash_info.h
/opt/pwndbg/.venv/lib/python3.12/site-packages/ziglang/lib/libcxx/include/experimental/utility
find: ‘/manpage/manpage3-pw’: Permission denied
find: ‘/dev/mqueue’: Permission denied
find: ‘/dev/shm’: Permission denied
bandit5@bandit:~/inhere$ find / -type f -size 1033c ! -executable 2>/dev/null
/home/bandit5/inhere/maybehere07/.file2
/usr/share/man/man1/git-mktree.1.gz
/usr/share/terminfo/x/xnuppc-m-f2
/usr/share/terminfo/x/xtalk
/usr/src/linux-aws-6.14-headers-6.14.0-1014/tools/power/acpi/tools/acpidump/Makefile
/usr/src/linux-aws-6.14-headers-6.14.0-1014/drivers/gpu/drm/solomon/Kconfig
/opt/radare2/subprojects/sdb/test/fuzz/minimized_second/out/id_000039.out
/opt/pwndbg/.venv/lib/python3.12/site-packages/jedi/third_party/django-stubs/django-stubs/conf/urls/__init__.pyi
/opt/pwndbg/.venv/lib/python3.12/site-packages/ziglang/lib/libc/include/any-linux-any/linux/hash_info.h
/opt/pwndbg/.venv/lib/python3.12/site-packages/ziglang/lib/libcxx/include/experimental/utility
bandit5@bandit:~/inhere$ cat maybehere07/.file2
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

*That marks the end of the OVERTHEWIRE Wargame Challenge. It helped us know the basic linux commmands.*

