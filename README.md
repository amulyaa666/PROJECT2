Fire Fighting Robot 🚒🤖
An autonomous Arduino-based robot designed to detect and extinguish small fires using flame sensors, IR obstacle detection, and a water pump system. Built as part of our Industry Oriented Mini Project in Electronics and Communication Engineering (2024–2025).

📜 Project Overview
Firefighters risk their lives in hazardous situations where fires occur in inaccessible or dangerous environments. This project aims to reduce that risk by developing an autonomous fire-fighting robot that detects fire, navigates toward it, and extinguishes it using water — all without human intervention.

The system uses:

Flame Sensors – Detect the presence and direction of fire.

IR Sensors – Detect obstacles and help in navigation.

Arduino Uno – Processes sensor data and controls movement and fire suppression.

DC Motors & Motor Driver (L293D) – Enable 4-wheel drive navigation.

Water Pump & Relay Module – Spray water on detected flames.

Servo Motor – Adjusts water nozzle direction for precise targeting.

⚙️ Features
✅ Autonomous fire detection & extinguishing
✅ 360° fire sensing with multiple flame sensors
✅ Obstacle detection and avoidance
✅ Low-cost, portable, and battery-powered
✅ Easy to customize and expand

🛠 Hardware Components
Arduino Uno (ATmega328P)

L293D Motor Driver Shield

Flame Sensors (x3)

IR Obstacle Sensor

Servo Motor (SG90/MG90S)

DC Motors (4-wheel drive)

Relay Module

12V DC Water Pump

Rechargeable Battery Pack (AX4444 / 4xAAA)

💻 Software & Tools
Arduino IDE – Programming the microcontroller

AFMotor & Servo Libraries – Motor and servo control

Embedded C/C++ – Logic implementation

🔄 Working Principle
Initialization – All components (motors, sensors, servo) are activated.

Fire Detection – Flame sensors detect the fire’s direction.

Navigation – Robot moves toward the fire, avoiding obstacles using IR sensors.

Extinguishing – Relay activates the water pump to spray water until the fire is out.

Monitoring – Continues scanning for reignition or new fire sources.

📊 Applications
Homes, offices, and classrooms

Laboratories & server rooms

Industrial safety in hazardous areas

Educational robotics & STEM projects

🚀 Future Improvements
Add AI/ML for fire pattern recognition

Integrate IoT for remote monitoring & control

Use thermal cameras for enhanced detection

Implement GPS/SLAM for large-scale navigation
