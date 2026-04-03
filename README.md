# BiTechX: Smart Medication Dispenser

## Overview

Millions of people living with chronic conditions require continuous monitoring and timely medication — yet many elderly individuals and patients struggle with remembering schedules, keeping up with appointments, or responding to unexpected health changes. BiTechX bridges the gap between patients, caregivers, and physicians by delivering an intelligent, connected health management system built on wearable technology, IoT, and smart automation.

---

## Key Features

**Automated Medication Dispenser**
Uses NFC-based identification to ensure patients receive the correct medication at the right time, significantly reducing missed or incorrect doses.

**Companion Mobile Application**
Connects patients, caregivers, and physicians in a shared real-time environment — enabling health tracking, medication updates, and appointment reminders from a single interface.

---

## Objectives

- Ensure patients never miss a scheduled dose.
- Reduce unnecessary hospital visits through proactive remote monitoring.
- Improve quality of life for patients and their caregivers alike.

---

## System Architecture

### Automated Dispenser and Multiplexer Control
The dispenser employs a multiplexer system to manage multiple medication sectors independently. Activation is triggered through sensor inputs, ensuring precise and reliable dosing for each compartment.

### Sensor Integration

| Sensor | Function |
|--------|----------|
| IR Sensor | Detects object presence to ensure safe dispenser operation |
| Laser Sensor | Monitors dispenser status and confirms successful pill ejection from each sector |
| Touch Sensor | Enables user interaction for alert acknowledgment |

### Audio Alerts
An integrated DFPlayer Mini handles audible notifications. The onboard AudioPlayer module manages track selection, volume control, and playback — alerting patients clearly when it is time to take their medication.

### Wi-Fi and Time Synchronization
The system connects to a Wi-Fi network and synchronizes with an NTP server to maintain accurate, real-time scheduling for dispensing events and reminders.

### LCD Display
A LiquidCrystal I2C display provides continuous status feedback, including the current time and battery level, rendered with custom characters for a clear and accessible interface.

---

## About

BiTechX is committed to merging advanced technology with practical healthcare solutions — delivering a safer, more reliable approach to medication management for patients and the people who support them.
