# selfhost_RPAutomatedConfig


Based off a guide (https://geoffhudik.com/tech/2020/04/27/automating-raspberry-pi-setup/) and source (https://github.com/thnk2wn/rasp-cat-siren/tree/main/pi-setup) for custom home server solution. 


## Steps

1. Create a new boot SD card for a target RaspberryPi 
1. Copy the files from the repo (and customise the wpa_supplicant.conf file)
1. Insert SD card in Pi and power on
1. Locate pi on local netork. 
1. SSH `ssh pi@raspberrypi`
1. Run script `sudo /boot/setup2.sh --host RP4Dev2`

## Example usage when ssh'd into Pi
`ssh pi@raspberrypi`

`sudo /boot/setup2.sh --host RP4Dev2`

## What does it do?
* changes the hostname of the pi so it can be addressed directly. e.g. "rp4dev2.local" instead of an IP address
* Prompts user to change password
* Installs Docker + sets up user account
* Reboot
