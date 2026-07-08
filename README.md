# 2nd-order-Active-Low-Pass-Filter-Macro-Model-OTA-
Design and simulation of 2nd-order OTA-based Butterworth, Bessel, and Chebyshev low-pass filters (10 kHz) using a 60 dB, 20 MHz UGB macro-model OTA in Tanner EDA.
# 2nd-Order OTA-Based Active Low-Pass Filter (10 kHz)

## Overview
Designed and analyzed three 2nd-order OTA-based active low-pass filters using a macro-model operational transconductance amplifier (OTA).

The project implements:
- Butterworth
- Bessel
- 3 dB Chebyshev


## OTA Specifications
- DC Gain: 60 dB
- Unity Gain Bandwidth (UGB): 20 MHz
- Macro-model implementation using VCCS, output resistance and capacitance.

## Filter Specifications
- Order: 2
- Cutoff Frequency: 10 kHz
- Topology: OTA-based Sallen-Key


## Design Parameters

| Filter | C1 | C2 | R1 | R2 |
|---------|----|----|------|------|
| Butterworth | 1 pF | 11.77 pF | 21.5 MΩ | 1 MΩ |
| Bessel | 1 pF | 7.56 pF | 20.64 MΩ | 1 MΩ |
| Chebyshev (3 dB) | 1 pF | 26.5 pF | 13.5 MΩ | 1 MΩ |

## Methodology
- Designed a macro-model OTA with 60 dB DC gain and 20 MHz UGB.
- Calculated filter component values using quality factor(Q) and frequency scaling factor(FSF).
- Implemented Butterworth, Bessel, and Chebyshev filter responses.

## Tools
- Tanner EDA
- Texas Instruments Active Low-Pass Filter Design Guide
