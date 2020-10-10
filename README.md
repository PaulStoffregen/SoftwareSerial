# SoftwareSerial 

The SoftwareSerial library has been developed to allow serial communication on other digital pins of the Arduino, using software to replicate the functionality (hence the name "SoftwareSerial"). It is possible to have multiple software serial ports with speeds up to 115200 bps. A parameter enables inverted signaling for devices which require that protocol.

The version of SoftwareSerial included in 1.0 and later is based on the NewSoftSerial library by Mikal Hart. 

# New Features!

```sh
DigiSpark 16Mhz
```
 
 # To use this library

```sh
#include <SoftwareSerial.h>.
```

# Limitations
```sh
    If using multiple software serial ports, only one can receive data at a time.
    Not all pins on the Mega and Mega 2560 support change interrupts, so only the following can be used for RX: 10, 11, 12, 13, 14, 15, 50, 51, 52, 53, A8 (62), A9 (63), A10 (64), A11 (65), A12 (66), A13 (67), A14 (68), A15 (69).
    Not all pins on the Leonardo and Micro support change interrupts, so only the following can be used for RX: 8, 9, 10, 11, 14 (MISO), 15 (SCK), 16 (MOSI).
    On Arduino or Genuino 101 the current maximum RX speed is 57600bps
    On Arduino or Genuino 101 RX doesn't work on Pin 13 
```
