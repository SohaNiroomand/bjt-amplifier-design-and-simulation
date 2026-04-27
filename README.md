# 🔌 BJT Amplifier Design & Simulation

This project presents the design, analysis, and simulation of a multi-stage BJT amplifier, including DC biasing, small-signal analysis, transient response, and harmonic distortion evaluation.

---

## 📌 Overview

The goal of this project is to design a BJT-based amplifier circuit that:

- Achieves a stable DC operating point
- Provides a desired voltage gain
- Maintains acceptable input resistance
- Produces a clean (non-clipped) output signal
- Minimizes harmonic distortion (THD)

The design is verified using both hand calculations and LTspice simulations.

---

## ⚙️ Circuit Description

The amplifier consists of three BJT stages (Q1, Q2, Q3):

- Stage 1 (Q1): Input amplification  
- Stage 2 (Q2): Intermediate gain stage  
- Stage 3 (Q3): Output stage  

The circuit includes:
- Biasing resistors for DC stability  
- Coupling capacitors for AC signal transfer  
- Emitter resistors for stabilization  
- Load resistance at output  

---

## 🔍 1. DC Analysis (Biasing)

The DC operating point (Q-point) was calculated manually and compared with simulation results.

### Key Results

| Transistor | Parameter | Hand Calc | Simulation |
|------------|----------|-----------|------------|
| Q1 | VCE | 1.95 V | ~1.98 V |
| Q1 | IC | 0.54 mA | ~0.53 mA |
| Q2 | VCE | 1.79 V | ~1.71 V |
| Q3 | VCE | 2.49 V | ~2.46 V |

---

## 📈 2. AC Analysis (Small-Signal)

- Voltage Gain: Av ≈ 20.7  
- Input Resistance: Rin ≈ 10.4 kΩ  

---

## ⏱️ 3. Transient Analysis

Input:
- Sine wave
- Frequency: 5 kHz
- Amplitude: 50 mV

Result:
- Output ≈ 1V peak
- No clipping observed

---

## 📉 4. Harmonic Distortion (THD)

- Total Harmonic Distortion (THD): 2.76%

---

## 🧪 Simulation Tools

- LTspice

---

## 🧠 Key Takeaways

- Proper biasing ensures stable operation  
- Cascaded stages increase gain  
- Capacitors isolate DC and pass AC  
- Trade-offs exist between gain, linearity, and distortion  

---

## 👤 Author

Soha Niroomand  
Student ID: 403170569
