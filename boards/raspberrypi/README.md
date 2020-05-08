https://archlinuxarm.org/platforms/armv6/raspberry-pi
https://archlinuxarm.org/platforms/armv6/raspberry-pi


## setup 
## __________________________________________________________________________________________
https://github.com/Jguer/yay
```
pacman -S git
pacman -S base-devel go
```

## installing Wifi: netctl 
## __________________________________________________________________________________________
https://wiki.archlinux.fr/netctl
https://wiki.archlinux.org/index.php/Netctl
https://raspberrypi.stackexchange.com/questions/7987/wifi-configuration-on-arch-linux-arm
```
install -m640 examples/wireless-wpa wirelesshome
netctl start wirelesshome
netctl enable wirelesshome
```

## MRAA
## __________________________________________________________________________________________

https://docs.labs.mediatek.com/resource/linkit-smart-7688/en/tutorials/peripheral-support-on-linkit-smart-7688-development-board/using-mraa-in-python

https://github.com/eclipse/mraa/blob/master/docs/building.md


```
sudo pacman -S python python-pip
git clone https://github.com/abdullatifmouhamadi/archlinux.git
makepkg -si

```

## RF24
## __________________________________________________________________________________________
http://tmrh20.github.io/RF24/
https://github.com/nRF24/RF24
https://tmrh20.github.io/RF24/Linux.html
https://tmrh20.github.io/RF24/CrossCompile.html


CrossCompile:
```
sudo pacman -S expect dejagnu
yay -S arm-linux-gnueabihf-gcc



```

-:
```



```


## DNS issues

https://archlinuxarm.org/forum/viewtopic.php?f=60&t=13950

resolvectl dnssec

In /etc/systemd/resolved.conf I changed: #DNSSEC=allow-downgrade to DNSSEC=no.

Then restart with sudo systemctl restart systemd-resolved















