# BusyBee
BusyBee is a accelerometer hooked up to wifi sending its data to server when it is moved.

This project is supposed to help indicate if a football table is currently occupied.

## Hardware

To archieve our goal we are using a MPU-6050 (GY-521) hooked up to a ESP8266 WiFi module.

### ESP8266
To connect the esp to your wifi: http://www.martyncurrey.com/arduino-esp8266/

![Pin Out ESP8266-01](http://cdn.instructables.com/FEO/6592/ICNNIGDJ/FEO6592ICNNIGDJ.MEDIUM.jpg)

There are a couple of ways to directly program this SOC. We are using the Arduino way.
Read more about it here: https://blog.thesen.eu/esp8266-wlan-microcontroller-mit-der-arduino-ide-programmieren/

To connect to the board via FTDI you should consider that it only takes 3.3V and for
convenience we are building a custom developer board to flash it properly

### Schematics

#### Developer Board

![Developer Board for flashing](https://blog.thesen.eu/wp-content/uploads/2015/04/esp8266-progboard.png)