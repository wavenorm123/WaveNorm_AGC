# WaveNorm_AGC

# Automatic Gain Control (AGC) Evaluation

This repository presents a comparative evaluation of three Automatic Gain Control (AGC) systems:

- **Carnival AGC**
- **WebRTC AGC**
- **WaveNorm AGC**

The evaluation is performed on:

- In-house generated speech dataset  
- TIMIT Speech Corpus  
- Voicebank+Demand Dataset  

---

## Objective

The goal of this project is to benchmark and compare different AGC systems across controlled and real-world speech datasets, evaluating:

- Loudness normalization performance
- Signal distortion
- Noise amplification behavior
- Speech intelligibility impact
- Dynamic range adaptation

---

##  Datasets

### In-House Dataset
- Custom recorded speech samples
- Multiple speakers (male/female)
- Various SNR conditions
- Controlled gain variations
- Simulated far-field and near-field recordings

---

### 2️⃣ TIMIT Speech Corpus
- Phonetically balanced speech dataset
- 630 speakers from 8 major dialect regions
- Clean speech recordings
- Widely used for ASR benchmarking

---

### 3️⃣ Voicebank Dataset
- Noisy speech dataset
- Used in speech enhancement research
- Contains paired clean and noisy speech samples
- Diverse background noise conditions

---

## ⚙️ Evaluated Systems

### 🎚️ WebRTC AGC
- Open-source AGC from WebRTC framework
- Widely used in VoIP and conferencing applications
- Real-time capable

### 🎚️ Carnival AGC
- Proprietary AGC implementation
- Adaptive dynamic gain control
- Optimized for speech clarity

### 🎚️ WaveNorm AGC
- Waveform-based normalization AGC
- Designed for consistent loudness output
- Lightweight implementation

---
