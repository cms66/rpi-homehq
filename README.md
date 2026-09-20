# rpi-homehq
Python setup and management system for a home RPi cluster. 
## First setup (server)
- Create SD with Raspberry Pi Imager (latest 64-bit Lite image) https://www.raspberrypi.com/software/operating-systems/
- Create files in visible partition (see example files)
    - hosts.txt
    - custom.conf
- Login as created user and run 
```
wget https://raw.githubusercontent.com/cms66/rpi-homehq/main/setup.py; sudo python ./setup.py
```
