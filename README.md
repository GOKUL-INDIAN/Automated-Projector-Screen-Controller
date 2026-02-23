
# 🎬 Automated Projector Screen Control System

## 📌 Overview
An automated motorized projector screen control system designed using programmable timer relay modules and discrete hardware logic. The system enables synchronized screen deployment and retraction with adjustable delay control and motor protection mechanisms.

---

## 🎯 Objective
To design a reliable and modular hardware-based automation system for controlling a motorized projector screen with configurable timing and safe motor operation.

---

## ⚙️ System Features

- Adjustable ON/OFF delay using digital timer relay modules
- Bidirectional motor control (UP / DOWN)
- Manual override capability
- Relay-based motor isolation
- Modular perfboard-based hardware design
- Expandable architecture for microcontroller integration

---

## 🏗 Hardware Architecture

### Major Components

- Digital Timer Relay Modules (with 7-segment display)
- SPDT Power Relays
- Perfboard-based custom routing boards
- DC Motor (Projector Screen Motor)
- External Power Supply
- Manual Trigger Inputs

---

## 🔄 Working Principle

1. Trigger input activates the control relay.
2. Timer module initiates programmable delay.
3. Motor drive relay energizes in selected direction.
4. Screen deploys or retracts.
5. Relay deactivates after set duration.
6. System resets to idle state.

---

## 🔐 Safety Features

- Directional interlock protection
- Time-limited motor activation
- Relay isolation between control and power stage
- Manual emergency override

---

## 🛠 Hardware Implementation

- Built on modular perfboards
- Separated control and power routing
- Organized relay grouping for each functional block
- Expandable design for future ESP32/IoT integration

---

## 🚀 Future Improvements

- ESP32-based wireless control
- Mobile app integration
- Limit switch feedback
- Position memory
- Soft start motor control
- Enclosed PCB design

---

## 📸 Hardware Prototype

<p align="center">
  <img src="images/hardware_setup.jpg" width="700">
</p>

---

