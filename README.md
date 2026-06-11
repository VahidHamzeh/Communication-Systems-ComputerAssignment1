# Communication Systems - Computer Assignments (Dr. Behroozi)

This repository contains the complete set of computer assignments (CAs) for the **Communication Systems** course at **Sharif University of Technology** (Spring 2025), under the instruction of **Dr. Behroozi**. 

The projects cover a comprehensive curriculum ranging from foundational signal analysis and analog modulations (AM/FM) to digital communication link simulations and analog noise modeling.

## 📂 Repository Structure

To keep the project organized, each assignment is contained within its respective directory:
* `/CA1_Signals_and_Systems`: Core signal concepts, system identification, filtering, and DTMF decoding.
* `/CA2_Analog_Modulation`: Extensive implementation and analysis of AM and FM transceivers.
* `/CA3_Digital_Comm_and_Noise`: Digital pulse shaping, matched filtering, Monte Carlo BER curves, and analog noise analysis.

---

## 📌 Project Overview & Highlights

### 🔹 Computer Assignment 1: Signals, Systems, and Noise
Focuses on time and frequency domain representations of signals, system characterization, and basic audio cleanup.
* **System Identification:** Utilizing a linear "chirp" probe signal and cross-correlation to estimate an unknown LTI system's (room with echoes) impulse response.
* **Forensic Audio Cleanup:** Designing a digital Notch Filter to eliminate sinusoidal whine and a Low-Pass FIR Filter to suppress white Gaussian noise from corrupted speech.
* **Channel Equalization:** Simulating a muffling channel distortion and building a regularized inverse FIR filter to restore high-frequency content.
* **DTMF Decoding:** Leveraging spectrogram analysis to decode dual-tone multi-frequency touch-tone phone sequences from audio samples.

### 🔹 Computer Assignment 2: Analog Modulation (AM & FM)
Covers the implementation, simulation, and comparison of mathematical models for analog transceivers.
* **Amplitude Modulation (AM):** Modulating baseband signals and developing multiple demodulation techniques including Envelope Detection (evaluating RC time constants and diode saturation), Rectification+LPF, and Coherent Detection.
* **Sideband Variations:** Simulating and comparing DSB-SC, USSB, and LSSB modulation schemes.
* **Frequency Modulation (FM):** Implementing manual FM modulation/demodulation from scratch, applying Carson's rule for bandwidth estimation, and designing a frequency detector using a differentiator and envelope detector.
* **Bandwidth Efficiency:** Computing the 90% effective energy bandwidth ($B_{eff}$) for non-linear modulated waves.

### 🔹 Computer Assignment 3: Digital Communications & Noise Analysis
An advanced simulation of a digital communication link and a rigorous mathematical study of noise in linear systems.
* **Pulse Shaping:** Generating and comparing Power Spectral Densities (PSD) for NRZ Rectangular and Half-Sine BPSK base pulses.
* **Matched Filter Receiver:** Implementing optimal matched filtering, analyzing SQNR linearity, and plotting Eye Diagrams to observe ISI.
* **Monte Carlo BER Analysis:** Simulating data transmission over AWGN channels to plot experimental vs. theoretical BER curves for **BPSK, QPSK, and 16-QAM (Gray coded)**.
* **Analog Noise Modeling:** Deriving the SNR equations for a receiver front-end (RC High-Pass + Ideal LPF) and validating the theoretical analysis via time-domain Monte Carlo simulations.

---

## 🛠️ Technologies & Tools

- **MATLAB / Python** (Core environments for simulation and signal processing)
- **SciPy / Signal Processing Toolboxes** (Digital filter design, FFT computations, and convolutions)
- **Matplotlib / Data Visualization** (Plotting Semilog BER curves, Eye diagrams, and Constellation scatter plots)

## 🚀 How to Run

1. Clone this unified repository to your local system:
   ```bash
   git clone [https://github.com/VahidHamzeh/Communication-Systems-Assignments.git](https://github.com/VahidHamzeh/Communication-Systems-Assignments.git)
