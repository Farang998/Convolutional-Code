# Convolutional Coding and Viterbi Decoding - MATLAB Project

This project simulates convolutional encoding and decoding using MATLAB, as part of our coursework in digital communication systems.

## Project Overview

The goal was to understand and implement error correction using convolutional codes, and decode them using the Viterbi algorithm. The simulation covers:

- Encoding a binary input using convolutional codes
- Modulating the encoded data using BPSK
- Transmitting through an AWGN (Additive White Gaussian Noise) channel
- Demodulating the received signal
- Decoding the signal using hard or soft decision Viterbi decoding

The project focuses on evaluating the effect of different constraint lengths, code rates, and SNR levels on bit error rate (BER) performance.

## Structure

All code is written in a **single MATLAB file** that contains all relevant functions:
- Encoding
- State table generation
- BPSK modulation and demodulation
- Noise addition
- Viterbi decoding (with support for both hard and soft decision)

You can run the simulation by opening the main script in MATLAB and running it. Parameters such as SNR, code rate, input size, and decoding mode can be adjusted at the top of the file.

## Simulation Result 
<img width="490" alt="final_BER_all 1" src="https://github.com/user-attachments/assets/b61b4a57-9408-48e9-9a4e-c19b89a24f93" />

## Team Members

Project developed by Group G19 as part of CT216.  
Team members:
- Patel Dhruvil  
- Vadodariya Jenish  
- Tandel Dhruvinee  
- Dhamecha Ayush  
- Jainil Patel  
- Meet Patel  
- Hirapara Tarang  
- Vasava Harshil  
- Gori Faran  
- Somaliya Vatsal

## For More Details

For a deeper explanation of the algorithms, simulations, and results, refer to the full project report and presentation submitted with this project.
