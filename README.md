# Hard vs. Soft Viterbi Decoding for Convolutional Codes

This MATLAB project simulates and analyzes the performance of convolutional codes using both **Hard Decision Decoding (HDD)** and **Soft Decision Decoding (SDD)** techniques over an **AWGN** channel with **BPSK modulation**.

> 📘 **Part of academic coursework (CT216 – Communication Systems)**  
> 👥 **Group Project** | 🎯 *My Contribution:* Implemented Soft Decision Decoding module and led the performance analysis presentation.

---

## 🧠 Project Overview

- Simulates convolutional encoding with different generator matrices and constraint lengths.
- Compares bit error rates (BER) of HDD vs. SDD over varying SNR (Eb/N0) levels.
- Evaluates decoding performance for:
  - Code 1: r = 1/2, Kc = 3  
  - Code 2: r = 1/3, Kc = 4  
  - Code 3: r = 1/3, Kc = 6

---

## 🚀 Features

- Custom implementation of:
  - Viterbi Hard Decision Decoder using **Hamming distance**
  - Viterbi Soft Decision Decoder using **Euclidean distance**
- Generation of BER vs. Eb/N0 curves
- Comparison with **theoretical BER bounds**
- Modular design with separate `.m` files for:
  - State diagram generation
  - Encoding
  - Decoding (HDD & SDD)

---
