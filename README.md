# S1 Popout Board by Silicon Witchery

A handy breakout board / development kit for the S1 Bluetooth-FPGA module.

**Features:**

- Solder-less form factor.
- USB Type-C charging & data.
- JST battery connector.
- Sparkfun [QWICC](https://www.sparkfun.com/qwiic) / Adafruit [STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) connector.
- 10 pin SWD connector.
- GPIO

## Bluetooth, FPGA & battery management in one module
The S1 Popout Board gets you quickly started with all kind of IoT projects. It carries our S1 Wearable Compute Module at it's core, and breaks out all the features so you can quickly start building.

- **Bluetooth 5.2** based on the Nordic nRF52811
- **iCE40 FPGA** with 5k LUT with DSP
- **Battery management** IC from Maxim with configurable boost rails
- **8Mb SPI Flash** for storing your FPGA bitstream or other data

## Plug & Play Sensors

Both Sparkfun and Adafruit make numerous I2C based sensor boards that can be daisy chained using the built in QUICC/STEMMA connector. There's no need to solder anything and there are tons of sensors for you to choose from such as:

- LSM9DS1 9 Axis Accelerometer/Gyro/Magentometer
- AS7341 10 channel visible & IR light sensor
- PA1010D GPS module
- APDS9960 Proximity Sensor
- Time of Flight sensor
- ST25DV16K re-programmable NFC tag
- Infineon Trust M Crypto co-processor & true random number generator
- OLED graphic displays

And many more. Check out Sparkfun's [QWICC](https://www.sparkfun.com/qwiic) and Adafruit's [STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) pages to see more.

## Battery & USB

You can use any single lithium polymer cell to power the Popout Board, or power it simply from a USB Type C port.

Connecting the USB cable will also charge any battery connected to the device. You can re-configure the charge rates and voltages over bluetooth but be sure to check out the documentation first as to not damage your battery from over charging. By default, the charge rate is low enough that even small cells will be safely charged, however bigger cells will take a long time.

In time we'll also be supporting USB data so you'll be able to talk to your Popout Board over USB.

## SuperStack Runtime

All our modules come with SuperStack pre-installed. (You can of course replace it with any nRF application you like using the 10pin SWD port connected to a Segger Jlink or nRF Development board as a programmer.)

With SuperStack you can wirelessly deploy FPGA binaries over Bluetooth using our serial JSON API.

