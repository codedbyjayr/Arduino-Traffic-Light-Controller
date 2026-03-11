# Arduino-Traffic-Light-Controller
A precision-timed signaling system built with Arduino, simulating a real-world four-way intersection. This project demonstrates core embedded systems concepts, including digital I/O handling, timing loops, and state machine logic.
🛠️ Features
Standard Signaling Logic: Accurate Green-Yellow-Red transitions with industry-standard delays.

Safety Interlocks: Logic-level checks to ensure "conflicting greens" (North-South vs. East-West) are physically impossible in the code.

Visual Feedback: High-brightness LED indicators for clear status monitoring.

Modular Code: Clean, documented functions for setNorthSouth() and setEastWest() to allow for easy scaling to 8-way intersections.

🧱 Components Used
Microcontroller: Arduino Uno / Nano

LEDs: 6x (2 Red, 2 Yellow, 2 Green)

Resistors: 220Ω (to protect the LEDs)

Breadboard & Jumper Wires
