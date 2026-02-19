<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
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

<hr>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Panagiotis Giannakopoulos, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/panagiotis-yannakopoulos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/panos-yannakopoulos-b9b6987/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Academic Scholar
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/academic_sc_ho/" target="_blank">UNIWA Profile</a> ·
  <a href="https://scholar.google.com/citations?user=-LnaZGgAAAAJ&hl=en" target="_blank">Scholar</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

</hr>

---

<p align="center">
  Athens, December 2022
</p>

---

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLHj_63AglzZgEVugSq9YUntnHdfQwaisPLnrQKkMJ&s" width="250"/>
</p>

---

# INSTALL

## RC Filters and Scissors

This guide explains how to install, set up, and use the **RC-Filters-and-Scissors** laboratory project.  
The repository contains **assignment material**, **theoretical notes**, **Multisim simulations**, **graphs**, and **laboratory results** related to **R-C smoothing filters** and **scissors (clipping) circuits**.

---

## 1. Prerequisites

Before working with this project, make sure the following requirements are met.

---

## 2. Software Requirements

### 2.1 NI Multisim

- **NI Multisim 14 or newer**
- Required to:
  - Open and run RC filter simulations
  - Simulate scissors (clipping) circuits
  - Observe waveforms, ripple voltage, and clipping behavior

Used in folders:

- `filter/Multisim/`
- `scissors/Multisim/`

### 2.2 PDF Reader

- Any modern PDF reader (Adobe Reader, browser-based PDF viewer, etc.)
- Required to open:
  - Assignment descriptions
  - Theoretical documentation (English & Greek)

### 2.3 Image Viewer

- Any standard image viewer
- Required for viewing:
  - Lab photos
  - Graphs
  - Screenshots (`.png` files)

---

## 3. Hardware Requirements (Optional – Physical Lab)

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

## 4. Installation & Setup

### 4.1 Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/RC-Filters-and-Scissors.git
cd RC-Filters-and-Scissors

```

### 4.2 Open Theoretical Documentation

Navigate to the `docs/` directory and open:

- English: `RC-Filters-and-Scissors.pdf`
- Greek: `RC-Φίλτρα-και-Ψαλλιδιστές.pdf`

These documents explain:

- RC smoothing filter operation
- Ripple voltage theory
- Clipping and voltage limiting circuits

### 4.3 Review Assignment Instructions

Open the files in the `assign/` folder:

- English: `Exercise-6th-RC-Filters-and-Scissors.pdf`
- Greek: `Άσκηση-6η-Φίλτρα-RC-και-Ψαλλιδιστές.pdf`

Follow these documents for:

- Required circuits
- Measurement steps
- Expected analysis and conclusions

---

## 5. Run Multisim Simulations

### 5.1 RC Filters

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

### 5.2 Scissors (Clipping) Circuits

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

### 5.3 View Experimental Results

- Graphs & Lab Sheets
  - `filter/*.png`
  - `scissors/*.png`
- Multisim Screenshots
  - `filter/MultisimPNG/`
  - `scissors/MultisimPNG/`
- Lab Photos
  - `filter/LabPNG/`
  - `scissors/LabPNG/`
