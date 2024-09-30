## FEATURES :
* [+] Deauth
* [+] Evil-Twin
* [+] User Interface

## TESTED ON :
* ESP32s - Nodemcu
* ESP8266 - Nodemcu
* Probably will work in all-other boards too..

  ## CONCEPT :
* Connect to the Access Point named `ertool` with password `Eviltwin` from your device.
* Select the target you want (list of available APs refreshes every 15secs - page reload is required).
* Select The Attack Mode. If you choose Deauth it will start deauthing the clients in that network.
* Then Start Evil-twin attack, which will create the clone of the selected network.
* The web interface will be unavailable during Evil-twin attack mode, You need to reconnect.
* Reconnect after some time, it will display you the correct password in Result section.

## ESP32 INSTALLATION
* Install [Arduino IDE](https://www.arduino.cc/en/software)
* Add Esp32 in Additional Board Manager
* Install your board, choose correct Port.
* Compile and Upload *ESP32.ino* file.

## ESP 8266 INSTALLATION
* Install [Arduino IDE](https://www.arduino.cc/en/software)
* Add Esp32 in Additional Board Manager
* Install your board, choose correct Port.
* Compile and Upload *ESP8266.ino* file.


## INSTALLATION :
* Install [Arduino IDE](https://www.arduino.cc/en/software)
* Add Esp32 in Additional Board Manager
* Install your board, choose correct Port.
* Compile and Upload ESP32.ino file.

## WARNING :
Use it only against your own networks and devices!
Please check the legal regulations in your country before using it.
We don't take any responsibility for what you do with this program.

## DONATIONS :
- Paypal ; @ErenKrb. 

