# esp32-camera-micropython
Creating Time-lapse video using esp32 camera module with the help of micropython

sample images ![Image1](https://github.com/Himanshu495-rada/esp32-camera-micropython/blob/main/2.png?raw=true)

![Image2](https://github.com/Himanshu495-rada/esp32-camera-micropython/blob/main/3.png?raw=true)

## Guide
`https://www.youtube.com/watch?v=peTnIN9iicQ`

## Erase ESP-cam
```
esptool --port COM3 erase_flash
```
## Install micropython
```
 esptool --port COM3 write_flash -z 0x1000 .\esp32cam-mirco_python.bin
```#   m i c r o p y t h o n - c a m e r a  
 