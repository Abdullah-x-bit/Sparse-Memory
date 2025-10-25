# 🧠 Sparse Memory (SystemVerilog Project)

## 📘 Overview
This project implements a **Sparse Memory module** in **SystemVerilog**, designed to efficiently store and access data in a sparse address space. It includes a comprehensive **testbench** and **simulation setup** for functional verification using ModelSim or other HDL simulators.

---

## 🚀 Features
- Efficient **sparse memory architecture** that stores only non-empty addresses.
- Supports **read** and **write** operations with customizable address and data widths.
- Includes a **SystemVerilog testbench** for functional verification.
- Compatible with **ModelSim**, **QuestaSim**, or any SystemVerilog simulator.
- Waveform screenshot provided for simulation verification.

---

## 📂 Project Structure
```
Sparse Memory/
├── sparse_mem.sv              # Main Sparse Memory module
├── tb_sparse_mem.sv           # Testbench for verification
├── Sparse Memory.cr.mti       # ModelSim simulation configuration
├── Screenshot 2025-10-17.png  # Simulation result (waveform/output)
```

---

## ⚙️ How to Run

### 🧰 Using ModelSim
1. Open **ModelSim** or **QuestaSim**.
2. Add the project files to your workspace:
   ```bash
   vlog sparse_mem.sv tb_sparse_mem.sv
   vsim work.tb_sparse_mem
   run -all
   ```
   Or simply run the provided `.cr.mti` file for automated setup.

3. Open the **Waveform** window to visualize signals and verify output behavior.

---

## 🧪 Testbench Description
The `tb_sparse_mem.sv` file includes:
- Memory initialization.
- Multiple **read/write tests**.
- Verification of expected data integrity.
- Console output and waveform generation for debugging.

---

## 📸 Simulation Output
Below is an example waveform from the simulation:

![Simulation Result](./Screenshot%202025-10-17%20213148.png)

---

## 🧩 Tools Used
- **Language:** SystemVerilog  
- **Simulator:** ModelSim / QuestaSim  
- **Operating System:** Windows / Linux  

---

## 👨‍💻 Author
**Abdullah Ibrahim**  
Nanotechnology and Nanoelectronics Engineering Student  
Zewail City of Science and Technology  

📧 Contact: [Email](s-abdullah.afifi@zewailcity.edu.eg)  
🌐 GitHub: [Abdullah Afifi](https://github.com/Abdullah-x-bit)

---

⭐ **If you find this project useful, consider giving it a star on GitHub!**
