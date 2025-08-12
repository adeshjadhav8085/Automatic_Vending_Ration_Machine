The Automatic Ration Vending Machine is an embedded system designed to automate the distribution of ration to registered users using fingerprint authentication. The system controls a servo motor for dispensing grains, a relay-operated pump for liquids, and logs every transaction to ThingSpeak for monitoring and analysis.
This project aims to reduce manual intervention, prevent ration fraud, and provide transparent distribution records.

Features:
Biometric Authentication – Fingerprint sensor to identify registered users.
Automated Dispensing – Servo motor for solid ration, relay pump for liquids.
IoT Data Logging – Real-time data upload to ThingSpeak.
LCD Display Interface – User guidance during the process.
Low-Cost & Scalable – Designed using readily available components.

Hardware Requirements:
ATmega328P 
Fingerprint Sensor
Servo Motor
Relay Module
Water Pump
LCD Display with I2C module
Power Supply
Breadboard, jumper wires, resistors

Software Requirements:
Arduino IDE
ThingSpeak account & API key
Arduino Libraries:
a)Adafruit_Fingerprint
b)Servo.h
c)LiquidCrystal_I2C
d)ThingSpeak

