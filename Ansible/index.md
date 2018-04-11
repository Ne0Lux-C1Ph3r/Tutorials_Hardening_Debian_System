<b><p align="center">ANSIBLE Hardening Debian System</p></b>
----------------------------------------

<p align="center">
  <img src="../files/ansible.png"/>
</p>


----------------------------------------

Description:

```
Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced
IT tasks such as continuous deployments or zero downtime rolling updates.
```
Installation Ansible:

```
sudo apt-get install ansible
```
Configuration minimal localhost:

```

EN CONSTRUCTION


```

Description tasks and templates for hardening:

```
Modification files:
/etc/hosts.allow
/etc/hosts.deny
/etc/issue
/etc/issue.net
/etc/banners
/etc/motd
/etc/bash.bashrc
/etc/profile
/etc/login.defs
/etc/modprobe.d/hardening1.conf
/etc/modprobe.d/hardening2.conf
/etc/sysctl.conf
/etc/securetty
/etc/security/access.conf

EN CONSTRUCTION OU VERIFICATION OU TEST:
iptables
apparmor
limits.conf
systemctl services ou reboot system
fstab
acct
auditd
module apache2
suhosin7
Many others.......

```


