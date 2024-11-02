# UseraidPocket
Flipper Zero-like device for pentesting and fun :)

> ⚠️ **Note**: It's very much a work in progress

## 3D View
![Both](/PCB/Both.png)

## Hardware Features
- ESP32 S3 Wroom Module with external Antenna (Non U Modules are also footprint compatible though)
- 1.69" ST7789 TFT with adjustable backlight
- SD Card Interface
- L86 GPS + Glonass Module
- 18650 for fast swapping and high density
- Built in Charging and battery protection
- IR LED 4.5mW
- IR Reciever
- WS2818 RGB LED
- Onboard USB to Serial Converter for External Serial Applications
- Mosfet Driven Buzzer
- Accelerometer and Gyro - MPU6050
- DS3231 RTC (May be battery backed in future)
- ULDO can supply upto 1A
- 6 Tactile Buttons
- 2x Type C interface for Charging, OTG, Serial, JTAG, HID
- Expansion Port

## Expansion Port
- I2C
- Serial
- General Purpose port
### Off-the-shelf Module Compatibility 
The pinouts for the expansion ports are made so that readily available modules can be directly attached but since chinese modules don't follow conventions sometimes, I'll maintain this compatibility list.
#### NFC
- PN532 - I2C

#### RF
- FS1000A 

#### Environmental 
- BME280 - I2C

#### Display
- 1.3" I2C OLED - I2C

## Schematic
![Schematic](/PCB/Schematic.png)

## Software
> **Current State** : Waiting to refine the pcb design, add more features and then finally order the PCBs to work on the software properly. Currently the dynamic menu system has been implemented along with app support.

Firmware for the Useraid Pocket can be found [here.](https://github.com/useraid/UOSPocket) It is currently in design phase and I am waiting to refine the hardware first to start working on the firmware.
