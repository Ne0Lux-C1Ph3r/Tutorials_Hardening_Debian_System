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

Problem1 recognition PHP7.2:
File modify for recognition PHP7.2 <p><a href="https://github.com/Ne0Lux-C1Ph3r/Tutorials_Hardening_Debian_System/blob/master/files/tests_php" target="_blank">tests_php</a></p>

Problem2 recognition inetd but not xinetd:
inetd isn't call but maybe xinetd file modify for changed inetd vs xinetd <p><a href="https://github.com/Ne0Lux-C1Ph3r/Tutorials_Hardening_Debian_System/blob/master/files/tests_insecure_services" target="_blank">tests_insecure_services</a></p>


