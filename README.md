# 8051 Microcontroller Development Board – PCB Design

A custom-designed 8051 microcontroller development board created for learning, experimentation,
and embedded systems prototyping. This project covers the complete hardware design flow,
from schematic capture to PCB layout.

---

##  Project Overview

This project involves the design of a standalone 8051 microcontroller development board.
The board provides all essential circuits required for reliable operation of the 8051,
including regulated power supply, clock generation, reset circuitry, and easy access to
all I/O ports. The design is suitable for students and beginners to understand practical
embedded hardware design.

---

##  Features

- Supports AT89S51 / 8051 microcontroller
- Regulated 5V power supply using LM7805
- External crystal oscillator (11.0592 MHz)
- Manual reset circuit using push button
- All I/O ports (P0, P1, P2, P3) available on headers
- ISP programming support (MOSI, MISO, SCK, RST)
- Power indication LED
- Simple and beginner-friendly PCB layout

---

##  Schematic Diagram

The complete schematic includes:
- Power supply circuit
- Reset circuit
- Crystal oscillator circuit
- 8051 microcontroller pin connections

> 📁 See: `docs/8051_dev_board_schematic.pdf`

---

##  Power Supply Design

The board uses an LM7805 linear voltage regulator to convert an external DC supply into a
stable 5V output required by the 8051 microcontroller. A diode is used for input protection,
and capacitors are placed for filtering and voltage stability.

---

##  Reset Circuit

A manual reset circuit is implemented using a push button and RC network to ensure proper
power-on reset and allow the user to reset the microcontroller during operation.

---

##  Clock Circuit

An external 11.0592 MHz crystal oscillator is used along with load capacitors to generate
a stable clock signal. This frequency is commonly used for accurate serial communication
applications.

---

##  PCB Design Details

- Designed using **KiCad**
- Single-layer / Double-layer PCB (as per design)
- Proper trace routing and grounding practices followed
- Decoupling capacitors placed close to power pins
- Clear silkscreen labeling for easy debugging and usage

---


