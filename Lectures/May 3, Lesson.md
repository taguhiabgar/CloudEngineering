Commands:
- `wc` - word count
- `wc -l` - line count
- `apt search openssh-server` - check if a package is installed or not
- `systemctl status ssh.service` - check if a service is currently running
- `systemctl start ssh.service` - start a service
- `systemctl stop ssh.service` - stop a service
- ssh - secure shell
- `less`
- `more`
- `head`
- `tail`
- `kill -9 887` - where 887 is example PID (process ID), and -9 is a signal sent to process
- `sudo su -`, then `reboot` -  for reboot
	- or, `systemctl reboot -i`
- `ip address` command
- `ssh 10.10.148.242 -l username` - same thing as `ssh username@10.10.148.242`, you can give username with `-l` option
- `chmod`

TASK: read about what signals can be sent

TASK: learn vim

TASK: learn about server-client architecture

`/etc`, `/var` - TASK: understand Linux folders, what are each of them used for

`sshd` - package name for ssh - ssh daemon, because it runs in the background

daemon processes - TASK: explore, what are they

Network protocols are a collection of standards for devices to interact with each other over network (example: http).

TASK: read about network protocols

TASK: read about Bridge vs. NAT network

TASK: create web server (nginx) on VM and open from browser

TASK: why are there no viruses on Linux?

TASK: read about apt vs. dpkg difference
