# Welcome to NexWatt ⚡

```text
          27145263556082778577134∞         ░▒▓█ N E X W A T T █▓▒░       ahpan@leland
      22793818301194912983367336244                                      ────────────
    48820466521384146951941511609433       [SYSTEM PROFILE STATUS]       OS: Ubuntu 24.04 LTS
   266482133936072602491412737245870       STATUS: Active Research       Hardware: TNU PIC18 Platform
   549303819644288109756659334461284       INITIATIVE: Eco-Charger       ECAD: KiCad 8.0 Pro
   709384460955058223172535940812848       LOCATION: Nashville, TN       Firmware: Low-Level C / C++
   078164062862089986280348233786783       NETWORK: Local I2C Bus        Protocols: SPI, UART, CAN Bus
   338327950288419716939937510511854       SAFETY: Hardware UVLO         IDE: MPLAB X, VS Code
   42643383279  3.14159  39393751051       VOLTAGE: 5.0V DC (USB-C)      Shell: zsh / bash
   95923078164    (π)    08998628034       METRICS: V, I, Watt-Hours     Core Focus: Robotics, Green Tech
   23066470938           17253594081                                     
   82328230664           51160943305       Contact:                      Location:
   55964462294           29833673362       ────────                      ─────────
   105559644622948954930381964428810       Email: jpan2@trevecca.edu     Trevecca Nazarene University
    2110555964462294895493038196442        GitHub: @Moonaround           Nashville, TN
        1536463678925903600113305
```

---

## ⚡ Renewable Energy Engineering & Microgrid Research [1]

### 🌍 Global Vision & Mission
Growing up in **Myanmar**, I witnessed firsthand what it means to live in a community without stable, reliable electrical infrastructure. In many regions, accessing everyday power is a luxury, and standard energy infrastructure projects are held back by massive technological barriers, high setup costs, and missing safety safeguards. 

**NexWatt was built to change that reality.** 

This organization is dedicated to developing affordable, accessible, and community-focused clean energy solutions. By treating power distribution as a hardware-software integration challenge, our goal is to design open-source frameworks for solar, wind, and green energy harvesting. We focus heavily on engineering stable, rugged electrical nodes that people in low-resource environments can easily set up, use, and rely on year-round.

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

## 🛠️ Technology Integration Stack

<p align="left">
  <img src="https://shields.io" alt="KiCad">
  <img src="https://shields.io" alt="C++">
  <img src="https://shields.io" alt="PIC18">
  <img src="https://shields.io" alt="I2C">
  <img src="https://shields.io" alt="Ubuntu">
</p>

---

## 👥 Research & Engineering Context
*   **Project Lead / Architect:** [Ah-Pan (Moonaround)](https://github.com/Moonaround)
*   **Mechatronics Foundation:** Derived from hands-on laboratory background at the **University of Georgia (UGA) SUROE Lab** managing 3-axis Cartesian gantry robotic control networks.
*   **Collaborative Scope:** Actively seeking professional partnerships with external university laboratories or industrial electronics engineering teams specializing in isolated power path governance and autonomous control logic.

***
