# DermoSense Pro

**Smart Medical Patch for Villages Without Doctors**

DermoSense Pro is a remote health monitoring system for elderly residents of rural areas where there are no permanent doctors or paramedic stations.

## Problem

In Kazakhstan, there are over 350 villages without doctors. One in five rural residents is over 60 years old. Heart attacks, strokes, falls, and low oxygen levels are the leading causes of death. A nurse cannot physically visit every patient on a daily basis.

## Solution

DermoSense Pro is a thin medical patch (1.8 mm thick) equipped with 6 sensors:

| Sensor | Parameter |
|--------|-----------|
| MAX30100 | Heart rate, SpO₂ |
| MPU6050 | Motion, fall detection |
| Temperature sensor | Body temperature |
| GSR sensor | Stress, dehydration |
| Sweat sensor | Fever |

### Smart Features

- **AI-based temperature forecasting** — predicts fever onset 1.5 hours in advance
- **Fall detection** — accelerometer + inactivity timer
- **Pulse wave analysis** — early detection of arrhythmia
- **Battery life** — 5–7 days, wireless charging
- **IP67 water resistance** — shower-safe

### Architecture

`[Patch] → Bluetooth → [Patient's phone] → Internet → [Cloud] → [Doctor dashboard] → [Relatives app]`

## Repository

This repository contains a web prototype of the doctor dashboard and mobile interface.

### Technologies

- HTML5 / CSS3 (Tailwind)
- JavaScript (Vanilla)
- Figma (design mockups)

### Installation and Setup

1. Clone the repository:
```bash
git clone https://github.com/romiisromie/DermoSense-Pro.git
```

2. Open `index.html` in any browser

Alternatively, simply download the ZIP archive and extract it.

### Structure

```
dermosense-pro/
├── index.html          # Doctor dashboard + patient interface
├── styles.css          # Styles (or embedded in HTML)
├── script.js           # Status switching logic, graphs
└── README.md
```

Co-authored-by: rkht111 <111953531+rkht111@://github.com>
