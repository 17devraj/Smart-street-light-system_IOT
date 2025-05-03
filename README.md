Smart Street Light System (IoT)
An intelligent street lighting solution developed as part of my academic project, aiming to enhance energy efficiency and public safety. The system utilizes motion detection and ambient light sensing to control street lights dynamically, ensuring illumination only when necessary.

🚀 Features
Motion Detection: Street lights activate upon detecting movement, conserving energy during inactivity.

Ambient Light Sensing: Lights adjust based on surrounding light conditions, ensuring optimal brightness.

Automated Control: Eliminates the need for manual operation, reducing maintenance efforts.

User-Friendly Interface: Frontend allows monitoring and control of the lighting system.

🛠️ Technologies Used
Hardware: ESP32 microcontroller, PIR motion sensors, LDR (Light Dependent Resistor), LEDs.

Software: C++ for microcontroller programming, HTML/CSS/JavaScript for frontend development.

📁 Project Structure
css
Copy
Edit

Smart-street-light-system_IOT/
├── Frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
└── Main.ino
Frontend/: Contains the web interface for the lighting system.

Main.ino: Core logic programmed in C++ for the ESP32 microcontroller.
GitHub
+2
GitHub
+2
GitHub
+2

⚙️ Setup Instructions
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/17devraj/Smart-street-light-system_IOT.git
Hardware Setup:

Connect PIR sensors and LDRs to the ESP32 as per the circuit diagram.

Ensure LEDs are connected to appropriate GPIO pins.

Upload Firmware:

Open Main.ino in the Arduino IDE.

Select the correct board and port.

Upload the code to the ESP32.

Launch Frontend:

Open index.html in a web browser to access the control interface.

🔧 Future Enhancements
Remote Monitoring: Integrate with cloud services for real-time monitoring.

Mobile Application: Develop a mobile app for on-the-go control.

Energy Analytics: Implement analytics to track energy savings and performance.
GitHub

📷 Screenshots
Include images of the hardware setup and frontend interface here.

👨‍💻 Author
Dev Parmar

GitHub: 17devraj

LinkedIn: Your LinkedIn Profile

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
