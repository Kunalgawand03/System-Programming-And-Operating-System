# 🧠 System Programming and Operating System

This repository contains the **System Programming and Operating System (SPOS)** laboratory experiments.  
Each experiment focuses on the core components of system software such as **Assembler, Macro Processor, Job Scheduling, Page Replacement,** and **Banker’s Algorithm**.

---

## 📘 Table of Contents
- [About](#about)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Learning Outcomes](#learning-outcomes)
- [Author](#author)
- [License](#license)

---

## 📖 About
This repository includes **5–6 major experiments** covering the concepts of:
- System Programming: Assemblers and Macro Processors  
- Operating System: CPU Scheduling, Memory Management, and Deadlock Avoidance  

Each experiment is implemented to help understand how low-level system components and OS algorithms function internally.

---

## 📂 Folder Structure

| Folder Name | Experiment Title | Description |
|--------------|------------------|--------------|
| `EXP_03_ASSEMBLER_PASS01` | **Assembler Pass 1** | Implementation of the first pass of a two-pass assembler to generate symbol and literal tables. |
| `EXP_04_ASSEMBLER_PASS_02` | **Assembler Pass 2** | Converts intermediate code into final machine code using tables generated in Pass 1. |
| `EXP_05_MACRO_PASS01` | **Macro Processor Pass 1** | Builds Macro Name Table (MNT) and Macro Definition Table (MDT). |
| `EXP_06_MACRO_PASS2` | **Macro Processor Pass 2** | Expands macros using the MNT and MDT to produce the final code. |
| `EXP_07_JOB_SCHEDULING_ALGORITHM` | **Job Scheduling Algorithms** | Demonstrates CPU scheduling techniques (FCFS, SJF, Priority, Round Robin). |
| `EXP_08_PAGE_REPLACEMENT_ALGORITHM` | **Page Replacement Algorithms** | Simulates memory management algorithms like FIFO, LRU, and Optimal. |
| `EXP_09_BANKERS_ALGORITHM` | **Banker’s Algorithm** | Implements resource allocation and deadlock avoidance using Banker’s Algorithm. |

---

## ⚙️ Technologies Used
- **Programming Languages:** C / C++ / Python  
- **IDE:** Visual Studio Code  
- **Platform:** Windows / Linux  

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/<Kunalgawand03>/System-Programming-and-Operating-System.git
Navigate to an Experiment Folder

bash
Copy code
cd EXP_03_ASSEMBLER_PASS01
Compile and Run the Program

bash
Copy code
gcc assembler_pass1.c -o assembler_pass1
./assembler_pass1
(Adjust file name and command based on your implementation.)

🎯 Learning Outcomes
By completing these experiments, you will:

Understand the structure and working of Assemblers and Macro Processors.

Implement and analyze CPU Scheduling Algorithms.

Explore Memory Management techniques and Deadlock Avoidance.

Gain practical knowledge of System-Level Programming and OS Internals.

👨‍💻 Author:Kunal Gawand
📅 Created on: November 2025
🏫 For Academic Use – SPOS Laboratory
