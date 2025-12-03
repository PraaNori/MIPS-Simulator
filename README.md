# MIPS Processor (Logisim)

A single-cycle **MIPS processor** designed and implemented in **Logisim**.  
This processor supports **R-Type, I-Type, and J-Type instructions**, and includes all major components of a basic MIPS CPU.

This is a clean, educational implementation that demonstrates core concepts of computer architecture and digital logic design.

---

## 🚀 Features

### ✔ **Supported Instruction Types**
- **R-Type** (add, sub, and, or, slt)
- **I-Type** (lw, sw, beq, addi)
- **J-Type** (j)

### ✔ **Processor Architecture**
- **Single-cycle MIPS CPU**
- No pipelining (simple architectural design)
- 32-bit datapath implementation

### ✔ **Major Components**
- Program Counter (PC)
- Instruction Memory
- Register File (32 registers × 32 bits)
- ALU (supports arithmetic & logical ops)
- Control Unit (generates all control signals)
- Sign-extender
- Data Memory
- Shift-left-2 units
- Multiplexers for datapath selection

---

## 🧩 Datapath Overview

The processor includes the complete datapath required for standard MIPS execution:

- **Instruction Fetch**
- **Instruction Decode**
- **Operand Fetch**
- **ALU Execution**
- **Memory Access** (for lw/sw)
- **Write Back**

---

---

## ▶️ How to Run

1. Download **Logisim Evolution**  
   https://github.com/logisim-evolution/logisim-evolution

2. Open the file: mips_processor.circ

3. Load your test instructions in Instruction Memory.

4. Click the clock to run a single cycle and observe:

- Register updates  
- ALU outputs  
- Memory reads/writes  

---

## 📘 Supported Instructions (Edit to match your exact list)

### **R-Type**
- `add`
- `sub`
- `and`
- `or`
- `slt`

### **I-Type**
- `lw`
- `sw`
- `beq`
- `addi`

### **J-Type**
- `j`

---

## 🎯 Learning Outcomes

Building this processor helped me understand:

- CPU datapath design
- Control signal generation
- Instruction decoding
- Memory addressing
- ALU operation selection
- How R/I/J type formats work internally

---

## 💡 Future Improvements

- Add **pipelining**
- Add **forwarding + hazard detection**
- Add support for more instructions
- Add syscall simulation
- Add GUI testbench for running programs

---

## 📎 License  
This project is open-source and free to use for learning.
