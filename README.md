# Force Cell v2 — Hardware & BLE Software

Development repository for the **hardware and software of a custom force cell**, focused on improving the performance of the first prototype.

The main goal is to improve the **response speed** and **signal-to-noise ratio (SNR)** of the measurement system, while developing a reliable interface for data acquisition and monitoring.

## Project Structure

The project is divided into two main areas:

```text
.
├── hardware/          # Force cell hardware development
├── ble_app/           # Bluetooth Low Energy application
├── firmware/          # Embedded firmware
└── tests/             # Testing and characterization
```

### Hardware

Development and testing of the force cell, including:

* Sensor and measurement electronics
* Signal conditioning
* Noise reduction
* Acquisition speed optimization
* Hardware revisions and characterization

### BLE Application

Development of a **Bluetooth Low Energy (BLE)** application for communicating with the force cell and handling measurement data.

The application is intended for:

* Real-time data acquisition
* Device communication
* Measurement monitoring
* Data recording and analysis

## Development

The project follows an iterative approach, with new hardware and software revisions tested against the previous prototype.

Key performance parameters include:

* Response time
* Signal-to-noise ratio
* Measurement stability
* Sampling rate
* BLE communication reliability

**Status:** In development.
