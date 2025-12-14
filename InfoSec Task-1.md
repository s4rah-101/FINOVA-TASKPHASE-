# FINOVA-TASKPHASE-
## OVERTHEWIRE Challenge (Level 0-5)
### **Level 0**

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

### **Level 1**

C:\Users\Asus>ssh bandit1@bandit.labs.overthewire.org -p 2220

bandit1@bandit.labs.overthewire.org's password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

bandit1@bandit:~$ ls - 

bandit1@bandit:~$ cat ./-

263JGJPfgU6LtdEvgfWU1XP5yac29mFx

bandit1@bandit:~$ exit

logout

Connection to bandit.labs.overthewire.org closed.

### **Level 2**

C:\Users\Asus>ssh bandit2@bandit.labs.overthewire.org -p 2220
bandit2@bandit.labs.overthewire.org's password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
bandit2@bandit:~$ ls
--spaces in this filename--
bandit2@bandit:~$ cat -- "--spaces in this filename--"
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
bandit2@bandit:~$ exit
logout
Connection to bandit.labs.overthewire.org closed

### **Level 3**

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

### **Level 4**

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

### **Level 5**

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

bandit5@bandit:~/inhere$ find / -type f -size 1033c ! -executable
bandit5@bandit:~/inhere$ cat maybehere07/.file2
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

*That marks the end of the OVERTHEWIRE Wargame Challenge. It helped us know the basic linux commmands.*

