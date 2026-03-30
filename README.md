# Robotic Arm Project 🤖

This repository contains the code and demonstration for a custom-built robotic arm. 

## 🎥 Video Demonstration
https://drive.google.com/drive/folders/1LBjvRVyuUAkUJt3Xkj5hFIh4rOBZWmnl?usp=sharing

## 🛠️ Hardware Used
* Microcontroller (Arduino Uno)
* Servo Motors (SG90)
* Power Supply module
* Jumper wires & Breadboard

## ⚙️ How It Works
This project explores the fundamentals of robotics, kinematics, and serial communication through the development of a custom-built, two-degree-of-freedom (2-DOF) robotic arm. Designed as a functional prototype for automated material handling, the arm is constructed using a lightweight, sustainable frame of ice cream sticks and high-torque servo motors. The system is controlled via an Arduino microcontroller, demonstrating how entry-level hardware can be used to achieve precise mechanical actuation.

Technical Architecture & Design
The mechanical structure utilizes a 2-axis configuration to manage vertical reach and gripping capabilities. While the initial design allowed for base rotation (X-axis), the current iteration focuses on optimized stability for "pick and place" operations.

Actuation: The arm is powered by two servo motors, which provide the necessary torque to lift small objects and maintain positions without the need for complex external braking systems.

Control Logic: The system uses a specialized Arduino sketch that maps user keyboard inputs to specific pulse-width modulation (PWM) signals. This allows for real-time manual control through the Serial Monitor, where the user can trigger "Up," "Down," "Pick," and "Drop" commands instantly.

Prototyping Strategy: By using accessible materials like ice cream sticks, the project emphasizes rapid prototyping and structural Iteration, allowing for quick adjustments to the arm’s center of gravity and reach.

Key Achievements
Successfully implemented a stable mechanical linkage system using basic materials.

Developed a responsive serial interface for manual coordinate control.

Calibrated servo angles to ensure smooth transition states and prevent mechanical binding.

Future Development & Computer Vision
The next phase of this project involves transitioning from manual serial control to AI-driven gesture recognition. By integrating a laptop webcam and the MediaPipe library, the goal is to enable the robotic arm to mirror human hand movements in real-time. This upgrade will move the project from a static controller model to a dynamic, vision-based robotics system, significantly increasing the complexity of the software stack and user interaction.
## 🚀 How to Run
1. Wire the components according to the circuit diagram.
2. Open the `.ino` file in the Arduino IDE.
3. Install the required Servo libraries.
4. Select the correct board and COM port.
5. Upload the code and power up the servos!

