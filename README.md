# Home Automation System
## Introduction
The project involves creating a home automation system using Arduino, a popular open-source electronics platform. This system is designed to manage two main functions: lighting control and gate operation.

#### For lighting control, the system allows users to remotely manage and schedule the lighting in their home. This means they can turn lights on or off, adjust brightness levels, and set up automated schedules for when lights should be on or off, all from a remote location.

#### The gate operation aspect of the system enables users to remotely open or close their gate. This can be particularly useful for security purposes or for convenience, allowing users to grant access to visitors even when they're not physically present.

## System Overview
This system enables remote control of two relay-connected devices labeled as light1 and light2, accessible through the Blynk mobile app.
Additionally, a Wi-Fi LED indicator (wifiLed) signifies the status of the Wi-Fi connection. Users can toggle each relay on or off via virtual buttons within the app, activating the corresponding device when pressed and deactivating it upon release. To set up the system, the ESP8266 connects to the home Wi-Fi network and the Blynk server, establishing communication with the Blynk app through a designated authentication token. While this code serves as a fundamental framework for home automation, practical solutions may encompass more advanced features such as sensor integration, scheduling, security measures, and voice control. Deploying a comprehensive home automation system necessitates careful consideration of factors including security, reliability, scalability, and user accessibility. Incorporating safety precautions and fail-safes is imperative, particularly when managing high-power electrical devices, to mitigate potential risks. Ultimately, home automation systems present opportunities for enhanced convenience, energy efficiency, and remote monitoring, contributing to the modernization and comfort of living spaces, albeit requiring diligent implementation to ensure a seamless and secure user experience.

## User requirements : 
•	Arduino Nano Board 
•	Servo Motor
•	Passive Infrared (PIR) Motion Sensor
•	Jumper Wires (male-to-male and male-to-female)
•	ESP8266 NodeMcu
•	2 way relay module
•	Bread board
•	230v bulbs

# How It Works

## 1. System Setup

### Hardware Connections:
Connect the Arduino Nano board to the relay module, PIR motion sensor, and servo motor.
Use jumper wires to establish connections on the breadboard.
Connect the ESP8266 NodeMCU to the Arduino Nano for Wi-Fi connectivity.
Ensure 230V bulbs are properly connected to the relay module.

### Wi-Fi and Blynk Setup:
The ESP8266 connects to your home Wi-Fi network and the Blynk server using a designated authentication token.
The Wi-Fi LED (wifiLed) will indicate the status of the Wi-Fi connection (on when connected, off otherwise).

## 2. Lighting Control
### Remote Management:
Use the Blynk mobile app to toggle the relays controlling light1 and light2.
Virtual buttons in the app allow you to turn lights on or off and adjust their brightness.
Scheduling:
Set up schedules in the Blynk app to automate lighting based on time of day or other conditions.
## 3. Gate Operation
### Remote Control:
The servo motor connected to the relay module controls the gate.
Use the Blynk app to open or close the gate remotely.

### Motion Detection:
The PIR motion sensor detects movement.
Integrate the sensor with the system to trigger the gate operation based on motion.

# Usage
### Controlling Lights:

Open the Blynk app on your mobile device.
Use the virtual buttons to turn light1 or light2 on or off.
Adjust brightness levels as needed.
### Managing the Gate:

Access the Blynk app to open or close the gate remotely.
Ensure the servo motor is correctly aligned with the gate mechanism.

