# MIPS-32 Processor in SystemVerilog

## 📌 Project Overview
This project implements a **32-bit MIPS processor** in SystemVerilog.  
The processor is capable of performing **Addition, Subtraction, Multiplication, and Division** operations, simulating a simplified CPU datapath design.

---

## 🔍 Problem Statement
Modern processors require efficient arithmetic units to handle a variety of computational tasks.  
The objective of this project was to design a **MIPS-32 processor** with a modular architecture that supports basic arithmetic operations and can be verified through simulation.

---

## ✅ Solution Approach
1. **Designing the Architecture**  
   - Defined the datapath and control signals for a MIPS-32 CPU.  
   - Implemented Arithmetic Logic Unit (ALU) modules for Add, Sub, Mul, and Div.  
   - Integrated control logic to manage instruction execution.  

2. **Overcoming Challenges**  
   - Created a structured **SystemVerilog design (design.sv)** with modular components.  
   - Wrote a **testbench (tb.sv)** for functional verification.  
   - Debugged using **EPWave/ModelSim waveform analysis** to ensure correctness of results.  

3. **Verification**  
   - Verified processor operations with multiple test cases.  
   - Validated correct outputs for arithmetic operations through simulation waveforms.  

---

## 🛠️ Technologies Used
- **SystemVerilog (design.sv, tb.sv)**  
- **EPWave / ModelSim** for simulation and waveform debugging  
- **GitHub** for version control and project hosting  

---

## 📂 Project Structure
├── design.sv # Processor design implementation
├── tb.sv # Testbench for simulation
├── Epwave.png # Example waveform output
└── README.md # Project documentation


---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/whozaifa/Mips-32.git


Open the files (design.sv and tb.sv) in your preferred simulator (ModelSim / Icarus Verilog).

Run the testbench to verify arithmetic operations.

View results in EPWave/ModelSim waveform viewer.

📊 Results

Successfully implemented a working 32-bit MIPS processor.

Verified correct execution of Add, Sub, Mul, and Div operations.

Example simulation waveform:

👨‍💻 Author

Nusaibul Hasan

📧 hasanryan052@gmail.com

🌐 LinkedIn
 | GitHub

