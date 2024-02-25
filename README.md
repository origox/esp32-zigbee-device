# esp32-zigbee-device

# HW
ESP32-C6-DEV-KIT-N8-M

# Enable USB from Windows to WSL2

```windows powershell
# Run from windows powershell
usbipd list
usbipd attach --wsl --busid=11-4
```
```bash
# Run from WSL 
# not too good but good enough for now...
sudo chmod 777 /dev/ttyACM0
```


