deddee# Hardware BikeTRack
Repository of embedded code of BikeTrack
update
____________
## Get started

### Clone the depot
```bash
cd whereYouWannaClone
git clone git@github.com:BikeTrack/APIv2.git
```

### Install Arduino 
To develop on Arduino please download Arduino editor [here](https://www.arduino.cc/en/Main/Software) and follow instructions to install it.

### Arduino libraries
Our code use libraries. You can add in your library's folder. They are on our git on the folder __librariesArduino__.

____________

## Electronics Components
### V1
* [Akeru beta 3.3](http://snootlab.com/lang-en/snootlab-shields/829-akeru-beta-33-en.html)
* [Accelerometer ADXL 335](https://learn.adafruit.com/adafruit-analog-accelerometer-breakouts/downloads)
* [GPS Bee Kit](http://wiki.seeedstudio.com/wiki/GPS_Bee_kit)
* Batterie

### V2
```on development```
* [Airboard](http://www.theairboard.cc)
* [Accelerometer ADXL 335](https://learn.adafruit.com/adafruit-analog-accelerometer-breakouts/downloads)
* [GPS Bee Kit](http://wiki.seeedstudio.com/wiki/GPS_Bee_kit)
* [Sigfox Remote with XBee Socket](https://www.cooking-hacks.com/sigfox-module-for-arduino-waspmote-raspberry-pi-intel-galileo-868-mhz-7184)

## Code
The code takes the number version of hardware components

____________
## Display & test
In the folder __affichageTest__ you can find code to display and testing BikeTrack hardware data.
* __sigfox.php__ - file call by the Sigfox'back-end to save data on file .json
* __sigfoxData.json__ - file contains data of BikeTrack like latitude or longitude
* __display.html__ - testing page to display last positions of BikeTrack

____________
## Battery Level (on development)
In the folder batteryLevel/ you can find an Arduino program to check the battery level of your devices
![Battery Level Design](https://github.com/BikeTrack/Hardware/blob/master/.pictures/batteryLevelDesign.png)
![Battery Level Schema](https://github.com/BikeTrack/Hardware/blob/master/.pictures/batteryLevelSchema.png)

Made by [Félix Moulin](www.felix-moulin.fr) with ❤️  on a :bike:
