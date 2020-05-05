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



#yay -S mraa




```



