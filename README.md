# Camp-Software
Software needed for Destination SPACE Satellite Week

## Arduino IDE 2.1.0 (or newer)
1. Download Arduino IDE 2.1.0 from [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)
2. Install Arduino IDE
  - Agree to the license agreement
  - Complete setup
3. Open Arduino IDE

### Installing board manager
1. Open Arduino IDE
2. Go to **Files > Preferences**
3. In the **Additional boards manager URLs:** text box, enter ```https://files.seeedstudio.com/arduino/package_seeeduino_boards_index.json```
4. Click **OK**
5. Go to **Tools > Board > Boards Manager...**
6. In the search box enter ```Seeed SAMD Boards```
7. Click **Install**

### Installing Software Libraries
1. Open Arduino IDE
2. Go to **Sketch > Include Library > Manage Libraries...**
3. In the search box enter and install the following libraries:

*Note: If prompted to **Install library dependencies**, click **Install All***
  - ```Adafruit SSD1306``` by Adafruit
  - ```Adafruit BME280 Library``` by Adafruit
  - ```BH1750``` by Christopher Laws
  - ```SparkFun SCD4x Arduino Library``` by SparkFun Electronics
