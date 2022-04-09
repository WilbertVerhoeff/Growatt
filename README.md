# Growatt
Growatt ShineWifi modbus with ESPHome code to run native in Home Assistant

Thanks to Jethro Kairys https://github.com/jkairys/growatt-esp8266 for his work of the Arduino code and otti https://github.com/otti/Growatt_ShineWiFi-S for his work on the ShineWifi hardware.

Thanks to this guys i was able to convert the code to ESPHome so there is a one time flashing and then everything is manageable via ESPHome.

The manufacturer has done a great job in making the connections available to easy flash the board with a ttl to serial adapter. I will make pictures of the ShineWifi-S that i have.

# Flashing

The TX and RX pin on the PCB are already twisted with the ESP so you can connect TX to TX and RX to RX on your serial adapter. With the ShineWifi-S and my serial adapter i had nothing else to do then flash it BUT otti (https://github.com/otti/Growatt_ShineWiFi-S) "added a 1k resistor between the output of the SW1 and GPIO0" to get the board into boot mode on startup.

# Tested and working

ShineWifi-s <br>
ShineWifi-x
