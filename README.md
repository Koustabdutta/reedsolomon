# 🚀 Reed–Solomon + Neural Network Error Correction for Satellite Telemetry

**Author:** Koustab Dutta  
**Affiliation:** Department of Data Science & Artificial Intelligence, RKMRC, Calcutta University  
**Email:** koustabduttaofficial@gmail.com

This project implements and compares **Reed–Solomon (RS)** error correction with a **Neural Network-based decoder** for handling noisy and burst-corrupted satellite telemetry data. It demonstrates a hybrid AI + classical coding approach for forward error correction (FEC) in space communication systems.

---

## 🛰️ Project Overview

Satellite telemetry data is prone to:
- **Random noise** (from transmission)
- **Burst errors** (from radiation and cosmic rays)

To handle this, we implemented:
- ✅ **RS(255,239)** encoder and decoder over GF(256)
- 🤖 A deep **neural network decoder (autoencoder-style)**
- 📉 Performance comparison: Bit Error Rate (BER), decoding latency, and robustness
- 💾 Logging and storage via SQLite database

---

## 📦 Technologies Used

- Python, NumPy, Pandas
- [reedsolo](https://pypi.org/project/reedsolo/) for RS coding
- TensorFlow / Keras (Neural Network)
- Matplotlib (Visualization)
- SQLAlchemy (DB export)
- Jupyter Notebook

---

## 📁 Structure

