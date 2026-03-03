# TouchstoneLab

A web-based **Touchstone (.s1p, .s2p, .s3p, .s4p)
S-Parameter analysis tool** built with Plotly.js and TailwindCSS.

TouchstoneLab enables engineers to visualize, analyze, and measure RF
network parameters directly in the browser --- no installation required.

------------------------------------------------------------------------

## 🚀 Features

-   Full Touchstone file support (.s1p / .s2p / .s3p / .s4p)
-   Multi-dataset overlay
-   Magnitude (dB)
-   Phase (deg)
-   Return Loss (dB)
-   VSWR
-   Group Delay (ns)
-   Impedance (R + jX)
-   Interactive Smith Chart
-   Marker placement with data table
-   Automatic bandwidth measurement
-   Log / Linear frequency scaling
-   Custom frequency range input (k / M / G supported)
-   Responsive layout (desktop + mobile)
-   Double-click fullscreen plots
-   Fully client-side (no server required)

------------------------------------------------------------------------

## 📷 Overview

TouchstoneLab provides a modern RF-style dark UI optimized for
high-clarity engineering visualization.

Ideal for: - RF Engineers - Antenna Designers - PCB Designers - SDR
Developers - Microwave Engineers - Students working with VNA
measurements

------------------------------------------------------------------------

## 🛠 How It Works

The application:

1.  Parses Touchstone files
2.  Converts S-parameters to complex form (RI / MA / DB supported)
3.  Computes:
    -   Magnitude
    -   Phase (unwrapped)
    -   Return Loss
    -   VSWR
    -   Group Delay
    -   Impedance from reflection coefficient
4.  Renders interactive plots using Plotly.js

All processing happens locally in your browser.

------------------------------------------------------------------------

## 📊 Bandwidth Measurement

Bandwidth can be measured based on:

-   Return Loss threshold
-   Insertion Loss threshold

Automatic detection switches between RL and IL based on selected
S-parameter.

------------------------------------------------------------------------

## 📜 License

MIT License

You are free to use, modify, and distribute this software.
