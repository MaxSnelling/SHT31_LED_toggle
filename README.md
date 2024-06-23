LED Humidity Monitor

This project toggles the color of an LED based on the humidity measurements from an SHT31 sensor. The STM32 Nucleo board reads humidity data from the SHT31 sensor using I2C and changes the LED color to indicate different humidity levels.

### Features
- Reads humidity data from the SHT31 sensor.
- Changes LED color based on humidity level:
  - Green: Humidity is below the normal threshold.
  - Red: Humidity is above the normal threshold (too humid).
  - Blue: Communication to sensor is in error.
  
