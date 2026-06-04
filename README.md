# DermoSense Pro

**Smart Medical Patch for Rural Communities Without Physicians**

DermoSense Pro is a remote health monitoring system designed for elderly individuals residing in rural areas that lack permanent physicians or primary care facilities.

## Problem Statement

Kazakhstan has over 350 rural settlements without a resident physician. One in five rural inhabitants is over the age of 60. Myocardial infarctions, strokes, falls, and hypoxemia constitute the leading causes of mortality. A visiting nurse is physically incapable of conducting daily rounds to check on every at-risk patient.

## Solution

DermoSense Pro is an ultra-thin medical patch (1.8 mm) equipped with six embedded sensors:

| Sensor | Parameter |
|--------|----------|
| MAX30100 | Heart rate, SpO₂ |
| MPU6050 | Motion, fall detection |
| Temperature sensor | Body temperature |
| GSR sensor | Stress, dehydration |
| Sweat sensor | Febrile indicators |

### Intelligent Features

- **AI-Powered Temperature Prediction** — forecasts a febrile episode up to 1.5 hours in advance
- **Fall Detection** — accelerometer data coupled with an immobility timer
- **Pulse Wave Analysis** — early detection of arrhythmia
- **Autonomous Operation** — 5–7 days of continuous use, wireless charging
- **IP67 Water Resistance** — safe for showering

### System Architecture
[Patch] → Bluetooth → [Patient's Smartphone] → Internet → [Cloud] → [Physician Dashboard] → [Family App]


## Repository

This repository contains a web-based prototype of the physician dashboard and the mobile interface.

### Technology Stack

- HTML5 / CSS3 (Tailwind)
- JavaScript (Vanilla)
- Figma (design mockups)

### Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/dermosense-pro.git
```
2. Open `index.html` in any web browser.
Alternatively, download the ZIP archive and extract it.

### Project Structure

```
dermosense-pro/
├── index.html          # Physician web dashboard + patient interface
├── styles.css          # Stylesheet (or embedded within HTML)
├── script.js           # Status toggling logic, charting
└── README.md
```
