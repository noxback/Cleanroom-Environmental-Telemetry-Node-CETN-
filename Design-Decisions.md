## DD-001: Microcontroller Selection

Decision:
ESP32 DevKit V1

Alternatives Considered:
- Arduino Uno
- Arduino Nano Every

Reasoning:
The ESP32 provides integrated Wi-Fi, significantly more memory, faster processing, and is designed for IoT applications. Since this project will eventually transmit telemetry over a network, selecting the ESP32 avoids redesigning the hardware later.

Tradeoffs:
- Slightly steeper learning curve
- More GPIO and features than required for Version 1
