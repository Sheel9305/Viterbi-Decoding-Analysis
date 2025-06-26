# Hard vs. Soft Viterbi Decoding for Convolutional Codes

This MATLAB project simulates and compares **Hard Decision Decoding (HDD)** and **Soft Decision Decoding (SDD)** for convolutional codes over an **AWGN** channel using **BPSK modulation**.

> 📘 **Course:** CT216 – Communication Systems  
> 👥 **Group Project** | 🎯 *My Contribution:* Implemented the **Hard Decision Decoder** and led **performance analysis presentation**

---

## 🧠 Overview

- Simulates convolutional encoding and decoding using Viterbi algorithm.
- Evaluates BER for both hard and soft decoding over varying Eb/N0 (SNR) values.
- Codes tested:
  - r = 1/2, Kc = 3  
  - r = 1/3, Kc = 4  
  - r = 1/3, Kc = 6
- Includes both **simulation** and **theoretical** BER curves.

---

## 🚀 Features

- Single pdf file includes:
  - Convolutional encoding logic
  - HDD and SDD decoding
  - BER computation
  - Graph plotting for comparison

---

## 📂 Files

- `viterbi_decoder.pdf` – Main MATLAB script containing full simulation logic in pdf format with results
- `CT216_Viterbi_Presentation.pptx` – Group presentation slides
- `Technical_Report.pdf` – Complete analysis and derivation report

---

## 🧪 How to Run

1. Open `viterbi_decoder.m` in MATLAB or Octave.
2. Run the script — it will:
   - Simulate encoding/decoding
   - Add AWGN noise
   - Compute and plot BER for all 3 configurations

---

## 📊 Output

The script generates BER vs. Eb/N0 plots comparing:
- Theoretical BER
- Hard Decision BER
- Soft Decision BER

---

## 📌 Tools Used

- MATLAB / GNU Octave
- BPSK modulation, AWGN noise
- Viterbi decoding (hard and soft)
- Euclidean and Hamming distance metrics

---

## 📄 License

This project is part of academic coursework and is open for educational/research use.

