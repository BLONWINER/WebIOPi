# WebIOPi
> This project forked from https://sourceforge.net/projects/webiopi/

## Usage 

$ wget https://github.com/BLONWINER/WebIOPi/archive/main.zip -O WebIOPi.zip  
$ unzip WebIOPi.zip  
$ cd WebIOPi-master/WebIOPi-0.7.1  
$ patch -p1 -i webiopi-pi2bplus.patch  
$ sudo ./setup.sh  

## Start WebIOPi

$ sudo webiopi -d -c /etc/webiopi/config

Then access webiopi through browser.

## References
https://github.com/doublebind/raspi