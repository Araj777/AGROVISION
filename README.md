# AGROVISION
IOT based project used widely in Agriculture sector
Agrovision: IoT-Enabled Predictive Analytics for Modern Farming
Overview

Agrovision is an IoT-based smart agriculture system designed to improve farming efficiency using sensors, cloud computing, and machine learning. The project collects real-time environmental data such as soil moisture, temperature, humidity, and rainfall to help farmers make data-driven decisions.

The system provides:

Real-time monitoring
Crop recommendation
Automated irrigation support
Cloud-based analytics
Mobile/Web access for farmers
Features
🌱 Soil moisture monitoring
🌡 Temperature and humidity sensing
☁ Cloud-enabled IoT platform
📊 Data analytics and visualization
🤖 Machine learning-based crop prediction
📱 Mobile app integration using Blynk
🚨 Alert and notification system
💧 Smart irrigation using solenoid valve
Technologies Used
Hardware
Arduino Uno
NodeMCU ESP8266
DHT11 Temperature & Humidity Sensor
Soil Moisture Sensor
Solenoid Water Valve
Breadboard
Jumper Wires
Software
Arduino IDE
Blynk
Python
Flask
Machine Learning Libraries
System Architecture

The project consists of four major layers:

Sensor Layer
Collects environmental data from sensors.
Cloud Layer
Stores and processes collected data.
Analytics Layer
Performs machine learning predictions and recommendations.
Application Layer
Displays insights through web/mobile applications.
Dataset Information

The dataset contains:

2200 rows
8 columns
No missing values
Parameters
Nitrogen (N)
Potassium (K)
Temperature
Humidity
pH Value
Rainfall
Working Process
Sensors collect real-time farm data.
NodeMCU sends data to the cloud.
Data is cleaned and analyzed.
ML models generate predictions.
Recommendations are displayed to farmers.
Alerts are sent when irrigation is required.
Circuit Connections
Main Connections
DHT11 → NodeMCU D4
Soil Moisture Sensor → NodeMCU D3/A0
Relay Module → NodeMCU D0
Solenoid Valve connected through relay module
Installation
Requirements
Arduino IDE
ESP8266 Board Package
Blynk App
Python 3.x
Arduino Libraries

Install:

ESP8266WiFi
Blynk
DHT Sensor Library
DallasTemperature
OneWire
SimpleTimer

Running the Project
Step 1

Upload the Arduino code to NodeMCU using Arduino IDE.

Step 2

Configure Wi-Fi credentials and Blynk Auth Token.

Step 3

Open the Blynk application and start monitoring sensor data.

Testing

The project includes:

Functional Testing
Performance Testing
Data Accuracy Testing
Integration Testing
Security Testing

Advantages-
Real-time monitoring
Efficient water usage
Improved crop productivity
Reduced manual effort
Remote farm management

Challenges-
High installation cost
Internet connectivity issues
Sensor reliability in harsh environments
Data quality management

Future Scope-
Advanced deep learning models
Larger sensor networks
Improved mobile dashboard
Community-based farming analytics
Real-time weather integration

Conclusion-

Agrovision demonstrates how IoT and machine learning can modernize agriculture through automation, monitoring, and predictive analytics. The system improves farming efficiency, supports resource optimization, and enables smart decision-making for sustainable agriculture.

Authors-

Developed as a Smart Agriculture Major Project.

License-

This project is intended for educational and research purposes.
