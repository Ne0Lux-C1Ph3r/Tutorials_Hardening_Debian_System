<b><p align="center">SUHOSIN7 FOR PHP7.2</p></b>
----------------------------------------

<p align="center">
  <img src="../files/suhosin.jpeg"/>
</p>

----------------------------------------

Suhosin Extension for PHP 7.x of <b><a href="https://github.com/sektioneins/suhosin7" style="color: rgb(255,0,0)">sektioneins</a></b>
https://www.suhosin.org


Suhosin7 compiled for PHP7.2

Good compilation for PHP7.2.


Put suhosin7.so in the folder in /usr/lib/php/20170718

Create suhosin7.ini in the folder /etc/php/7.2/mods-available with:
```
; configuration for php suhosin7 module

; priority=10

extension=suhosin7.so

#suhosin.simulation = off
```


Recreate link in /etc/php/7.2/apache2/conf.d and /etc/php/7.2/cli/conf.d


The command "php -m" confirm me that suhosin7 is present.


<a href="https://github.com/Ne0Lux-C1Ph3r/Tutorials_Hardening_Debian_System/blob/master/Suhosin7/suhosin7.so">suhosin7.so</a>
 
 
EN CONSTRUCTION


