CAN-Based Automotive Dashboard

📌 Project Overview

This project implements a CAN (Controller Area Network) based automotive dashboard to simulate real-time monitoring of vehicle parameters. It demonstrates reliable inter-ECU communication using the CAN protocol, which is widely used in modern automotive systems.

The dashboard receives CAN messages representing various vehicle parameters and updates them dynamically, simulating real-world automotive behavior.

🎯 Objectives

Understand CAN protocol fundamentals

Implement inter-ECU communication

Simulate real-time automotive dashboard behavior

Gain hands-on experience in embedded C and automotive systems

⚙️ Features

CAN-based communication between multiple nodes

Real-time display of vehicle parameters:

Vehicle Speed

Engine Temperature

Fuel Level

CAN message transmission and reception

Error detection and reliable communication

Scalable architecture for adding more ECUs

🛠️ Technologies Used

Embedded C

CAN Protocol

Microcontroller with CAN support

CAN controller and transceiver

Embedded development tools (Keil / MPLAB / Arduino IDE – based on setup)

🧩 System Architecture

Multiple CAN nodes act as vehicle subsystems

Each node sends sensor data via CAN frames

A dashboard controller receives and processes CAN messages

Dashboard updates values in real time based on received data

🚀 How It Works

CAN bus is initialized with proper bit timing

Each ECU transmits data using unique CAN identifiers

Dashboard node filters and decodes messages

Parameters are updated dynamically on the dashboard

Error handling ensures reliable communication

📂 Project Structure
CAN-Based-Automotive-Dashboard/
│
├── src/            # Source code files
├── inc/            # Header files
├── config/         # CAN configuration files
├── README.md

📈 Learning Outcomes

Practical understanding of automotive communication protocols

Experience with real-time embedded programming

Knowledge of CAN message framing, filtering, and debugging

Foundation for automotive embedded software roles

🔮 Future Enhancements

Add more vehicle parameters

Integrate CAN diagnostics

Support extended CAN IDs

Hardware dashboard display integration

👩‍💻 Author

N. K. Vaishnavi
Embedded Systems Enthusiast | Automotive Domain
