# Home Automation System
The project involves creating a home automation system using Arduino, a popular open-source electronics platform. This system is designed to manage two main functions: lighting control and gate operation.

For lighting control, the system allows users to remotely manage and schedule the lighting in their home. This means they can turn lights on or off, adjust brightness levels, and set up automated schedules for when lights should be on or off, all from a remote location.

The gate operation aspect of the system enables users to remotely open or close their gate. This can be particularly useful for security purposes or for convenience, allowing users to grant access to visitors even when they're not physically present.

This system enables remote control of two relay-connected devices labeled as light1 and light2, accessible through the Blynk mobile app.
Additionally, a Wi-Fi LED indicator (wifiLed) signifies the status of the Wi-Fi connection. Users can toggle each relay on or off via virtual buttons within the app, activating the corresponding device when pressed and deactivating it upon release. To set up the system, the ESP8266 connects to the home Wi-Fi network and the Blynk server, establishing communication with the Blynk app through a designated authentication token. While this code serves as a fundamental framework for home automation, practical solutions may encompass more advanced features such as sensor integration, scheduling, security measures, and voice control. Deploying a comprehensive home automation system necessitates careful consideration of factors including security, reliability, scalability, and user accessibility. Incorporating safety precautions and fail-safes is imperative, particularly when managing high-power electrical devices, to mitigate potential risks. Ultimately, home automation systems present opportunities for enhanced convenience, energy efficiency, and remote monitoring, contributing to the modernization and comfort of living spaces, albeit requiring diligent implementation to ensure a seamless and secure user experience.

User requirements : 
•	Arduino Nano Board 
•	Servo Motor
•	Passive Infrared (PIR) Motion Sensor
•	Jumper Wires (male-to-male and male-to-female)
•	ESP8266 NodeMcu
•	2 way relay module
•	Bread board
•	230v bulbs


