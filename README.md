# RAM-DESIGN

**COMPANY:** CODTECH IT SOLUTIONS  
**NAME:** Likhith Gowda H R  
**INTERN ID:** CTISAR20
**DOMAIN:** VLSI  
**DURATION:** 4 Weeks  
**MENTOR:** Neela Santosh  

--

📌 Project Overview

This project presents the design and simulation of a Synchronous Random Access Memory (RAM) using Verilog Hardware Description Language (HDL). RAM is an essential component of digital systems used for storing and retrieving data in processors and embedded systems.

The implemented design performs memory read and write operations based on clock and write enable control signals. The design is verified using simulation waveforms and synthesized using Cadence Genus to evaluate hardware performance such as power consumption, timing performance, and area utilization.

🎯 Objective

Design a synchronous RAM using Verilog HDL

Implement clock-based read and write operations

Verify functionality using simulation waveform

Perform synthesis and analyze power, timing, and area performance

⚙️ Tools Used

Verilog HDL

Cadence Genus

SimVision

💻 Source Code
🔹 RAM Design (syncram.v)

Implements synchronous memory operations using clock, write enable, address, and data input signals. The design stores data in memory locations and retrieves stored data based on control signals.

🔹 Testbench (syncram_tb.v)

Applies different input combinations to verify memory read and write operations and generates simulation waveforms.

Source files are available in the Source_Code folder.

🧠 RAM Operation

Write Operation:
When write enable is active and a clock edge occurs, input data is written into the selected memory location.

Read Operation:
When write enable is inactive, stored data from the selected address is retrieved and provided as output.

🖥 Simulation Output

![Waveform](Simulation_Output/waveform.png)

The waveform verifies correct memory read and write operations based on clock and control signals.

🔧 RTL Schematic

![RTL](RTL_Design/rtl.png)

The RTL view shows the synthesized hardware structure of the synchronous RAM generated from the Verilog design.

📊 Synthesis Reports

Power, timing, area, and gate-level reports are available in the Synthesis_Report folder.

📄 Project Report

📥 Download Full Report:
RAM Simulation Report (PDF)

✅ Results

Simulation confirms correct memory storage and retrieval operations. The synthesis analysis shows efficient hardware utilization with acceptable power consumption and timing performance. The design operates reliably under clock-controlled conditions.
