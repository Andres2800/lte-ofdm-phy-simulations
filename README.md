# LTE OFDM Physical Layer Simulations

This repository contains a collection of LTE-standard–compliant physical layer simulations implemented using Jupyter notebooks. The goal of these experiments is to model different transmission techniques used in LTE, visualize the impact of the channel, and evaluate performance through the reconstruction of a transmitted image.

All simulations implement full baseband processing, including modulation, OFDM/SC-FDM, cyclic prefix insertion, multipath fading, AWGN, demodulation, and BER computation.

## Features

### 1. **Baseline OFDM Transmission**
- Image loading and bit conversion  
- QPSK / 16-QAM / 64-QAM modulation  
- LTE OFDM modulation and cyclic prefix insertion  
- Multipath fading and AWGN  
- OFDM demodulation and image reconstruction  
- BER analysis  

### 2. **SC-FDM Transmission**
- All OFDM features  
- Additional DFT precoding to reduce Peak-to-Average Power Ratio (PAPR)  
- Aligned with LTE uplink processing  

### 3. **SC-FDM with Receive Diversity**
- SC-FDM transmission  
- Multiple receive antennas (SIMO)  
- Maximal Ratio Combining (MRC)

### 4. **SFBC (Space-Frequency Block Coding) Transmission**
- Two transmit antennas  
- OFDM-based Alamouti coding in frequency domain  
- Improved reliability in frequency-selective channels

### 5. **Digital Beamforming Transmission**
- Multiple transmit antennas  
- Digital beamforming weights  
- Directional transmission gain and improved SNR

### 6. **MIMO Transmission**
- Multiple transmit and receive antennas  
- Spatial multiplexing  
- Linear MIMO receivers (ZF/MMSE)

### 7. **OFDM with Channel Coding**
- Baseline OFDM  
- Channel coding (e.g., convolutional or Turbo coding)  
- Coding gain evaluation through BER

---

## Repository Structure

```
lte-ofdm-phy-simulations/
│
├── README.md
├── images/
│ └── test_image.png
│
├── notebooks/
│ ├── 01_ofdm_basic.ipynb
│ ├── 02_sc_fdm.ipynb
│ ├── 03_sc_fdm_rx_diversity.ipynb
│ ├── 04_ofdm_sfbc.ipynb
│ ├── 05_ofdm_beamforming.ipynb
│ ├── 06_mimo_transmission.ipynb
│ └── 07_ofdm_channel_coding.ipynb
```
---

## **Simulation File Names**
- **01_ofdm_basic.ipynb**  
- **02_sc_fdm.ipynb**  
- **03_sc_fdm_rx_diversity.ipynb**  
- **04_ofdm_sfbc.ipynb**  
- **05_ofdm_beamforming.ipynb**  
- **06_mimo_transmission.ipynb**  
- **07_ofdm_channel_coding.ipynb**

---
