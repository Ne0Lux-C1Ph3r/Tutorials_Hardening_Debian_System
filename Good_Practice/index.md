<b><p align="center">G00D PR4CT1C3 4 D3V3L0PM3NT 4ND H4RD3N1NG $Y$T3M</p></b>
----------------------------------------

<p align="center">
  <img src="../files/hard.jpeg"/>
</p>

<p align="center">
  <img src="../files/security.png"/>
</p>

----------------------------------------

Description:

```
Several installations to protect the system to develop and more !!!!
```


```
First see my tutorials.....
Secondly there is an order in the configurations and installations!!!
I'll come back to it later.
"I will not be responsible for errors or even worse"
"Always check and check before"
```

Order for hardening system: Yes/No

After installation, modify, before reboot:

In progress:

```
*** SEE ANSSI RECOMMENDATION and OTHERS UBUNTU, DEBIAN AND OTHERS ***

/etc/adduser.conf
DSHELL=/bin/bash in DSHELL=/bin/false if problem go back into bash.

/etc/bash.bashrc
Add umask 0027

/etc/gdm3/daemon.conf
AllowRoot = false
DisallowTCP = true

/etc/hosts ==> example minimal!!!
127.0.0.1	localhost local localhost.localdomain
127.0.1.1	$MACHINE-NAME
# The following lines are desirable for IPv6 capable hosts
::1     localhost ip6-localhost ip6-loopback
fe00::0 ip6-localnet
ff00::0 ip6-mcastprefix
ff02::1 ip6-allnodes
ff02::2 ip6-allrouters
255.255.255.255 broadcasthost
0.0.0.0 0.0.0.0

/etc/hosts.allow
ALL: LOCAL 127.0.0.1

/etc/hosts.deny
ALL: ALL
ALL: PARANOID

/etc/issue
/etc/issue.net
/etc/motd
SEE /etc/banners
See my folder ansible for example.
Put a security phrase of logging and not left the name of system. 

/etc/login.defs
See my folder ansible for example except PASS_MAX_DAYS and PASS_MIN_DAYS and PASS_WARN_AGE!!!.
Add umask 0077
Add LOGIN_RETRIES		2
Add SHA_CRYPT_MIN_ROUNDS 65536 ==> however, it will be necessary 
to modify /etc/pam.d/common-password "SEE ANSSI RECOMMENDATION"


/etc/logrotate
Modify in daily and not in weekly and put a compressor. 

/etc/modprobe.d/hardening.conf
See my folder ansible for modules to disable.

/etc/profile
Add umask 0027

/etc/securetty
See my folder ansible for example if not just put console for r00t.

/etc/sysctl.conf
See my folder ansible for example.

/etc/security/limits.conf minimal see more on internet!!
*               soft    core            0
*               hard    core            0

/etc/ssh/sshd_config
if installed!!
PermitRootLogin no
WARNING ON THE RSA KEYS!!!! CLEAR!!!!!!!!!!!!!!!!!!!
CTF is g00d THING for see that RSA hihihi!!!!!!
Almost always faults even according to the configurations.
For my part, I prefer a very hard "STRONG" password with security tool for denied!!!!!!

After, I will put options........

```
After update, upgrade and dist-upgrade, modify:
In progress:

```
/etc/aide...... after !!!!
​
/etc/ansible
See my folder ansible for example.
​
/etc/apache2...... after !!!!
​
/etc/apparmor...... after !!!!
​
/etc/apt...... after !!!!
​
/etc/audisp...... after !!!!
/etc/audit...... after !!!!
/etc/cron......after !!!!
/etc/default/......after !!!!
/etc/fstab
/etc/init.d/......after !!!!

```

EN CONSTRUCTION

For any good developer and programmer:
```
sudo apt-get install linux-headers-$(uname -r)
"important for installation virtualbox and others and ....."

For ruby and python lastest version:

sudo apt-get upgrade "except for python, download on site".

Ruby:
Create file in /home/$USER without "r00t" for more security!!!!
echo "gem: --user-install" >> ~/.gemrc

IN PROGRESS!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


```
