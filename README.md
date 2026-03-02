SYNCHRONOUS RANDOM ACCESS MEMORY (RAM)

COMPANY: CODTECH IT SOLUTIONS
NAME: Likhith Gowda H R
INTERN ID: CTISAR20
DOMAIN: VLSI
DURATION: 4 Weeks
MENTOR: Neela Santosh

📌 Project Overview

This project presents the design and simulation of a Synchronous Random Access Memory (RAM) using Verilog Hardware Description Language (HDL). RAM is an essential component of digital systems responsible for storing and retrieving data in processors, embedded systems, and communication devices.

The implemented RAM performs memory read and write operations based on clock and write enable control signals. The design is verified using simulation and synthesized using Cadence Genus to evaluate hardware performance such as power consumption, timing performance, and area utilization.

🎯 Objective

Design a synchronous RAM using Verilog HDL

Implement clock-based memory read and write operations

Verify functionality using simulation waveform

Perform synthesis and analyze hardware performance metrics

⚙️ Tools Used

Verilog HDL

Cadence Genus

SimVision

💻 Source Code
🔹 RAM Design (syncram.v)

Implements synchronous memory operations using clock, write enable, address, and data input signals. The design stores data in memory locations and retrieves stored data based on control signals.

🔹 Testbench (syncram_tb.v)

Applies different input combinations to verify RAM functionality and generates simulation waveforms.

Source files are available in the Source_Code folder.

🧠 RAM Operation
Control Signal	Operation
Write Enable = 1	Data is written into selected memory location
Write Enable = 0	Stored data is read from memory

Memory operations occur only at the positive edge of the clock signal.

🖥 Simulation Output

![Waveform](Simulation_Output/waveform.png)

The waveform verifies correct memory read and write operations based on clock, address, and write enable signals.

🔧 RTL Schematic

![RTL](RTL_Design/rtl.png)

The RTL view shows the synthesized hardware structure of the synchronous RAM generated from the Verilog design.

📊 Synthesis Reports

Power, timing, area, and gate-level reports are available in the Synthesis_Reports folder.

📄 Project Report

[RAM Simulation Report (PDF)](Project_Report/RAMSimulationReport.pdf)


✅ Results

Simulation confirms correct memory storage and retrieval operations. Synthesis analysis shows efficient hardware utilization with acceptable power consumption and timing performance. The design operates reliably under clock-controlled conditions.
