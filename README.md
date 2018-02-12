[![ MCP7455L](MCP7455L_I2C.png)](https://store.ncd.io/product/mma7455l-3-axis-low-g-digital-output-accelerometer-i2c-mini-module/).

#  MCP7455L

Manufactured by Freescale Semiconductor, Inc., the MMA7455L 3-Axis Digital Output Accelerometer is a low power, micro-machined sensor capable of measuring acceleration along its X, Y, and Z axes.This device can be easily configured to detect quick motion pulses as single-taps, double-taps, and 0g (free-fall) conditions on any or all axis and provides configurable interrupt pins (INT1 and INT2) for each type of event.
This Device is available from www.ncd.io 

[SKU: MCP7455L]

(https://store.ncd.io/product/mma7455l-3-axis-low-g-digital-output-accelerometer-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MCP7455L 3Axis accelometer With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mma7455l-3-axis-low-g-digital-output-accelerometer-i2c-mini-module/">MCP7455L 3Axis accelometer sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MCP7455L.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
