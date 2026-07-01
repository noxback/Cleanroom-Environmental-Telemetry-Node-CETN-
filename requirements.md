# System Requirements

## Purpose

Design and develop an embedded environmental monitoring device capable of measuring, displaying, and eventually transmitting environmental data representative of conditions found within industrial cleanroom environments.

---

# Functional Requirements

## FR-1 Environmental Monitoring

The system should measure:

- Temperature
- Relative Humidity
- Atmospheric Pressure

---

## FR-2 Data Display

The system shall display sensor measurements locally using an OLED display.

Display update rate:

- 1 Hz

---

## FR-3 Continuous Operation

The system shall continuously collect sensor data while powered.

---

## FR-4 Expandability

The hardware shall allow future integration of additional sensors including:

- VOC
- CO₂
- Particulate Matter
- Differential Pressure

---

## FR-5 Documentation

All hardware revisions, firmware revisions, and design decisions shall be documented within the GitHub repository.

---

# Performance Requirements

## PR-1 Sampling Rate

Sensor values shall update once every second.

---

## PR-2 Reliability

System shall operate continuously for at least 24 hours without software failure.

---

## PR-3 Accuracy

Sensor accuracy shall match published manufacturer specifications.

---

# Design Constraints

Maximum project cost:
$100 (Version 1)

Development Platform:
Arduino Framework

Programming Language:
C++

Power Source:
USB

---

# Future Requirements

Version 2
- Wi-Fi communication
- MQTT telemetry
- Data logging

Version 3
- Custom PCB
- Battery operation
- Enclosure

Version 4
- SCADA integration
- Alarm outputs
- Calibration procedure

---

# Success Criteria
The project will be considered successful when it can:

✓ Collect environmental measurements
✓ Display live measurements
✓ Operate continuously
✓ Produce documented engineering results
✓ Support future expansion through modular hardware and software design
