#  Low Power and High Speed Approximate Multiplier for Neural Network and Image Processing Applications

This project focuses on the design and implementation of **low-power, high-speed approximate multipliers** using **approximate compressors** and **NAND gates**. These multipliers are optimized for **neural network** and **image processing** applications, where slight computational inaccuracies can be tolerated in exchange for improved energy efficiency and performance.

---

##  Abstract

Approximate computing offers a powerful strategy to reduce power consumption and design complexity by relaxing the requirement for perfect accuracy. This project proposes novel energy- and quality-efficient approximate multipliers. By employing NAND gates for complemented partial product generation and innovative approximate compressors, the design significantly reduces the transistor count and energy consumption. The designs are evaluated using **Cadence Virtuoso** and **Xilinx Vivado** simulation tools.

---

##  Societal Significance

- Supports **Green AI** by reducing the carbon footprint of AI applications.
- Prolongs battery life in **mobile** and **IoT devices**.
- Enables cost-effective AI solutions in **healthcare**, **smart cities**, and **autonomous systems**.
- Promotes **sustainability** and **accessibility** of technology in underserved regions.

---

##  Problem Statement

Traditional exact multipliers are power-hungry and slow for modern high-performance AI tasks. This project aims to:
- **Reduce power usage and latency**
- **Maintain acceptable accuracy**
- **Create hardware-efficient multipliers** tailored for applications where perfect precision is unnecessary.

---


##  Proposed Methodology

1. **Input**: Two 8-bit values `a` and `b`.
2. **Partial Products**: Bit-wise multiplication.
3. **Basic Architecture**: Built to handle multiplication.
4. **Approximate Compressors**: Replace standard components to reduce complexity.
5. **Approximate Multiplier Design**: Constructed from the above architecture.
6. **Power Analysis**: Evaluate consumption using Cadence.
7. **Performance Evaluation**: Accuracy, speed, and thermal metrics.

![Methodology Diagram](#) <!-- Add actual image link if available -->

---

##  Result Analysis

The proposed **Hybrid Multiplier PM3** integrates 4:1 and 5:2 compressors. It demonstrates improved:
- **Power consumption**
- **Speed**
- **Junction temperature**
Compared with existing multiplier designs.

---

## 👥 Team

- **Guide**: Mrs. K. L. Sowjanya (Asst. Professor, ECE Dept.)
- **Team Members**:
  - K. MANEESHA (228W1A0420, Team Leader)
  - K. TEJA (228W1A0422)
  - B. ESWAR NAIK (238W5A0417)

---

## 📖 References

1. U. Anil Kumar et al., *Low-Power Compressor-Based Approximate Multipliers*, 2022.
2. Haoran Pei et al., *Ultra-Low Power Approximate 4-2 Compressors*, 2021.
3. Suganthi Venkatachalam and Seok-Bum Ko, *Power and Area Efficient Approximate Multipliers*, 2020.
4. L. Sravani and K. Baboji, *Area Efficient Approximate Multiplier using 5:2 Compressors*, 2019.
5. Nguyen Van Toan and Jeong-Gun Lee, *FPGA-Based Approximate Multipliers*, 2020.
6. Amir Momeni et al., *Design and Analysis of Approximate Compressors*, IEEE.

---

## 💻 Tools Used

- **Cadence Virtuoso**
- **Xilinx Vivado**

---


