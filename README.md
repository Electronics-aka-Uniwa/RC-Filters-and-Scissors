<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Electronics</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  RC Filters and Scissors
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Anastasios Tsilikounas, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/anastasios-tsilikounas/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/anastasios-tsilikounas-31111566/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Georgios Antoniou, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/georgios-antoniou/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, December 2022
</p>

---

# Project Overview

This document is a laboratory report for the **Circuit Theory** course within the **Department of Informatics and Computer Engineering** at the **University of West Attica**.

The project focuses on the **study and analysis of the resonance effect in RLC circuits**. It explores the behavior of **resistors, inductors, and capacitors** when connected in **series** and **parallel** configurations across varying frequencies.

---

## Table of Contents

| Section | Folder / File | Description |
|--------:|---------------|-------------|
| 1 | `assign/` | Assignment material |
| 1.1 | `assign/Exercise-6th-RC-Filters-and-Scissors.pdf` | Assignment description (English) |
| 1.2 | `assign/Άσκηση-6η-Φίλτρα-RC-και-Ψαλλιδιστές.pdf` | Assignment description (Greek) |
| 2 | `componentss/` | Lab components and equipment images |
| 3 | `docs/` | Theoretical documentation |
| 3.1 | `docs/RC-Filters-and-Scissors.pdf` | Theory (English) |
| 3.2 | `docs/RC-Φίλτρα-και-Ψαλλιδιστές.pdf` | Theory (Greek) |
| 4 | `filterr/LabPNG/` | RC filter lab experiment images |
| 4.1 | `filterr/Multisim/` | RC filter Multisim project files |
| 4.2 | `filterr/MultisimPNG/` | RC filter Multisim screenshots |
| 4.3 | `filterr/` | Graphs and lab sheets (Filtro_Graph.png, FylloErgasthriou*.png, Q4.png, Q5.png, Q5Graph.png) |
| 5 | `scissorss/LabPNG/` | Scissors (waveform shaping) lab images |
| 5.1 | `scissorss/Multisim/` | Scissors lab Multisim project files |
| 5.2 | `scissorss/MultisimPNG/` | Scissors lab Multisim screenshots |
| 5.3 | `scissorss/` | Graphs and lab sheets (FylloErgasthriou*.png, psali_*.png, Psali_*.png, Q1_*.png) |
| 6 | `README.md` | Repository overview and instructions |

---

## Key Contents

The report is structured into:

- **Theoretical Analysis**  
- **Software Simulations** using *Multisim*  
- **Experimental Laboratory Results**

---

## 1. RLC Series Circuit

**Theory:**  
Analysis of the frequency at which the **inductive reactance (Xₗ)** and **capacitive reactance (Xc)** cancel each other out.

**Key Observations:**

- The **impedance (Z)** becomes equal to the **ohmic resistance (R)** at resonance.
- **Maximum current flow** occurs at the resonant frequency.
- **Overvoltage phenomena** are observed across the capacitor and inductor.

**Formula Used:**  

$$
f_r = \frac{1}{2\pi\sqrt{LC}}
$$

Where:  
- \(f_r\) = resonant frequency  
- \(L\) = inductance  
- \(C\) = capacitance


---

## 2. RLC Parallel Circuit

- Theoretical solutions and **simulation results** for parallel RLC configurations.  
- Detailed analysis provided in the report (pages 12–17).

---

## Laboratory Equipment

The experimental work utilized the following tools:

- **Multimeters** (Analog and Digital)  
- **Oscilloscope**  
- **Breadboard**  
- **Passive Components:**  
  - Resistors  
  - Capacitors  
  - Inductors

---

# Installation & Setup Guide

This repository contains laboratory simulations and analysis for **Circuit Theory**, focusing on **RLC series and parallel circuits** and their resonance behavior.  

All simulations are implemented in **NI Multisim**.

---

## Prerequisites

### Required Software
- **NI Multisim 14** (or later)  
  Ensure your system meets the requirements for running `.ms14` files.  
  Download from [NI Multisim](https://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/what-is-multisim.html).

### Optional Software
- **PDF Viewer** for documentation: `Coordination.pdf` / `Συντονισμός.pdf`

---

## Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/Circuit-Theory/Coordination.git
```

### 2. Navigate to Project Directory
```bash
cd Coordination
```
Ensure the following folder structure exists:
```bash
assign/
docs/
multisim/
```

---

## Multisim Simulation Files

The repository includes two key simulation files:

| File  | Description |
|------:|-------------|
| multisim/CoordinationSerial.ms14 |  RLC series circuit simulation |
| multisim/CoordinationParallel.ms14 |  RLC parallel circuit simulation |


### 3. Open a Simulation in Multisim
- Launch NI Multisim.
- Select File → Open.
- Navigate to the `multisim/` folder.
- Open the desired `.ms14` file (series or parallel circuit).
- Wait for the circuit topology to load.

---

## Open the Documentation
1. Navigate to the `docs/` directory
2. Open the report corresponding to your preferred language:
    - English: `Coordination.pdf`
    - Greek: `Συντονισμός.pdf`
