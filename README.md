# 2.4 GHz Inductively Degenerated Cascode LNA Design using Qucs

## Overview

This project presents the design and simulation of a 2.4 GHz CMOS Inductively Degenerated Cascode Low Noise Amplifier (LNA) using Qucs. The amplifier employs a cascode architecture with inductive source degeneration to achieve high gain, improved input impedance matching, and low noise performance for RF receiver front-end applications operating in the 2.4 GHz ISM band.

---

## Circuit Schematic

<img width="975" height="727" alt="image" src="https://github.com/user-attachments/assets/ff6d408c-25ec-4348-9428-c5564a87d635" />


---

## Simulation Results

### S21 Gain Response

<img width="757" height="868" alt="image" src="https://github.com/user-attachments/assets/33adb052-46fd-4924-bef2-3af681e95c75" />


**Results**

* Peak Gain ≈ 35 dB
* Resonant Frequency ≈ 2.4 GHz

### Noise Figure

<img width="644" height="658" alt="image" src="https://github.com/user-attachments/assets/0843fabd-ba85-46a5-9f53-956c0bd38164" />

**Results**

* Minimum Noise Figure ≈ 0.268 dB
* Optimized low-noise performance near resonance

---

## Design Specifications

| Parameter            | Value   |
| -------------------- | ------- |
| Operating Frequency  | 2.4 GHz |
| Supply Voltage       | 1.8 V   |
| Gate Inductor (Lg)   | 150 nH  |
| Source Inductor (Ls) | 2 nH    |
| Drain Inductor (Ld)  | 5 nH    |
| NMOS Width (W)       | 50 µm   |
| NMOS Length (L)      | 0.18 µm |

---

## Design Methodology

* Cascode NMOS topology for high gain and improved isolation.
* Inductive source degeneration for input matching and noise reduction.
* LC matching network tuned around 2.4 GHz.
* S-parameter analysis for gain and impedance matching evaluation.
* Noise analysis for low-noise RF performance assessment.

---

## Applications

* WLAN Receivers
* Bluetooth Receivers
* RF Receiver Front-End Circuits
* Low Noise Wireless Communication Systems

---

## Tools Used

* Qucs
* CMOS RF IC Design
* S-Parameter Analysis
* Noise Figure Analysis

---

## Author

**Divya Sharma**
