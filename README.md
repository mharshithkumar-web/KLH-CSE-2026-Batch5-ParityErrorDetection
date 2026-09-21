# KLH-CSE-2026-Batch5-ParityErrorDetection
Design and Simulation of a Digital Error Detection System Using Parity

## Project Overview
This repository contains the complete design, circuit implementation, simulation files, and presentation reports for the Digital Design and Computer Architecture (DDCA) course project at KLH University.

---

## Team Members & Registration Numbers
* **M. Harshith Kumar** – 2620030453
* **Balasai Vaishnavi** – 2620030340
* **Pasham Thanay Kumar** – 2620030350
* **Bijjam Naga Harsha Vardhan Reddy** – 2620030433

## Institutional Details
* **Department:** Department of Computer Science and Engineering (CSE)
* **University:** KLH University
* **Academic Year:** 2026–2027
* **Faculty Guide:**  Kartheek V

---

## Abstract
Digital communication systems transmit data as binary sequences of 0s and 1s. External noise and interference can cause bit-flipping during transmission, leading to data corruption. This project implements a reliable, low-cost parity-based error detection architecture using XOR logic gates, featuring a 4-bit parity generator at the sender and a parity checker with an LED indicator at the receiver.

---

## Repository Directory Structure
* `/src` – Contains core Logisim circuit implementation files (`.circ`).
  * `Parity_Error_Detection.circ`
  * `PARITY_GENRATOR.circ`
  * `PARITY_CHECKER.circ`
* `/reports` – Contains project presentation slides
  * `DDCA_Parity_Error_Detection_PPT.pptx`

---

## Setup and Execution Instructions
1. **Prerequisites:**
   * Download and install **Logisim** simulation software.
2. **Opening the Circuit Files:**
   * Open Logisim, navigate to the `src/` directory, and open `Parity_Error_Detection.circ`.
3. **Simulating and Testing:**
   * Use the Logisim Poke Tool to toggle binary input pins (`D0`, `D1`, `D2`, `D3`, and parity bit `P`) to verify error and no-error states via the output LED.
