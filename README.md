# esp32-rs485-pump-control
Control for Inverter Pool Pump over RS485

Used to take control over a Aquagem InverPro IP30 via a esp32 and TTL to RS485 adapter. 
Sets ON/OFF and capacity. Shows status, pressure, flowrate, power, energy, errors ...
Needs (Home Assistant) ESPHome to compile . Currently values are send to MQTT server.

## Disclaimer
testet only on my InverPro - Use at your own risk.

## Hardware
ESP32 Dev Board
TTL to RS485 Modul (works with auto direction detection too)

## ESPHome Configuration
put pool-control as new Device in your setup
edit ssid / password and mqtt server address
optional: add api for home assistant

