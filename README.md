# selfhost_RPAutomatedConfig


Based off a guide (https://geoffhudik.com/tech/2020/04/27/automating-raspberry-pi-setup/) and source (https://github.com/thnk2wn/rasp-cat-siren/tree/main/pi-setup) for custom home server solution. 


## Steps

Create a new boot SD card for a target RaspberryPi 
Copy the files from the repo (and customise the wpa_supplicant.conf file)
Insert SD card in Pi and power on
Locate pi on local netork. 
SSh in

## Example usage when ssh'd into Pi

ssh pi@raspberrypi
sudo /boot/setup2.sh --host RP4Dev2
