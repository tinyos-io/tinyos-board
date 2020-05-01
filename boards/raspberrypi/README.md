https://archlinuxarm.org/platforms/armv6/raspberry-pi
https://archlinuxarm.org/platforms/armv6/raspberry-pi


https://weworkweplay.com/play/automatically-connect-a-raspberry-pi-to-a-wifi-network/


sudo nano /etc/wpa_supplicant/wpa_supplicant.conf


network={
ssid="YOUR_NETWORK_NAME"
psk="YOUR_NETWORK_PASSWORD"
proto=RSN
key_mgmt=WPA-PSK
pairwise=CCMP
auth_alg=OPEN
}





