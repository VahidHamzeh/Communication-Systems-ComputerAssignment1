# Communication Systems - Computer Assignment 1

This repository contains the implementation of the first computer assignment for the **Communication Systems** course at **Sharif University of Technology**, instructed by **Dr. Behroozi**.

The project explores the fundamental concepts of signals, linear time-invariant (LTI) systems, noise filtering, and frequency-domain analysis through practical audio and signal processing tasks.

## 📌 Topics Covered

The assignment is divided into four main computational problems:

1. **System Identification using Cross-Correlation**
   - Generating a linear "chirp" probe signal.
   - Simulating acoustic room echoes and calculating the impulse response of an unknown system using cross-correlation.
   - Analyzing auto-correlation and cross-correlation properties in the time domain.

2. **Forensic Audio Cleanup: Spectral Analysis & Filtering**
   - Analyzing corrupted speech signals using Power Spectral Density (PSD) and Spectrograms.
   - Designing a **Notch Filter (Band-stop)** to remove high-frequency sinusoidal interference (whine).
   - Designing a **Low-Pass FIR Filter** to suppress Additive White Gaussian Noise (AWGN) while preserving speech energy.

3. **Channel Equalization (Inverse Filtering)**
   - Simulating signal distortion over a muffling FIR channel.
   - Designing an **Inverse Equalizer Filter** to reverse channel distortion and recover attenuated high frequencies from a voice recording.
   - Regularizing the ideal inverse response to prevent noise amplification at higher frequencies.

4. **Sampling Theorem, Aliasing, and DTMF Decoding**
   - Demonstrating the Nyquist-Shannon sampling theorem and visualizing the effects of aliasing in the frequency domain.
   - **DTMF Decoding:** Using spectrogram analysis to decode dual-tone multi-frequency (touch-tone) dialpad sequences from an audio signal.

## 🛠️ Technologies & Libraries Used

- **Python 3** (or MATLAB)
- **NumPy / SciPy** (for signal processing, FIR filter design, and convolutions)
- **Matplotlib** (for plotting time-domain signals, PSDs, and Spectrograms)

## 🚀 How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/VahidHamzeh/your-repo-name.git](https://github.com/VahidHamzeh/Communication-Systems-Simulation-Assignments1.git)
