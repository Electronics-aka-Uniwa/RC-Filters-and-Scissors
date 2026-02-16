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
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Lecturer in Applications
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, December 2022
</p>

---

# Project Overview

This project investigates the behavior of **R-C (Resistor–Capacitor) circuits**, with emphasis on **smoothing filters** and **scissors (clipping) circuits**. The study combines **theoretical analysis**, **software simulations using Multisim**, and **hands-on laboratory experiments** to validate circuit behavior under various operating conditions.

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
| 4 | `filter/LabPNG/` | RC filter lab experiment images |
| 4.1 | `filter/Multisim/` | RC filter Multisim project files |
| 4.2 | `filter/MultisimPNG/` | RC filter Multisim screenshots |
| 4.3 | `filter/` | Graphs and lab sheets (Filtro_Graph.png, FylloErgasthriou*.png, Q4.png, Q5.png, Q5Graph.png) |
| 5 | `scissors/LabPNG/` | Scissors (waveform shaping) lab images |
| 5.1 | `scissors/Multisim/` | Scissors lab Multisim project files |
| 5.2 | `scissors/MultisimPNG/` | Scissors lab Multisim screenshots |
| 5.3 | `scissors/` | Graphs and lab sheets (FylloErgasthriou*.png, psali_*.png, Psali_*.png, Q1_*.png) |
| 6 | `README.md` | Repository overview and instructions |

---

## Project Structure

The report is divided into two main sections:

### 1. R-C Smoothing Filter Circuits
Analysis of smoothing filter behavior with focus on **ripple voltage (Vₖ)** under varying parameters:
- Input frequency
- Resistance values
- Capacitance values  

The effect of each parameter on output signal stability is examined through calculations, simulations, and measurements.

---

### 2. Scissors (Clipping) Circuits
Study of clipping circuit configurations, including:
- Standard scissor circuits  
- Circuits with **DC voltage offset**  
- **Inverted clipping (shear) circuits**

The output waveform distortion and voltage limiting behavior are analyzed.

---

## Laboratory Equipment Used

- **Breadboard**: M21-7000A Analog & Digital Training System  
- **Power Supply**: DC Power Supply  
- **Multimeter**: MCP MT8045 Digital Multimeter Bench  
- **Oscilloscope**: HAMEG HM303-6 or HM203-5  
- **Components**:
  - Silicon diode  
  - Resistors: **4.7 kΩ**, **10 kΩ**  
  - Capacitor: **0.1 µF**

---

## Experimental Example: 1 kHz Smoothing Filter

A representative experiment involves a smoothing filter powered by a **6 V<sub>p-p</sub>** input signal at **1 kHz**.

### Theoretical Foundation
The ripple voltage **Vₖ** is calculated using:

$$
Vₖ = Vₚ / (f · R · C)
$$

For:
- f = 1 kHz  
- R = 4.7 kΩ  
- C = 0.1 µF  


The theoretical ripple voltage is:

$$
Vₖ ≈ 2 V
$$

---

## Procedure Summary

1. **Setup**  
   - Set input frequency to **1000 Hz**  
   - Adjust the input signal to **6 V<sub>p-p</sub>** using the oscilloscope  

2. **Assembly**  
   - Connect the silicon diode in series with the source  
   - Place the **4.7 kΩ resistor** after the diode  

3. **Filtering**  
   - Connect the **0.1 µF capacitor** in parallel with the resistor  

4. **Measurement**  
   - Use **Channel B** of the oscilloscope to measure the output across the capacitor  

---

## Contents

- **Theoretical Solution**  
  Mathematical analysis and circuit schematics  

- **Simulated Solution**  
  Waveforms and measurements obtained using **Multisim**  

- **Experimental Solution**  
  Step-by-step laboratory procedures and recorded measurements

---

# Installation & Setup Guide  

This guide explains how to install, set up, and use the **RC-Filters-and-Scissors** laboratory project.  
The repository contains **assignment material**, **theoretical notes**, **Multisim simulations**, **graphs**, and **laboratory results** related to **R-C smoothing filters** and **scissors (clipping) circuits**.

---

## Prerequisites

Before working with this project, make sure the following requirements are met.

---

### 1. Software Requirements

#### NI Multisim
- **NI Multisim 14 or newer**
- Required to:
  - Open and run RC filter simulations
  - Simulate scissors (clipping) circuits
  - Observe waveforms, ripple voltage, and clipping behavior

Used in folders:
- `filter/Multisim/`
- `scissors/Multisim/`

---

#### PDF Reader
- Any modern PDF reader (Adobe Reader, browser-based PDF viewer, etc.)
- Required to open:
  - Assignment descriptions
  - Theoretical documentation (English & Greek)

---

#### Image Viewer
- Any standard image viewer
- Required for viewing:
  - Lab photos
  - Graphs
  - Screenshots (`.png` files)

---

### 2. Hardware Requirements (Optional – Physical Lab)

Required **only if** you plan to repeat the experiments in a real laboratory environment:

- **Analog & Digital Training System:** M21-7000A  
- **DC Power Supply**
- **Digital Multimeter:** MCP MT8045  
- **Oscilloscope:** HAMEG HM303-6 or HM203-5  
- **Electronic Components**
  - Silicon diode  
  - Resistors: **4.7 kΩ**, **10 kΩ**  
  - Capacitor: **0.1 µF**

> Hardware is **not required** for studying theory or running simulations.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/RC-Filters-and-Scissors.git
cd RC-Filters-and-Scissors

```

### 2. Open Theoretical Documentation
Navigate to the `docs/` directory and open:
- English: `RC-Filters-and-Scissors.pdf`
- Greek: `RC-Φίλτρα-και-Ψαλλιδιστές.pdf`

These documents explain:
- RC smoothing filter operation
- Ripple voltage theory
- Clipping and voltage limiting circuits

### 3. Review Assignment Instructions
Open the files in the `assign/` folder:
- English: `Exercise-6th-RC-Filters-and-Scissors.pdf`
- Greek: `Άσκηση-6η-Φίλτρα-RC-και-Ψαλλιδιστές.pdf`

Follow these documents for:
- Required circuits
- Measurement steps
- Expected analysis and conclusions

### 4. Run Multisim Simulations
#### RC Filters
1. Open NI Multisim.
2. Navigate to:
```bash
filter/Multisim/
```
3. Open the provided Multisim project files.
4. Run the simulation.
5. Observe:
    - Output smoothing
    - Ripple voltage variation
    - Effect of R, C, and frequency changes

#### Scissors (Clipping) Circuits
1. Open NI Multisim.
2. Navigate to:
```bash
scissors/Multisim/
```
3. Open the circuit files.
4. Run the simulation.
5. Observe:
    - Clipped waveforms
    - Voltage limiting levels
    - Effect of DC offset and inversion

### 5. View Experimental Results
- Graphs & Lab Sheets
  - `filter/*.png`
  - `scissors/*.png`
- Multisim Screenshots
  - `filter/MultisimPNG/`
  - `scissors/MultisimPNG/`
- Lab Photos
  - `filter/LabPNG/`
  - `scissors/LabPNG/`
