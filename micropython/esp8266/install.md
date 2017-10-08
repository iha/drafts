`pip install esptool`

`esptool.py --port /dev/ttyUSB0 erase_flash`

[Download the firmware](http://micropython.org/download#esp8266)

`esptool.py --port /dev/ttyUSB0 --baud 460800 write_flash --flash_size=detect 0 esp8266-20170108-v1.8.7.bin`
