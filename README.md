# IoT Based Patient Health Monitoring System using ESP8266 & ThingSpeak

## Introduction

This project implements an IoT-based Patient Health Monitoring System using ESP8266 and ThingSpeak. It allows monitoring of vital parameters such as room temperature, heartbeat, and blood pressure of a patient. The system utilizes sensors connected to an Arduino board, which communicates with the ThingSpeak platform via ESP8266 for data transmission. Users can monitor real-time data through a mobile application connected to the ThingSpeak channel.

## Components Used

- **ESP8266 Wi-Fi Module**: Enables internet connectivity for data transmission.
- **Arduino Board**: Processes sensor data and controls system operations.
- **Pulse Sensor**: Measures heartbeat (BPM) of the patient.
- **LM35 Temperature Sensor**: Monitors room temperature.
- **16x2 LCD Display**: Provides local display of vital parameters.
- **ThingSpeak**: IoT platform used for data storage, retrieval, and visualization.

## Setup Instructions

### Hardware Setup

1. **Connect Sensors**: 
   - Attach Pulse Sensor and LM35 Temperature Sensor to the designated pins on the Arduino board as per their datasheets.
   - Connect the 16x2 LCD Display to the Arduino board for local parameter display.

### Software Setup

1. **Arduino IDE Configuration**:
   - Upload the provided Arduino sketch (`filename.ino`) to the Arduino board.
   - Ensure the necessary libraries for sensors and LCD display are installed in the Arduino IDE.

2. **ThingSpeak Configuration**:
   - Create a ThingSpeak account if you do not have one.
   - Set up a new channel on ThingSpeak to receive data from the sensors.
   - Note down your ThingSpeak Channel ID and API Key.

3. **ESP8266 Configuration**:
   - Update the Wi-Fi credentials (`SSID` and `Password`) in the Arduino sketch to match your local network settings.
   - Enter your ThingSpeak Channel ID and API Key in the Arduino sketch for data transmission.

## Usage

1. **Power On**:
   - Power on the Arduino board and ensure all components are functioning properly.

2. **Data Monitoring**:
   - Use the ThingSpeak mobile application or web interface to monitor real-time patient health data.
   - The data will be updated automatically on your ThingSpeak channel, enabling remote monitoring from anywhere.

## Troubleshooting

- Verify all connections between components are secure and correctly wired.
- Check Wi-Fi connectivity of the ESP8266 module.
- Ensure correct setup of ThingSpeak channel ID and API Key in the Arduino sketch.
