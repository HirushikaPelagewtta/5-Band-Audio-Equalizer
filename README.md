# 5-Band Audio Equalizer

## Overview

This project is a **5-Band Audio Equalizer** that allows the adjustment of the output of different frequency bands within an audio signal. The equalizer is designed using **4th order Sallen-Key filters**, and the gain for each band can be adjusted individually. The outputs are displayed using a sound level indicator.

---

## Features

- **Adjustable Gain**: Gain can be controlled for 5 frequency bands.
- **Sound Level Indicators**: Visual indication of the output signal for each band.
- **High-Quality Audio Processing**:
  - Implemented using **4th order Sallen-Key filters**.
  - Each 4th order filter is created by cascading two 2nd order filters.
- **Low Noise and High Performance**: Built using **TL072 ICs**, known for their low noise, low distortion, wide bandwidth, and high slew rate.

---

## Frequency Bands

The five bands implemented in the equalizer are:

1. **20 Hz - 300 Hz** (Low Frequency)
2. **300 Hz - 1 kHz** (Low-Mid Frequency)
3. **1 kHz - 4 kHz** (Mid Frequency)
4. **4 kHz - 10 kHz** (Upper-Mid Frequency)
5. **10 kHz - 20 kHz** (High Frequency)

---

## Components Used

- **TL072 IC**: Selected for its excellent performance characteristics:
  - Low noise
  - Low distortion
  - Wide bandwidth
  - High slew rate
- **4th Order Sallen-Key Filters**: For accurate frequency band separation.

---

## Circuit Design

- **Filtering**: The 4th order Sallen-Key filters for each frequency band are created by cascading two 2nd order filters.
- **Gain Adjustment**: Adjustable gain controls for each band.
- **Output Display**: A sound level indicator is integrated to monitor the audio output.

---

## Usage

1. Connect the audio input signal to the equalizer.
2. Adjust the gain knobs for each band to suit your preferences.
3. Observe the output levels using the sound level indicators.
