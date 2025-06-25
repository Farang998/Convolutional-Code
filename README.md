# Convolutional Coding and Viterbi Decoding

This repository contains a MATLAB-based implementation and analysis of convolutional coding and Viterbi decoding—a widely used error-correction method in digital communication systems.

## 🔍 Project Overview

The primary aim of this project is to simulate the complete transmission chain using:
- **Convolutional Encoding**
- **BPSK Modulation**
- **AWGN Channel Simulation**
- **Soft and Hard Decision Viterbi Decoding**

The goal is to evaluate system performance using Bit Error Rate (BER) as the key metric, under different noise conditions and coding parameters.

---

## 📁 Project Structure

- `Convolutional_Encoder.m`: MATLAB function to encode binary input using specified generator polynomials.
- `state_table_generator.m`: Creates state transition data for decoding.
- `BPSK_modulate.m`: Maps bits to symbols for transmission.
- `add_AWGN_noise.m`: Adds noise to simulate channel imperfections.
- `Demodulator.m`: Performs hard or soft demodulation based on input.
- `Viterbi_Decoder.m`: Core implementation of Viterbi decoding using dynamic programming.
- `main.m`: Script to run the full process (encode → modulate → add noise → decode).
- `plots.m`: Code for plotting BER vs. SNR graphs.
- `Convolutional_Codes_Project_Report.pdf`: Detailed write-up including background, equations, results, and theoretical analysis.
- `CT216_G19[1].pptx`: Presentation slides for summarizing project insights.

---

## 🧠 Key Concepts

- **Constraint Length (Kc)**: Determines how many past bits influence the output.
- **Code Rate (r)**: Ratio of input bits to output bits (e.g., 1/2 or 1/3).
- **Generator Matrix (Octal)**: Defines how bits are combined for redundancy.
- **Soft vs. Hard Decision Decoding**: Soft decision uses raw signal info; hard decision uses binary thresholding.

---

## ⚙️ How to Use

1. Open the project folder in MATLAB.
2. Run `main.m` to start the simulation.
3. Adjust parameters like `SNR`, `Kc`, and code rate inside `main.m` to see how performance changes.
4. Check the plotted graphs or exported data for BER performance.

---

## 📊 Observations

- **Lower code rates** (e.g., 1/3) yield better error correction but at the cost of bandwidth.
- **Higher constraint lengths** improve performance due to longer memory.
- **Soft decision decoding** provides better BER than hard decision, especially in low SNR scenarios.

---

## 📚 Reference Materials

For more details, in-depth explanation of the Viterbi decoding algorithm, simulation results, and performance comparison:

📄 View the full report: `Convolutional_Codes_Project_Report.pdf`  
📊 Refer the presentation: `CT216_G19[1].pptx`

---

## 🤝 Contributors

Team G19  
> Patel Dhruvil, Vadodariya Jenish, Tandel Dhruvinee, Dhamecha Ayush, Jainil Patel, Meet Patel, Hirapara Tarang, Vasava Harshil, Gori Faran, Somaliya Vatsal

---

