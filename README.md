# Smart-car-parking-with-IOT-and-RFID

## Introduction
This project integrates IoT and RFID technology to create an efficient and automated car parking system. It uses RFID cards for user authentication, allowing access to the parking lot while logging entry details such as the person's name, time, and date into a Google Sheet. The system also leverages the Blynk app for real-time monitoring of parking slot availability and gate control. This smart solution enhances parking management by providing seamless automation, real-time tracking, and secure data logging.



## Features
- RFID-Based Detection: Automatic car detection using unique RFID tags/cards.
- IoT Integration: Real-time slot status display in the Blynk app and remote gate control.
- Google Sheets Logging: Uploads the RFID user's name, entry time, and date into a Google Sheet for record-keeping.
- Real-Time Monitoring: Displays parking slot availability on a 20x4 LCD display and the Blynk app.
- Entry Gate Control: Open and close the entry gate through the Blynk app.
- Full Slot Notification: Displays "All slots booked" message when parking is full.

## Technologies Used
### Hardware:
- ESP microcontroller 
- MFRC522 RFID module
- 20x4 LCD display
- Relay module for gate control
- Buzzer
- IR sensor
- lights
### Software:
- Arduino IDE
- Blynk App (for real-time control and monitoring)
- Google Sheets API (for logging user entry data)

## System Components
- Microcontroller: ESP32 
- RFID Reader: MFRC522 module for detecting RFID tags/cards.
- LCD Display: 20x4 I2C LCD for displaying available parking slots.
- Relay Module: Controls the entry gate via the Blynk app.
- Blynk App: Displays real-time slot status and provides remote control for the entry gate.
- Google Sheets: Logs RFID cardholder details (name, time, date) for tracking purposes.
- RFID Tags: Unique tags for each registered car/individual.
- IR Sensor Integration: Utilizes IR sensors to detect whether a parking slot is booked or empty.

## Screenshot
![1727534349082 (1)](https://github.com/user-attachments/assets/3c9264aa-9515-40c0-8df3-5d1051c481a6)
![1727534349178](https://github.com/user-attachments/assets/8b366ead-03f3-4670-b0f3-3ca0f9a7b11b)


