# Geothermal Eruption Prediction (Edge AI & IoT)

## 📌 Overview
An end-to-end IoT system designed to predict geothermal activity using Edge AI. This project uses an ESP32 for data collection and a Raspberry Pi to run real-time inference using a TensorFlow Lite model.

## 🚀 My Key Contributions
* **ML Integration:** Implemented and optimized the `geothermal_eruption_model.tflite` for edge deployment.
* **System Orchestration:** Developed `raspi_manager.py` to handle data flow between hardware and the AI model.
* **Data Engineering:** Conducted exploratory data analysis and feature engineering in the `ESP32 Notebook.ipynb`.

## 📂 File Guide
- `raspi_manager.py`: Main management script for Raspberry Pi.
- `geothermal_eruption_model.tflite`: Optimized TinyML model.
- `control.py`: System control logic based on prediction outputs.
- `esp32.c`: Firmware for hardware sensor data acquisition.
