# ESP32 Pin Configuration

| Device | Pin | ESP32 |
|---|---|---|
| Soil Moisture | AO | GPIO34 |
| DHT22 | DATA | GPIO4 |
| BH1750 | SDA | GPIO21 |
| BH1750 | SCL | GPIO22 |
| OLED | SDA | GPIO21 |
| OLED | SCL | GPIO22 |
| Relay | IN | GPIO26 |
| RGB LED | Red | GPIO25 |
| RGB LED | Green | GPIO27 |
| RGB LED | Blue | GPIO14 |

## Power

Sensors should be powered according to their module specifications.

The 12V pump must use an external 12V power supply.

Do not connect the 12V pump directly to the ESP32.
