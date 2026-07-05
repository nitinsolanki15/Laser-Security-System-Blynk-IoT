# Laser-Security-System-Blynk-IoT🚀
It's the basic laser security which detects the intruder ...

# Laser Security System with ESP32 and Blynk IoT

A laser-based intrusion detection system developed using ESP32 and Blynk IoT. The system continuously monitors a laser beam using an LDR sensor. If the beam is interrupted, an alarm is activated and a notification is sent through Blynk IoT.

---

## Features✨

- Laser Beam Detection
- Intruder Detection
- ESP32 Based
- Blynk IoT Integration
- Email Notification
- Push Notification
- Alarm Count
- Arm / Disarm System
- Real-Time Status Monitoring

---

## Hardware Required🛠️

- ESP32 Dev Board
- Laser Module
- LDR Module
- LED
- Active Buzzer
- Breadboard
- Jumper Wires
- USB Cable

---

## Software Required🖥️

- Arduino IDE
- ESP32 Board Package
- Blynk IoT
- Blynk Library

---

## Pin Connections📌

| Component | ESP32 Pin |
|-----------|-----------|
| LDR OUT | GPIO27 |
| LED | GPIO14 |
| Buzzer | GPIO21 |

---

## Blynk Datastreams💾

| Virtual Pin | Type | Purpose |
|-------------|------|---------|
| V0 | String | System Status |
| V1 | Integer | Alarm LED |
| V2 | Integer | LDR Value |
| V3 | Integer | Arm / Disarm |
| V4 | Integer | Alarm Count |

---

## Working Principle🌟

1. Laser continuously falls on the LDR.
2. ESP32 monitors the sensor.
3. If laser beam is interrupted:
   - LED turns ON
   - Buzzer turns ON
   - Blynk status changes to INTRUDER
   - Alarm count increases
   - Push notification is sent
   - Email notification is sent
4. When the beam is restored, the alarm stops and the status changes to SAFE.

---

## Blynk Dashboard📟

The dashboard contains:

- Status Label
- LED Indicator
- LDR Value Gauge
- Arm/Disarm Switch
- Alarm Counter

---

## Future Improvements📈

- ESP32-CAM Integration
- Telegram Bot Notification
- Firebase Database
- GSM SIM800L Support
- Cloud Data Logging
- Mobile App

---

## Author🙌

Nitin Solanki
<br>
B.Tech ECE Student
