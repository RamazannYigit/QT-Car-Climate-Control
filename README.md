# QT-Car-Climate-Control
**QT Car Climate Control with PCAN Integration**

This project implements an advanced car climate control system using the QT framework, integrated with PCAN (CAN bus) communication for real-time data exchange with the vehicle's systems.

## Project Overview
The QT Car Climate Control application provides a sophisticated interface for monitoring and controlling a vehicle's climate system. It utilizes PCAN (Peak CAN) hardware for bidirectional communication with the car's CAN bus, allowing real-time data acquisition and control of various climate parameters.

## Features
- Real-time temperature control and monitoring  
- Fan speed adjustment with multiple levels  
- Air direction settings (face, feet, defrost)  
- Auto mode for optimal climate management  
- Integration with vehicle's CAN bus via PCAN  
- Data logging and visualization of climate parameters  
- User-friendly GUI designed with QT

## Technical Details

### PCAN Communication:
- Receives real-time data from car sensors (temperature, humidity, etc.)
- Sends control commands to adjust climate settings
- Implements error handling and data validation for robust operation

### QT Framework:
- Utilizes QT for creating a responsive and intuitive user interface
- Implements multi-threading for smooth UI performance during data processing

### Data Processing:
- Real-time parsing and interpretation of CAN messages
- Algorithmic control for maintaining desired climate conditions

## Technologies and Tools
- QT Framework
- C++
- PCAN-Basic API
- CAN bus protocol
- Git for version control

## Setup and Installation
Follow these steps to set up and run the project:

1. **Required Software:**
   - QT
   - Git
   - PCAN-Basic API
2. Install these software on your computer.
3. Clone the project:
4. Open QT Creator.
5. Click on "Open Project" within QT Creator.
6. Select and open the `CMakeLists.txt` file in the downloaded project folder.
7. QT Creator will validate and load all project files to your screen.
8. You can now compile and run the project.

## Usage
1. Connect the PCAN device to the vehicle.
2. Launch the application.
3. In the application interface, click on the button or option corresponding to the action you want to perform.
4. The selected action will be sent as data to the vehicle through the PCAN device.

**Note:** The bytes and IDs of incoming or outgoing data from the PCAN device may vary depending on your vehicle or system. Therefore, you may need to examine the code content and make necessary adjustments to adapt the application to your system.
