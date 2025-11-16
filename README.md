Auto Rain Shield for Clothes

📌 Project Overview

Auto Rain Shield for Clothes is an Arduino-based automation system designed to protect clothes drying outdoors during unexpected rain. The system continuously monitors rainfall using a rain-detection sensor and automatically slides a protective cover over the clothes using a motor-driven rack-and-pinion mechanism. When the rain stops, the cover retracts automatically.

This project demonstrates practical use of embedded systems, sensor integration, and motor control to solve a real-world household problem.


🛠 Components Used

Arduino Uno

Rain Detection Sensor Module

L298N Motor Driver

5V DC Motor

Rack and Pinion Mechanism

Jumper Wires

Breadboard

Power Supply


⚙️ Working Principle

1. The rain sensor constantly monitors moisture levels.


2. When rain is detected, it sends a signal to the Arduino.


3. Arduino activates the L298N motor driver.


4. The motor rotates the rack-and-pinion mechanism to slide the protective cover over the clothes.


5. When the rain stops, the system reverses the motor to retract the shield.


6. The entire process runs automatically without any human intervention.





🔧 Technical Highlights

Real-time rain detection using analog/digital thresholding.

Bidirectional motor control using L298N H-bridge.

Mechanical automation using a rack-and-pinion setup.

Fully autonomous behavior with simple, reliable electronics.

Energy-efficient and low maintenance design.


📐 Block Diagram

Rain Sensor --> Arduino Uno --> L298N Motor Driver --> DC Motor --> Rack & Pinion Cover


📂 Applications

Automated cloth drying systems

Smart home automation

Weather-responsive mechanisms

DIY home improvement projects


🚀 Future Scope

Mobile app notifications (rain alert).

Solar-powered system for outdoor setup.

Integration with IoT platforms (Blynk / MQTT).

Waterproof enclosure for long-term outdoor use.
