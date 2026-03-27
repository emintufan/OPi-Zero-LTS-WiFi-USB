# Introduction
This is a port of mrfenyx's RPi-Zero-W-WiFi-USB script to Orange Pi Zero LTS. It is using Filebrowser Quantum rather than Samba.

# Automated Setup
You need to flash latest Armbian (Minimal / IOT, Debian) image to the device and power it on. After a successful connection to a network, run those commands via SSH:
```
sudo apt update && sudo apt upgrade -y
sudo apt install git -y
git clone https://github.com/emintufan/OPi-Zero-LTS-W-WiFi-USB.git
cd OPi-Zero-LTS-W-WiFi-USB
sudo chmod +x install.sh
sudo ./install.sh
```
# Accessing to Filebrowser Quantum
Just go: http://YOUR-ORANGE-PI-LOCAL-IP/
Enter login credentials:
```
Username: admin
Password: admin
```
And don't forget to change your credentials!
