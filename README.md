# lab2
1.List the available shells in your system.
ubuntu@giving-chipmunk:~$ cat /etc/shells
# /etc/shells: valid login shells
/bin/sh
/usr/bin/sh
/bin/bash
/usr/bin/bash
/bin/rbash
/usr/bin/rbash
/usr/bin/dash
/usr/bin/screen
/usr/bin/tmux

2.List all of the environment variables in your current shell.
ubuntu@giving-chipmunk:~$ printenv
SHELL=/bin/bash
PWD=/home/ubuntu
LOGNAME=ubuntu
XDG_SESSION_TYPE=tty
HOME=/home/ubuntu
LANG=C.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=00:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.avif=01;35:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.webp=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:*~=00;90:*#=00;90:*.bak=00;90:*.crdownload=00;90:*.dpkg-dist=00;90:*.dpkg-new=00;90:*.dpkg-old=00;90:*.dpkg-tmp=00;90:*.old=00;90:*.orig=00;90:*.part=00;90:*.rej=00;90:*.rpmnew=00;90:*.rpmorig=00;90:*.rpmsave=00;90:*.swp=00;90:*.tmp=00;90:*.ucf-dist=00;90:*.ucf-new=00;90:*.ucf-old=00;90:
SSH_CONNECTION=192.168.64.1 50169 192.168.64.7 22
LESSCLOSE=/usr/bin/lesspipe %s %s
XDG_SESSION_CLASS=user
TERM=xterm-256color
LESSOPEN=| /usr/bin/lesspipe %s
USER=ubuntu
SHLVL=1
XDG_SESSION_ID=3
XDG_RUNTIME_DIR=/run/user/1000
SSH_CLIENT=192.168.64.1 50169 22
XDG_DATA_DIRS=/usr/local/share:/usr/share:/var/lib/snapd/desktop
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/1000/bus
SSH_TTY=/dev/pts/0
_=/usr/bin/printenv

3.Display your current shell name.
ubuntu@giving-chipmunk:~$ echo $SHELL
/bin/bash

4.List all of the environment variables for the Bash shell.
ubuntu@giving-chipmunk:~$ env
SHELL=/bin/bash
PWD=/home/ubuntu
LOGNAME=ubuntu
XDG_SESSION_TYPE=tty
HOME=/home/ubuntu
LANG=C.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=00:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.avif=01;35:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.webp=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:*~=00;90:*#=00;90:*.bak=00;90:*.crdownload=00;90:*.dpkg-dist=00;90:*.dpkg-new=00;90:*.dpkg-old=00;90:*.dpkg-tmp=00;90:*.old=00;90:*.orig=00;90:*.part=00;90:*.rej=00;90:*.rpmnew=00;90:*.rpmorig=00;90:*.rpmsave=00;90:*.swp=00;90:*.tmp=00;90:*.ucf-dist=00;90:*.ucf-new=00;90:*.ucf-old=00;90:
SSH_CONNECTION=192.168.64.1 50169 192.168.64.7 22
LESSCLOSE=/usr/bin/lesspipe %s %s
XDG_SESSION_CLASS=user
TERM=xterm-256color
LESSOPEN=| /usr/bin/lesspipe %s
USER=ubuntu
SHLVL=1
XDG_SESSION_ID=3
XDG_RUNTIME_DIR=/run/user/1000
SSH_CLIENT=192.168.64.1 50169 22
XDG_DATA_DIRS=/usr/local/share:/usr/share:/var/lib/snapd/desktop
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/1000/bus
SSH_TTY=/dev/pts/0
_=/usr/bin/env

5.Edit your shell profile to display the date at login and change your prompt.
ubuntu@giving-chipmunk:~$ echo 'echo "today date is $(date)"' >> ~/.bashrc
echo 'PS1="\u@\h:\w\$ "' >> ~/.bashrc
source ~/.bashrc
todays date is Sun Apr 6 10:46:30 UTC 2025' >> ~/.bashrc
echo 'PS1=u@h:w$ ' >> ~/.bashrc
source ~/.bashrc
exit

ubuntu@giving-chipmunk:~$  echo 'echo todays date is Sun Apr  6 10:47:51 UTC 2025
today date is Sun Apr  6 10:47:51 UTC 2025

6.Redirect the output of the ls command to a file called file_list.txt.
ubuntu@giving-chipmunk:~$ ls > file_list.txt

7.Use file globbing to list all .txt files in the current directory.
ubuntu@giving-chipmunk:~$ ls *.txt
file_list.txt

8.Redirect the output of the ls command to a file and append it.
ubuntu@giving-chipmunk:~$ ls >> file_list.txt
ubuntu@giving-chipmunk:~$ ls
echo  exit  file_list.txt  source

9.Use a pipe to send the output of ls to the grep command to filter for files containing the word "report".
ubuntu@giving-chipmunk:~$ ls | grep "report"

10.Use head to view the first 10 lines of a file, and tail to view the last 10 lines.
ubuntu@giving-chipmunk:~$ head file_list.txt
echo
exit
file_list.txt
source
echo
exit
file_list.txt
source
ubuntu@giving-chipmunk:~$ tail file_list.txt
echo
exit
file_list.txt
source
echo
exit
file_list.txt
source

11.Use cut to extract the second column of a file called data.csv.
ubuntu@giving-chipmunk:~$ echo -e "id,name,age\n1,nesma,22\n2,salma,22\n3,nada,22" > data.csv
ubuntu@giving-chipmunk:~$ cut -d',' -f2 data.csv
name
nesma
salma
nada

12.Search for all lines in a file called log.txt that contain the word "ERROR" using grep.
ubuntu@giving-chipmunk:~$ echo -e "INFO: System started\nWARNING: Low disk space\nERROR: Failed to load module\nINFO: Update completed\nERROR: Timeout occurred" > log.txt
ubuntu@giving-chipmunk:~$ cat log.txt
INFO: System started
WARNING: Low disk space
ERROR: Failed to load module
INFO: Update completed
ERROR: Timeout occurred
ubuntu@giving-chipmunk:~$ grep "ERROR" log.txt
ERROR: Failed to load module
ERROR: Timeout occurred

13.Create a shell variable called current_user to store the output of the whoami command.
ubuntu@giving-chipmunk:~$ current_user=$(whoami)
ubuntu@giving-chipmunk:~$ echo $current_user
ubuntu

14.Use tr to convert a string of lowercase letters to uppercase.
ubuntu@giving-chipmunk:~$ echo "nesma ibrahim" | tr 'a-z' 'A-Z'
NESMA IBRAHIM

15.Use a pipe to send the output of ps to grep to search for a specific process name.
ubuntu@giving-chipmunk:~$ ps aux | grep ssh
root         993  0.0  0.8  12020  8064 ?        Ss   05:28   0:00 sshd: /usr/sbin/sshd -D [listener] 0 of 10-100 startups
root         994  0.0  0.8  14736  8048 ?        Ss   05:28   0:00 sshd: ubuntu [priv]
ubuntu      1109  0.2  0.7  14992  6948 ?        S    05:28   0:06 sshd: ubuntu@notty
root        2307  0.0  0.8  14868  8048 ?        Ss   05:29   0:00 sshd: ubuntu [priv]
ubuntu      2353  0.0  0.7  15028  6948 ?        S    05:29   0:00 sshd: ubuntu@pts/0
ubuntu     38804  0.0  0.2   7076  2048 pts/0    S+   06:12   0:00 grep --color=auto ssh

16.Create a Bash alias named ls for the command ls -l.
ubuntu@giving-chipmunk:~$ echo "alias ls='ls -1'" >> ~/.bashrc
source ~/.bashrc
todays date is Sun Apr 6 10:46:30 UTC 2025' >> ~/.bashrc
echo 'PS1=u@h:w$ ' >> ~/.bashrc
source ~/.bashrc
exit

ubuntu@giving-chipmunk:~$  echo 'echo todays date is Mon Apr  7 06:13:15 UTC 2025
today date is Mon Apr  7 06:13:15 UTC 2025

17.Use sort to sort the output of ls -l by file size.
ubuntu@giving-chipmunk:~$ ls -lS
total 12
-rw-rw-r-- 1 ubuntu ubuntu 121 Apr  6 10:08 log.txt
-rw-rw-r-- 1 ubuntu ubuntu  62 Apr  6 09:54 file_list.txt
-rw-rw-r-- 1 ubuntu ubuntu  44 Apr  6 10:06 data.csv
-rw-rw-r-- 1 ubuntu ubuntu   0 Apr  6 09:46 echo
-rw-rw-r-- 1 ubuntu ubuntu   0 Apr  6 09:46 exit
-rw-rw-r-- 1 ubuntu ubuntu   0 Apr  6 09:46 source

18.Use grep to count the number of lines that contain the word "success" in a file.
ubuntu@giving-chipmunk:~$ echo -e "success\nfailure\nsuccess\nsuccess\nerror" > successfile.txt
ubuntu@giving-chipmunk:~$ grep -c "success" successfile.txt
3

19.Redirect the output of the dmesg command to a file and view the first 20 lines using head.
ubuntu@giving-chipmunk:~$ sudo dmesg > dmesg_output.txt
ubuntu@giving-chipmunk:~$ head -n 20 dmesg_output.txt
[    0.000000] Linux version 6.8.0-57-generic (buildd@lcy02-amd64-040) (x86_64-linux-gnu-gcc-13 (Ubuntu 13.3.0-6ubuntu2~24.04) 13.3.0, GNU ld (GNU Binutils for Ubuntu) 2.42) #59-Ubuntu SMP PREEMPT_DYNAMIC Sat Mar 15 17:40:59 UTC 2025 (Ubuntu 6.8.0-57.59-generic 6.8.12)
[    0.000000] Command line: BOOT_IMAGE=/vmlinuz-6.8.0-57-generic root=LABEL=cloudimg-rootfs ro console=tty1 console=ttyS0
[    0.000000] KERNEL supported cpus:
[    0.000000]   Intel GenuineIntel
[    0.000000]   AMD AuthenticAMD
[    0.000000]   Hygon HygonGenuine
[    0.000000]   Centaur CentaurHauls
[    0.000000]   zhaoxin   Shanghai  
[    0.000000] BIOS-provided physical RAM map:
[    0.000000] BIOS-e820: [mem 0x0000000000000000-0x000000000009ffff] usable
[    0.000000] BIOS-e820: [mem 0x0000000000100000-0x00000000007fffff] usable
[    0.000000] BIOS-e820: [mem 0x0000000000800000-0x0000000000807fff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x0000000000808000-0x000000000080afff] usable
[    0.000000] BIOS-e820: [mem 0x000000000080b000-0x000000000080bfff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x000000000080c000-0x000000000080ffff] usable
[    0.000000] BIOS-e820: [mem 0x0000000000810000-0x00000000008fffff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x0000000000900000-0x000000003ee5bfff] usable
[    0.000000] BIOS-e820: [mem 0x000000003ee5c000-0x000000003ef1cfff] reserved
[    0.000000] BIOS-e820: [mem 0x000000003ef1d000-0x000000003f8ecfff] usable
[    0.000000] BIOS-e820: [mem 0x000000003f8ed000-0x000000003fb6cfff] reserved

20.Use cut to extract the first field from a CSV file and display it.
ubuntu@giving-chipmunk:~$ cut -d',' -f1 data.csv
id
1
2
3
