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

## Sample UI

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/616024bd-058a-47d3-a434-4121d9433109" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/176aaadc-85db-4efa-91b2-b16e6b2715b1" />

