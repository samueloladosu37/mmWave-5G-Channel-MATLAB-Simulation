# 📡 mmWave 5G Channel Simulation

This repository contains MATLAB implementations for simulating **5G millimeter-wave (mmWave)** uplink (UL) and downlink (DL) wireless channels. The simulations include **Angle of Arrival (AoA) estimation**, **transmit beamforming**, and general modeling of mobile equipment behavior in a 5G mmWave environment.

---

## 🔍 Key Features

- 📶 **Downlink (DL) Channel Simulation**  
  Models the transmission path from base station to user equipment in a mmWave system.

- 📡 **Uplink (UL) Channel Simulation**  
  Simulates the return path from user equipment to the base station.

- 🎯 **Angle of Arrival (AoA) Estimation**  
  Estimates the direction from which signals are received using multiple antennas or spatial filtering techniques.

- 🔊 **Transmit Beamforming**  
  Focuses the transmitted signal toward a specific user or direction using phased arrays.

---

## 📁 Project Structure

```plaintext
mmWave-5G-Channel-Simulation/
├── AOA_Estimation.m             # MATLAB script for Angle of Arrival estimation
├── Transmit_Beamforming.m       # Beamforming simulation and visualization
├── Uplink_Channel_Sim.m         # mmWave uplink channel simulation
├── Downlink_Channel_Sim.m       # mmWave downlink channel simulation
└── README.md
