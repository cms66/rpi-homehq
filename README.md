# rpi-homehq
This is a Python setup and management system for a home RPi cluster. The aim of the project is
- Gather data from multiple local devices for security, environment monitoring etc.
- Process data using local cluster resources
- Save relevant data locally
- Backup local data to cloud or other off-site provider

## First setup (server)
- Create SD with Raspberry Pi Imager (latest 64-bit Lite image) https://www.raspberrypi.com/software/operating-systems/
- Create files in visible partition (see example files)
    - hosts.txt
    - custom.conf
### First boot
- login as created user and run 
```
wget https://raw.githubusercontent.com/cms66/rpi-homehq/main/setup.py; sudo python ./setup.py
```
