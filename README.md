# Circuit-Logic
Implementation of fundamental digital logic circuits using TTL components, culminating in the development of a fully functional 12-hour digital clock.

## Overview

This repository contains the final project developed for the Computer Organization course.

The objective of this project was to design, implement and validate several fundamental digital circuits using combinational and sequential logic. Each module was developed independently and later integrated into a complete 12-hour digital clock.

The project emphasizes practical applications of digital electronics concepts, including logic gates, counters, multiplexers, flip-flops, encoders, decoders and digital system integration.

## Simulation Files

The complete digital system is available in the `circuit/` directory.

To run the project:

1. Download the `Circuit_Logic.CircuitProject` file.
2. Download the LogicCircuit software:
https://www.logiccircuit.org/download.html
3. Start the simulation to observe the behavior of the implemented modules and the integrated 12-hour digital clock.
## Objectives

- Understand the operation of combinational circuits.
- Design sequential logic circuits.
- Implement synchronous counters.
- Develop digital systems using modular components.
- Integrate multiple digital modules into a complete system.

## Concepts Covered

- Combinational Logic
- Sequential Logic
- TTL Logic (74LS Series)
- Digital Counters
- Flip-Flops
- Multiplexing
- Binary and Decimal Encoding
- Magnitude Comparison
- Seven-Segment Display Control
- Digital System Integration
- Computer Organization

## Implemented Modules

### BCD to Seven-Segment Decoder

Implementation of a BCD decoder responsible for converting binary-coded decimal values into seven-segment display outputs.

---

### Modulo-10 Counter

Synchronous decimal counter used for units digits.

---

### Modulo-6 Counter

Counter designed for tens of seconds and tens of minutes.

---

### Modulo-2 Counter

Binary counter used for control and state transitions.

---

### JK Flip-Flop

Implementation of a JK Flip-Flop featuring:

- Clock input
- Preset
- Clear

The flip-flop was used for sequential control and state storage.

---

### Multiplexer

Implementation of a digital multiplexer for signal selection.

---

### Decimal Priority Encoder

Priority encoder capable of selecting the highest-priority active decimal input.

---

### Magnitude Comparator

Digital comparator capable of determining:

- A > B
- A = B
- A < B

---

### 12-Hour Digital Clock

The final system integrates all previous concepts into a complete digital clock featuring:

- Hours
- Minutes
- Seconds
- AM/PM indication
- Seven-segment displays

## Learning Outcomes

This project provided practical experience with the design and implementation of digital systems using modular hardware components.

The development process reinforced concepts related to combinational and sequential logic, synchronous circuit design, modular decomposition and system integration, demonstrating how individual digital circuits interact to form a complete embedded system.
## Future Improvements

- 24-hour clock mode
- Alarm functionality
- Stopwatch
- Timer
- PCB implementation
- FPGA implementation
- Hardware prototyping

## Author

Arthur

Computer Science Undergraduate Student

State University of Ceará, UECE

Brazil
