# EV-Dashboard-PFE
Digital dashboard for a 3-wheel electric vehicle (EV).  
The system provides **real-time monitoring and control** of the vehicle, including motor, sensors, and cameras, with a user-friendly interface on a 7-inch touchscreen.

## Objectives
- Display speed, battery status, and motor status.
- Monitor sensors and control actuators via STM32.
- Integrate camera-based ADAS (Advanced Driver Assistance System) for safety.
- Provide a visual and interactive GUI for the driver.

## Technologies
- **Qt & QML** – Graphical User Interface
- **Python & OpenCV** – Camera capture and processing
- **STM32** – Motor and sensor control
- **Jetson Nano** – Interface processing
- **Machine Learning / AI** – ADAS model to detect speed limits and vehicles in front

## Architecture
![System Diagram](images/System.PNG)
*Diagram showing STM32, Jetson Nano, cameras, and dashboard interaction.*

## Features
- Real-time vehicle monitoring (speed, battery, motor status)
- Camera-based ADAS:
  - Detects **speed limits** from road signs
  - Detects **vehicle in front**
  - Provides **warning signals** to the driver
- Interactive GUI for touch screen control
- Data logging and visualization

## Screenshots
![Dashboard Screenshot](images/MainGUI.png)

![Dashboard Screenshot](images/30Adas.png)

*Screenshot of the dashboard in action.*
## opening camera while backward 
![Dashboard Screenshot](images/rrrr.png)


## Results
- Real-time vehicle monitoring and control.
- Successfully integrated STM32 and Jetson Nano systems.
- Fully functional GUI for user interaction.

## Demo
![Demo Result](images/Demo)

## ADAS Detection Capture
![ADAS Capture](images/Model.PNG)  
*Placeholder for AI model detection: speed limit and vehicle ahead.*


## Achievements
- Fully functional dashboard integrated with EV systems
- AI model successfully detects speed limits and vehicles ahead
- Real-time interaction between STM32, Jetson Nano, and GUI
