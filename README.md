# GridSentinel Prototype

A self-contained dashboard prototype for an AI-powered transformer monitoring system.

## Run
Open `index.html` in any modern browser.

## Demo
Click **Simulate Fault** to demonstrate:
- transformer health degradation
- failure-risk increase
- AI fault classification
- AI explanation
- recommended protective action

Click **Reset System** to return to normal operation.

## Hardware integration path
Replace the simulated JavaScript values with ESP32 sensor data delivered through MQTT/LoRa/HTTP.

Suggested deployment:
ESP32-S3 + current sensor + temperature sensor + vibration sensor -> Edge AI -> MQTT/LoRa -> backend -> dashboard.

Note: all dashboard values in this prototype are simulated and are not real grid measurements.
