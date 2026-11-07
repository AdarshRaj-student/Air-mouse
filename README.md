# Air-mouse
This mouse works on air and works very smoth and its easy to create and for creating you just need this repository
# AirMouse 🖱️

An **Air Mouse** built using **ESP32 + MPU6050 + BLE Mouse library**.  
Move your hand → control the PC cursor via Bluetooth!  

## 🚀 Features
- Wireless mouse via BLE
- Motion tracking with MPU6050
- Left & Right click buttons
- Deadzone filtering & smoothing for stable movement

## 🛠️ Hardware Required
- ESP32 (with BLE support)
- MPU6050 (GY-521 or similar)
- Push buttons (x2) for left & right click
- Jumper wires & breadboard

## 📡 Pin Connections
| Component      | ESP32 Pin |
|----------------|-----------|
| MPU6050 SDA    | GPIO 21   |
| MPU6050 SCL    | GPIO 22   |
| Left Button    | GPIO 4    |
| Right Button   | GPIO 5    |
| VCC            | 3.3V      |
| GND            | GND       |

## 📦 Libraries Used
- [I2Cdev](https://github.com/jrowberg/i2cdevlib)
- [MPU6050](https://github.com/jrowberg/i2cdevlib/tree/master/Arduino/MPU6050)
- [BleMouse](https://github.com/T-vK/ESP32-BLE-Mouse)

Install these via Arduino IDE or PlatformIO.
