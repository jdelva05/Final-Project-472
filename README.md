# Fall Detection System Project Report

# Project Goals

The primary objective of this project is to develop a Fall Detection System using Python and its tkinter library. The system aims to monitor and alert users in real-time in the event of a fall. This application is particularly relevant for ensuring the safety of vulnerable groups such as the elderly or individuals with health conditions that increase their risk of falls.

# Significance of the Project

Falls are a major health risk, especially for older adults, leading to severe injuries and even fatalities. This project is significant because it provides a proactive solution to detect falls, ensuring timely assistance and potentially saving lives. By offering peace of mind to users and their caregivers, the system contributes significantly to the overall happiness and well-being of its users.

# Installation and Usage Instructions

Installation:
- Prerequisites: Python environment with tkinter library (usually included in standard Python installations).
- Website: https://www.jetbrains.com/pycharm/<br>
- Running the Application: Execute the script in a Python environment.<br>
1. Open Pycharm and click "Get from VCS"<br>
   <img width="800" alt="Screenshot 2023-12-03 at 9 46 29 PM" src="https://github.com/redbolt101/Final-Project-472/assets/132689188/698defb3-cad7-4f8f-8727-e2112e34d506">
 2. Copy this link: https://github.com/redbolt101/Final-Project-472.git, next paste in URl, then hit clone
    <img width="802" alt="Screenshot 2023-12-03 at 9 48 14 PM" src="https://github.com/redbolt101/Final-Project-472/assets/132689188/da5d62b4-e25b-4012-9584-4ab9ba2c5fd4">
    
3. Once project open click on main.py file
   <img width="379" alt="Screenshot 2023-12-03 at 9 49 06 PM" src="https://github.com/redbolt101/Final-Project-472/assets/132689188/6c37e6c8-c0a6-43c4-8026-3d2574c519f3">

4. Then run hit the green triangle on the top to rum program
   <img width="1440" alt="Screenshot 2023-12-03 at 9 49 42 PM" src="https://github.com/redbolt101/Final-Project-472/assets/132689188/dad7505e-008b-47ac-94ab-7e5608b8e7a4">

5. Finally the program will run displaying an alert with a log of time and date of fall
   <img width="1111" alt="Screenshot 2023-12-03 at 9 51 11 PM" src="https://github.com/redbolt101/Final-Project-472/assets/132689188/d411f011-d79a-4133-9155-7f6cef59ee0f">


- Usage:<br>
On running the script, a GUI titled "Fall Detection System" appears.<br>
The system automatically begins monitoring for falls.<br>
In the event of a fall (simulated randomly in this version), an alert is displayed with the time of the incident.
  <img width="1111" alt="Screenshot 2023-12-03 at 9 51 11 PM" src="https://github.com/redbolt101/Final-Project-472/assets/132689188/1241662b-9ad8-44cb-96cb-54713943179d">


# Code Structure

The script is organized into several key parts:

Imports: Necessary Python modules like tkinter, random, threading, time, and datetime.
Main Function create_fall_detection_gui(): Sets up the GUI and the fall detection mechanism.
Initializes the main window.
Defines a function to display fall detection alerts.
Implements a background process to simulate continuous monitoring.
Initiates the GUI event loop.

# List of Functionalities and Test Results

Functionalities:
Real-time monitoring for fall detection.
Alert system with timestamped notifications.
A log of detected fall events.
Test Results:
Reliability: The detection (simulated) was consistently identified.
Responsiveness: The GUI promptly displayed alerts post-detection.
Accuracy: Timestamps in alerts matched the system's current time.

# Discussion and Conclusions

This project integrates fundamental concepts of GUI development, multithreading, and event handling. It demonstrates practical application in a real-world context, albeit with a simulated detection mechanism.

Limitations:
The fall detection is currently random and does not reflect real-world conditions.
Potential challenges include integrating real sensors and managing GUI responsiveness under different system loads.

Conclusion:
The project serves as a foundational step towards creating a practical fall detection system. Future enhancements could include integrating real-time sensors for accurate detection and improving the GUI for added functionalities like emergency contacts. This project effectively showcases the application of course learnings in developing a potentially life-saving application.
The random simulation of falls, which does not represent real-world scenarios accurately.
Potential delays in GUI response due to threading.
Improvements could include integrating real-time sensors for accurate fall detection and enhancing the user interface for better user experience and functionality, such as adding an emergency contact system.
