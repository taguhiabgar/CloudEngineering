
54 minute in video
https://drive.google.com/drive/folders/1TZA19-jw7Cdku2dcPKSKPGKxglg5mRbV

**Contents**:
- [[#Quiz]]
- [[#Shells]]
- [[#Processes]]
- [[#`free` command]]
- [[#`df -h` command]]
- [[#`lsblk` command]]
- [[#`top` command]]
- [[#Virtualization]]
- xx
- xx

# Quiz

![[Screenshot 2026-05-15 at 11.09.14.png]]

![[Screenshot 2026-05-15 at 11.11.30.png]]
![[Screenshot 2026-05-15 at 11.13.08.png]]

![[Screenshot 2026-05-15 at 11.14.43.png]]

![[Screenshot 2026-05-15 at 11.16.59.png]]

![[Screenshot 2026-05-15 at 11.17.51.png]]

![[Screenshot 2026-05-15 at 11.18.31.png]]

![[Screenshot 2026-05-15 at 11.19.11.png]]

![[Screenshot 2026-05-15 at 13.08.31.png]]

![[Screenshot 2026-05-15 at 13.08.53.png]]

![[Screenshot 2026-05-15 at 13.09.22.png]]

![[Screenshot 2026-05-15 at 13.09.47.png]]

# Shells

There are many types of shells. Shell is a program. Bash (short for Bourne Again Shell) is a popular text-based command-line interpreter and scripting language used to interact with Unix-like operating systems. It acts as a bridge between you and the computer kernel, translating your typed commands into actions the system can execute.

```bash
bash
man bash
```

![[Screenshot 2026-06-28 at 02.44.41.png]]

If you type in terminal command:
```bash
echo $SHELL
# prints /bin/bash
```
where `$SHELL` indicates SHELL environment variable, you will know which shell you're using now.

The command:

```bash
ls -la /bin/bash
```

uses the `ls` (list) command to display detailed information about the file `/bin/bash`.

The options mean:

- `-l` (long format) — shows detailed information such as:
    - file type and permissions
    - number of hard links
    - owner
    - group
    - file size
    - modification date
    - file name
- `-a` (all files) — includes hidden files (those starting with `.`). In this particular case, since you’re listing a specific file (`/bin/bash`) rather than a directory, `-a` usually has no effect.

For example:

```bash
$ ls -la /bin/bash
-rwxr-xr-x 1 root root 1265648 Mar 15 12:34 /bin/bash
```

This output means:

|Field|Meaning|
|---|---|
|`-rwxr-xr-x`|File type (`-` means regular file) and permissions|
|`1`|Number of hard links|
|`root`|Owner|
|`root`|Group|
|`1265648`|File size in bytes|
|`Mar 15 12:34`|Last modification time|
|`/bin/bash`|File name|

For example, on some systems you might see:

```bash
$ ls -la /bin/bash
lrwxrwxrwx 1 root root 12 Jan 10 2025 /bin/bash -> /usr/bin/bash
```

The leading `l` indicates that `/bin/bash` is a symbolic link, and `-> /usr/bin/bash` shows where it points.

# Processes

The `ps` command (process status) displays information about running processes on the system.

## ps

https://www.geeksforgeeks.org/linux-unix/ps-command-in-linux-with-examples/

## ps aux

This is one of the most common ways to view processes:

```bash
ps aux
```

It displays all running processes on the system, regardless of terminal or user.

The options come from BSD-style syntax:

- `a` — show processes for all users attached to terminals
- `u` — display in a user-oriented format (owner, CPU, memory, etc.)
- `x` — include processes without a controlling terminal (background services, daemons)

Example:

```bash
$ ps aux
USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root         1  0.0  0.1 167840 12000 ?        Ss   Jun27   0:03 systemd
root       789  0.0  0.0  10520  3500 ?        Ss   Jun27   0:00 sshd
alice     2450  0.2  1.1 125000 90000 pts/0    Sl   10:15   0:10 firefox
```

### Columns

|Column|Meaning|
|---|---|
|`USER`|Process owner|
|`PID`|Process ID|
|`%CPU`|Percentage of CPU currently used|
|`%MEM`|Percentage of RAM used|
|`VSZ`|Virtual memory size (KB)|
|`RSS`|Resident memory (physical RAM, KB)|
|`TTY`|Terminal (`?` means no terminal)|
|`STAT`|Process state|
|`START`|Start time/date|
|`TIME`|Total CPU time consumed|
|`COMMAND`|Command line used to start the process|

## Process state (`STAT`) examples

The `STAT` column contains codes describing the process state:

|Code|Meaning|
|---|---|
|`R`|Running|
|`S`|Sleeping (interruptible)|
|`D`|Uninterruptible sleep (usually I/O)|
|`T`|Stopped|
|`Z`|Zombie|
|`I`|Idle kernel thread|

Additional modifiers:

|Modifier|Meaning|
|---|---|
|`s`|Session leader|
|`l`|Multi-threaded|
|`+`|Foreground process group|

Examples:

- `Ss` — sleeping session leader
- `Sl` — sleeping, multi-threaded
- `R+` — running in the foreground terminal

---

## Useful variants

### Show processes as a tree

```bash
ps -ef --forest
```

Example:

```
root         1 systemd
 ├─sshd
 │   └─bash
 │       └─vim
```

### Search for a process

```bash
ps aux | grep nginx
```

### Show only your processes

```bash
ps -u $USER
```

### Full process information

```bash
ps -ef
```

This uses the POSIX/System V style options:

- `-e` = all processes
- `-f` = full format

## Why are there two styles (`ps aux`vs`ps -ef`)?

Historically, Unix developed two incompatible option syntaxes:

|BSD style|System V/POSIX style|
|---|---|
|`ps aux`|`ps -ef`|
|No leading `-`|Uses leading `-`|
|Common on BSD/macOS|Common on Linux and Unix|

On Linux, both styles are supported and are roughly equivalent:

```bash
ps aux
ps -ef
```

Both show all processes; they just format the output differently.

# `free` command

https://www.geeksforgeeks.org/linux-unix/free-command-linux-examples/

# `df -h` command

https://www.geeksforgeeks.org/linux-unix/df-command-linux-examples/

# `lsblk` command

https://www.geeksforgeeks.org/linux-unix/lsblk-command-in-linux-with-examples/

# `top` command

https://www.geeksforgeeks.org/linux-unix/top-command-in-linux-with-examples/


# Virtualization

Question: If we have 2 VMs, how can we make them communicate with each other?



