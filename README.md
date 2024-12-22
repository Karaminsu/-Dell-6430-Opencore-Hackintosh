# -Dell-6430-Opencore-Hackintosh


![alt text](https://github.com/Arewatechnology/-Dell-6430-Opencore-Hackintosh/raw/master/Screenshot%202020-09-27%20at%2011.37.48.png?raw=true)



# Specs
Os: macOS Catalina 10.15.6
CPU: Intel(R) Core(TM) i5-3340M CPU @ 2.70GHz Turbo 3.4Ghz (2 cores, 4 threads)
Ram: Micron 8GB DDR3-RAM @ 1600 Mhz (8KTF51264HZ-1G6E1)
GPU: Intel HD Graphics 4000 1536 Mb
SSD: INTEL SSDSC2BW180A3H 180 GB SSD 
Screen: 14" HD 1366x768




# works
Sound (in and out)
Trackpad with gestures
USB Ports including USB3 and USB2
DVD Player
Webcam (tested with Photobooth)
LAN/Ethernet
Fn keys to change volume or brightness
Battery percentage/status
Sleep/Wake-up
SD Card Reader
HDMI Out


# Doesn't work natively

Wifi (need to change internal card) ; I use a Atheros 9280 and hackintool for install kext https://github.com/headkaze/Hackintool/releases/
Bluetooth (not tested)
VGA out (Not Work but according to some users it can work)



# Settings
Once you have the correct BIOS version v12, go to the BIOS by using the F12 key at boot. Click on "Load defaults" then set SATA Operations to AHCI, set Boot List Option to UEFI and Disable Secure Boot.
