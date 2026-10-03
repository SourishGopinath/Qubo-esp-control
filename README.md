# QUBO ESP32 Control

ESP32-based control system integrating an IR sensor with a QUBO smart plug through MQTT.

## Project Status

Early development.

## Architecture

```text
IR Sensor
    │
    ▼
ESP32 GPIO
    │
    ▼
ESP32 Firmware
    │
    ├── Wi-Fi
    │
    └── MQTT
          │
          ▼
      MQTT Broker
          │
          ▼
      QUBO Smart Plug