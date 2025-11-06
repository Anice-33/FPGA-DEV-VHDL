# Programmable Logic – FPGA & VHDL Lab Series

This repository contains all five FPGA laboratory exercises from the **“Programmierbare Logik”** module at the **Berliner Hochschule für Technik (BHT)**.  
The labs were implemented using **Intel Quartus Prime** and simulated in **ModelSim**, targeting **Intel DE2-115** and **DE10/DE12** FPGA boards.

Each lab demonstrates practical aspects of digital design — from combinational logic and sequential machines to serial communication interfaces — written entirely in **VHDL**.

---

## 📂 Folder Overview

all/
├── Labor_1_Neptun/ → BCD-to-7-Segment Converter & Binary-to-BCD IP-Core
├── Labor_2_Neptun/ → 3-Digit Counter, 24-Hour Clock, Stopwatch
├── Labor_3_Neptun/ → Bit-Sequence Detector (FSM Design)
├── Labor_4_Neptun/ → Booth Multiplier (Datapath & Control Unit)
└── Labor_5_Neptun/ → SPI Slave Interface

---

## 🧠 Summary of Each Laboratory

### **Labor 1 – BCD to 7-Segment Converter**
Design and simulation of a combinational decoder converting BCD input to 7-segment output.  
Includes a testbench and structural composition of a binary-to-7-segment display system using an IP-Core.

**Topics:** BCD logic, behavioral vs. structural VHDL, RTL analysis, IP-core integration.

---

### **Labor 2 – Counters and Time Systems**
Implementation of a 3-digit BCD counter extended into a full 24-hour clock and stopwatch using the DE2-115 FPGA board.

**Topics:** clock division, synchronous counters, display multiplexing, timekeeping FSMs.

---

### **Labor 3 – Bit-Sequence Detector**
Development of a state machine that detects sequences of four identical bits (`0000` or `1111`) using D-flip-flops and alternative CASE-based process modeling.

**Topics:** state encoding, FSM design, sequential logic, manual flip-flop instantiation, RTL & technology view verification.

---

### **Labor 4 – Booth Algorithm Multiplier**
Implementation of a **Booth-encoded** multiplier for signed 4-bit numbers in two’s complement.  
Design includes datapath and control unit separation.

**Topics:** arithmetic datapath design, control FSM, signed multiplication, Moore automaton modeling.

---

### **Labor 5 – SPI Slave Interface**
Design and verification of an SPI slave module capable of receiving 8-bit words via MOSI/SCLK/SS lines.  
Output is displayed on 7-segment LEDs upon transfer completion.

**Topics:** synchronous serial communication, edge detection, shift registers, timing analysis.

---

## ⚙️ Tools and Hardware

- **Intel Quartus Prime Lite Edition**  
- **ModelSim Intel FPGA Edition**  
- **Terasic DE2-115 / DE10-Lite / DE12 FPGA boards**  
- **VHDL-2008 standard**

---

## ▶️ How to Run the Projects

1. Open any `Labor_X_Neptun` folder in **Quartus Prime**.  
2. Load the `.qpf` project file.  
3. Compile the design and open the **RTL Viewer**.  
4. Run provided testbenches or `.do` scripts in **ModelSim**.  
5. (Optional) Load the compiled `.sof` file onto your FPGA board to verify operation.

---

## 📜 License
All projects are part of an academic course and are shared for **educational and research purposes** only.  
Reproduction or redistribution for grading or commercial use requires citation of the author.

---

## 👤 Author

**Anis Jallali**  
Student of Embedded Systems Engineering – Berliner Hochschule für Technik (BHT)  
📧 [s90499@bht-berlin.de](mailto:s90499@bht-berlin.de)  
🔗 [GitHub: Anice-33](https://github.com/Anice-33)
