# DHT11-DHT22-Sensor-interfacing-with-esp32

# Arduino DHT11 and DHT22 Sensor Readings

![DHT Sensors](dht_sensors.jpg)

## Overview

This Arduino project reads data from DHT11 and DHT22 sensors to measure temperature and humidity. The DHT11 sensor is a basic and affordable option, while the DHT22 sensor provides higher accuracy. Both sensors are connected to the same Arduino board, allowing simultaneous data acquisition.

## Hardware Requirements

For this project, you will need the following components:

- Arduino board (e.g., Arduino Uno)
- DHT11 sensor
- DHT22 sensor
- Jumper wires
- Optional: Breadboard for convenient connections

## Wiring Diagram

Please refer to the provided wiring diagram for connecting the components:

![image](https://github.com/Shivani9698/DHT11-DHT22-Sensor-interfacing-with-esp32/assets/119753029/3ffb8bc5-ae68-40d6-a9bf-b2484e6b7322)


## Installation

1. Connect the DHT11 sensor to the `DHTPIN_11` (pin 26) and the DHT22 sensor to the `DHTPIN_22` (pin 27) on the Arduino board.

2. Upload the code to the Arduino board using the Arduino IDE.

3. Open the Serial Monitor in the Arduino IDE to view the temperature and humidity readings.

## How it Works

- The code initializes both DHT11 and DHT22 sensors and the serial communication at a baud rate of 115200 bits per second.

- In the `loop()` function, the code reads data from both sensors, obtaining temperature and humidity values.

- The obtained readings are then printed to the Serial Monitor for viewing.

## Sensor Calibration (Optional)

If you notice discrepancies between the readings of the DHT11 and DHT22 sensors, you may need to calibrate them. Calibration involves adjusting the readings of one sensor to match the other. This is especially important if you want more consistent results from the sensors.

## Troubleshooting

If you encounter any issues:

- Double-check the wiring connections to ensure they are accurate and secure.

- Verify that the DHT library is installed in your Arduino IDE.

- If the readings seem incorrect, consider calibration or replacing the sensors.

## License

This project is licensed under the [MIT License](LICENSE).

---
