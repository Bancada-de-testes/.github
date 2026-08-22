# 🛠️ Project: Instrumented Test Bench for Drum Brakes

Welcome to the instrumentation development organization for a drum brake test bench.

This project focuses on developing dedicated electronics for signal acquisition, firmware for control, and a user interface for monitoring tribological tests.

## 🎯 Project Objective

The primary goal is to instrument and validate a test bench capable of extracting precise, real-time data on drum brake behavior under various operating conditions.

Testing focuses primarily on monitoring the following parameters:
*   **Brake lining wear**.
*   **Temperature**.
*   **Vibration**.

This infrastructure will serve as a foundation for academic research.

---

## 🏗️ System Architecture and Repositories

The project scope is modularized into the following repositories:

### ⚡ [`electronics`](https://github.com/Bancada-de-testes/electronics/tree/main)
Project hardware. Contains schematics, PCB layouts, and routing designs for data acquisition and signal conditioning (thermocouples, accelerometers, etc.), as well as datasheets and circuit simulations.

### 💻 [`firmware`](https://github.com/Bancada-de-testes/firmware/tree/main)
Embedded systems and sensing. Contains all code running on the microcontrollers responsible for sampling sensors, controlling test bench actuators, and processing initial telemetry.

### 🖥️ [`interface`](https://github.com/Bancada-de-testes/interface/tree/main)
Web-based visualization and control software. An application designed to receive real-time hardware data, plot wear and temperature graphs, and provide centralized, unified control of the tests. ### 📚 [`docs`](https://github.com/Bancada-de-testes/docs/tree/main)
Knowledge repository. Central repository containing theoretical foundations, articles, technical standards (SAE, ISO), bibliographic references, meeting minutes, and academic texts.

---

## 👥 Development Team

*   **Add**

---

*Project under development - 2026*
