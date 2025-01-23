# Secure Smart Home System using STM32
## Contributors
- **Saimum Reza Siam**
- **Fahim Nahar Shaily**
- **Md. Adnan Hossain Sadi**
- **Mehrab Muhtasim Sayem**

This project implements a secure and scalable IoT-based smart home system using the STM32F446RE microcontroller. It aims to address security and privacy concerns in modern IoT systems while ensuring seamless control and monitoring of connected devices.

## Features
- **Environmental Monitoring:** Collects data from sensors like air quality, temperature, humidity, and power usage.
- **Device Control:** Allows remote control of home appliances via a web or mobile app.
- **Intruder Detection:** Identifies suspicious activities to enhance home security.
- **Data Communication:** Utilizes MQTT and HTTP protocols for secure data exchange and remote monitoring.
- **Data Storage:** Logs data locally using an SD card.

## Components and Sensors
- **STM32F446RE Microcontroller**
- **Air Quality Sensor (Grove v1.3)**
- **DHT11 Temperature & Humidity Sensor**
- **PZEM004T Power Module**
- **Serial Camera Module**
- **SD Module**
- **Relay Module**
- **W5300 Ethernet Controller**

## Communication Protocols
- **UART:** For data exchange with the PZEM004T Power Module and Serial Camera.
- **FMC:** For high-speed Ethernet communication via the W5300 controller.
- **GPIO:** For control signals to devices like relays and DHT11 sensor communication.
- **ADC:** For processing analog signals from sensors like the air quality sensor.
- **MQTT:** For efficient IoT messaging.
- **HTTP:** For transferring images and data to the app.

## System Design
The system is built to:
1. Interface multiple sensors and modules with STM32.
2. Collect and process data efficiently.
3. Provide a user-friendly remote control interface via mobile or web apps.
4. Ensure system security through robust communication protocols and error handling.

## How to Run
1. **Hardware Setup:**
   - Connect all sensors and modules as per the schematic provided in the documentation.
2. **Software Setup:**
   - Flash the STM32 microcontroller with the provided firmware.
   - Configure the MQTT broker and HTTP server details in the code.
3. **Run the Application:**
   - Use the web or mobile app to monitor and control the system remotely.

Feel free to contribute to this project or suggest improvements by opening an issue or submitting a pull request!
