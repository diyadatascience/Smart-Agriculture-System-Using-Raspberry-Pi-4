# Smart Agriculture System Using Raspberry Pi 4
This repository contains the Python code and presentation for a soil moisture monitoring system utilizing a Raspberry Pi 4. The project leverages the power of Raspberry Pi and its GPIO capabilities to interface with a soil moisture sensor. The goal of this system is to automate the process of soil moisture detection, providing real-time feedback on water levels in the soil, which is crucial for optimal plant growth.

# Project Overview
The system continuously monitors the soil moisture levels, employing a straightforward mechanism involving a moisture sensor connected via an MCP3008 to the Raspberry Pi. Based on the readings from the sensor, the system activates a red LED to indicate a dehydration state, or a green LED to signal sufficient moisture. This visual feedback is an essential feature for managing irrigation in a variety of settings, from agricultural fields to domestic gardens.

# Components
Raspberry Pi 4
4 Amp Power Adapter
8GB micro-SD Card
Jumper Wires
Soil Moisture Sensor
LED Lights (Red and Green)

# How It Works
Setup: Configure the Raspberry Pi GPIOs to read from the moisture sensor and control the LEDs.
Detection: The moisture sensor checks the soil and sends the data to the Raspberry Pi.
Feedback: Depending on the moisture level, appropriate LEDs are triggered to visually represent the soil's moisture state.
Loop: The system continually checks every second, updating the status based on the latest moisture readings.
Why Monitor Soil Moisture?
Efficient water management is essential in agriculture. Understanding soil moisture in real time helps in optimizing irrigation, leading to better crop health and reduced water wastage. This project contributes to sustainable farming practices by providing essential data that can be used to improve irrigation schedules and methods.

This repository includes all the necessary code and a comprehensive PowerPoint presentation detailing the setup and functionality of the system, making it accessible for anyone interested in DIY electronics or smart farming solutions.

# Files attached 
GPIO code.ipynb: Jupyter notebook with Python code for soil moisture monitoring.
Raspberry Pi Project.pptx: Presentation detailing the Raspberry Pi soil moisture system.


