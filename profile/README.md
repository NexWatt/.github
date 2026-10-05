# Welcome to NexWatt ⚡

```text
 ███▄    █ ▓█████▒██   ██▒ █▒ █▓ ▄▄▄      ▄▄▄█████▓ ▄▄▄█████▓
 ██ ▀█   █ ▓█   ▀ ▒██  ██▒▓██▒██▒▒████▄    ▓  ██▒ ▓▒ ▓  ██▒ ▓▒
▓██  ▀█ ██▒▒███    ▒██ ██░ ▒████▒░▒██  ▀█▄  ▒ ▓██░ ▒░ ▒ ▓██░ ▒░
▓██▒  ▐▌██▒▒▓█  ▄  ░ ▐██▓░ ░██ ░█░░██▄▄▄▄██ ░ ▓██░ ░  ░ ▓██░ ░ 
▒██░   ▓██░░▒████▒ ░ ██▒▓░ ░██ ░█░ ▓█   ▓██▒  ▒██▄░     ▒██▄░  
░ ▒░   ▒ ▒ ░░ ▒░ ░  ██▒▒▒  ░ ▒ ░░  ▒▒   ▓▒█░  ░██▒░     ░██▒░  
░ ░░   ░ ▒░ ░ ░  ░▓██ ░▒░  ░ ░▒ ░   ▒   ▒▒ ░    ░░        ░░   
   ░   ░ ░    ░   ▒ ▒ ░░     ░ ░    ░   ▒        ░         ░   
         ░    ░  ░░ ░        ░          ░  ░               ░   
                  ░ ░                                          
```

<p align="center">
  <img src="https://shields.io" alt="Junior Capstone">
  <img src="https://shields.io" alt="Founder">
  <img src="https://shields.io" alt="ECE & Robotics">
</p>

---

## ⚡ Our Vision: Democratic & Resilient Green Infrastructure

Growing up in **Myanmar**, I experienced firsthand what it means to live in a community without stable, reliable electrical power grids. In many developing regions, accessing basic electricity is an everyday challenge, and constructing large-scale hydro-power generation networks remains locked behind extreme technological barriers and critical safety compliance risks. 

**NexWatt was founded to shatter those dependencies.** 

Led as an independent undergraduate engineering research initiative, our mission is to apply rigid hardware-software co-design, power electronics, and embedded control loops to engineer open-source, affordable, and easily deployable microgrid solutions. We focus on bridging the gap between volatile natural forces and safe digital systems—developing hybrid solar tracking, robust wind-turbine harvesting arrays, and intelligent multi-chemistry storage protection networks tailored specifically for community resilience and low-resource environments.

---

## 🛰️ System Topology Blueprint

```text
        ┌────────────────────────────────────────────────────────┐
        │                 ENVIRONMENTAL HARVESTERS               │
        │    ☀️  [Solar Photovoltaic Array (East-to-West)]       │
        │    💨  [Micro-Wind Turbine Kinetic Spinner]            │
        └───────────────────────────┬────────────────────────────┘
                                    │ (Chaotic Input Voltages)
                                    ▼
        ┌────────────────────────────────────────────────────────┐
        │             ANALOG FRONT-END TELEMETRY LAYER           │
        │    📋  [Resistor Divider Network (Voltage Scaling)]    │
        │    📊  [Sub-Ohm Inline Shunt (Current Monitoring)]      │
        └───────────────────────────┬────────────────────────────┘
                                    │ (Safe 0-3.3V Analog Signals)
                                    ▼
        ┌────────────────────────────────────────────────────────┐
        │             CENTRAL CONTROL CORE (THE BRAIN)           │
        │    💻  [TNU PIC18 Microcontroller Peripheral Loop]      │
        │    ⚡  [Hardware Finite State Machine (UVLO Control)]   │
        └─────────────────────┬───────────┬──────────────────────┘
                              │           │
     (I2C Local Serial Bus)   ▼           ▼  (High-Speed PWM Commands)
  ┌─────────────────────────────┐       ┌─────────────────────────────┐
  │   SERIAL DISPLAY NETWORK    │       │     MOSFET SWITCH ARRAY     │
  │  🤖 Secondary Screen Driver │       │  🔋 Battery Bank Isolation  │
  │  📺 Live Power Diagnostics  │       │  🔌 5V USB Type-C Delivery  │
  └─────────────────────────────┘       └─────────────────────────────┘
```

---

## 🛠️ Core Technology Integration Stack

<p align="left">
  <img src="https://shields.io" alt="KiCad">
  <img src="https://shields.io" alt="C++">
  <img src="https://shields.io" alt="PIC18">
  <img src="https://shields.io" alt="I2C">
  <img src="https://shields.io" alt="Ubuntu">
</p>

---

## 👥 Lead Architect & Research Profile
*   **Founder / Systems Engineer:** [Ah-Pan (Moonaround)](https://github.com/Moonaround) — Electrical & Computer Engineering Student.
*   **Mechatronics Foundation:** Drawing from practical research background at the **University of Georgia (UGA) SUROE Lab**, focusing on 3-axis Cartesian gantry robotic control networks and automated instrument placement.
*   **Research Focus:** Open-source power electronics, isolated telemetry acquisition, and deterministic embedded safety safeguards.

***
