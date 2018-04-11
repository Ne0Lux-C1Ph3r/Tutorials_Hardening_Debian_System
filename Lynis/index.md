<b><p align="center">LYNIS Hardening Debian System</p></b>
----------------------------------------

<p align="center">
  <img src="../files/lynis.png"/>
</p>

----------------------------------------

Description:
```
Lynis written in shell script, audits your machine's configuration to evaluate and verify its security.
Once the scan is complete, it publishes a report to take advantage of this analysis.
```
Installation Lynis:

```
sudo wget -O - https://packages.cisofy.com/keys/cisofy-software-public.key | sudo apt-key add -

echo "deb https://packages.cisofy.com/community/lynis/deb/ stretch main" | sudo tee /etc/apt/sources.list.d/cisofy-lynis.list

sudo apt-get update && sudo apt-get install lynis
```
Modification of lynis for problems modules updates: 

```
EN CONSTRUCTION


```
