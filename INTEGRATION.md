### Checks
* How to check if port is in use in
`sudo netstat -tulpn | grep LISTEN`
* Configuration Z2M `frontend` gives gui interface to handle devices
###  [Mosquitto](https://mosquitto.org/) (MQTT brocker)
#### Installation
* `sudo apt-add-repository ppa:mosquitto-dev/mosquitto-ppa`
* `sudo apt-get update`

### npm / [nvm](https://github.com/nvm-sh/nvm#installing-and-updating) / node
* nvm allows you to quickly install and use different versions of node via the command line.

### [Conbee II](https://phoscon.de/en/conbee2)
* Should be plugged into computer by usb2 cable for better communication 
* Issues [Here](https://phoscon.de/en/support#conbee2-connection-issues)
* `lsusb` list usb devices linked into computer. Should print Dresden Elektronik
* `ls -l /dev/ttyACM*` check serial interface available to configure
* [Flashing USB stick](https://github.com/dresden-elektronik/deconz-rest-plugin/wiki/Update-deCONZ-manually#update-in-ubuntu-or-debian)