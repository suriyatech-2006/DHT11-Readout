# DHT11 Readout

**Author:** suriyakumar P

## Task

Interface a DHT11 sensor with an ESP32 and display temperature and humidity readings every 2 seconds.

## Components

- ESP32 DevKit V4
- DHT11 temperature and humidity sensor

## Connections

| DHT11 | ESP32 |
|---|---|
| VCC | 3V3 |
| DATA | GPIO 4 |
| GND | GND |

## Working

The ESP32 reads the DHT11 sensor every 2 seconds and displays the temperature and humidity values in the Serial Monitor.

## Serial Monitor

Set the Serial Monitor baud rate to **115200**.

Example output:

```
DHT11 Readout
Temperature: 24.0 °C
Humidity: 50.0 %
--------------------
```

## Wokwi

This project is designed to run in the Wokwi ESP32 simulator.
