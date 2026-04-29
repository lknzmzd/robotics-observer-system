# Robotics Observer System

Servo-driven robotics system focused on real-time motion control, hardware integration, and expressive mechanical behavior.

---

## 🔹 System Overview

This project explores control and coordination of multiple servo motors to simulate responsive, lifelike motion using an embedded microcontroller (ESP32-C3).

The system is designed as a foundation for robotics interaction modules, combining hardware control, signal stability, and motion logic.

---

## 🔹 Hardware Architecture

- Microcontroller: ESP32-C3
- Actuators: SG90 Servo Motors (multi-axis control)
- Power: External power supply (required for stability)
- Additional Modules (planned/tested):
  - VL53L0X (distance sensor)
  - INMP441 (microphone)
  - BH1750 (light sensor)

---

## 🔹 System Flow

Input → Control Logic → PWM Signal → Servo Movement → Physical Response

---

## 🔹 Engineering Challenges

- Servo jitter caused by unstable power distribution
- Signal instability when controlling multiple servos
- Calibration drift after hardware modifications
- Limited GPIO/PWM control optimization on ESP32-C3

---

## 🔹 Solutions & Experiments

- Implemented external power supply for servo stability
- Manual recalibration of servo positions
- Tested PWM signal consistency across multiple channels
- Iterative tuning of motion behavior

---

## 🔹 Current Status

Prototype stage — actively developing control stability and motion coordination.

---

## 🔹 Media / Demonstration

(Add images / videos here)

---

## 🔹 Future Work

- Sensor-driven reactive behavior
- Improved motion synchronization
- Integration with higher-level control systems
