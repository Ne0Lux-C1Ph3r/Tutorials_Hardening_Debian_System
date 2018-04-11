
<b><p align="center">DOCKER Hardening Debian System</p></b>
----------------------------------------

<p align="center">
  <img src="../files/docker.png"/>
</p>


----------------------------------------

Description:

```
Docker is a tool designed to make it easier to create, deploy, and run applications by using containers.
Container virtualization is based on Linux LXC virtualization for Linux Containers. This is a 
partitioning method at the OS level. The principle is to run Linux environments isolated from each other
in containers sharing the same kernel. This means that unlike traditional virtual machines, a container 
does not include OS, since it relies on the OS features of the host machine. The containers then access 
the host OS completely isolated from each other.

```
Installation Docker:

```
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -

sudo apt-key fingerprint 0EBFCD88

sources.list
deb [arch=amd64] https://download.docker.com/linux/debian buster edge

sudo apt-get install docker-ce

```
Configuration minimal localhost:

```

EN CONSTRUCTION

```

