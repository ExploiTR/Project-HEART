# Project-HEART

Final Year Project for my B.Tech in 2022. 
> #### I was advised to improve the product to apply patent for it, but let knowledge be OPEN because internet helped me make it - all the credit goes back to it!!
If you're copying stuff just cite the project - it won't hurt your GPA!

## Overview

Project-HEART is an automated and portable heart disease analyzer that integrates hardware and software for real-time ECG monitoring and arrhythmia analysis. The system uses an ESP8266 (or any WiFi-enabled Arduino) connected to an AD8232 ECG sensor to capture heart signals. Users can view their ECG graph in real time and analyze the data using a deep neural network (DNN) model (TensorFlow Lite) within the Android app.

## Features

- **Hardware Integration:** Connects to ESP8266/Arduino devices with AD8232 ECG sensors over WiFi.
- **Android Application:** Visualizes ECG signals and provides arrhythmia classification using an on-device TensorFlow Lite model.
- **Machine Learning:** Uses a DNN trained on the Kaggle ECG dataset to analyze heartbeats for arrhythmia detection.
- **Portable and Automated:** Designed for easy deployment and use in various environments.

## Getting Started

### Hardware Requirements

- ESP8266 or any WiFi-enabled Arduino board
- AD8232 ECG Sensor
- (Optional) SSD1306 OLED display

### Software Requirements

- Android Studio (for compiling the app)
- Arduino IDE (for flashing the microcontroller)
- Outdated library dependencies may require code modifications for compatibility.

### Dataset

- [Kaggle ECG dataset](https://www.kaggle.com/datasets/sadmansakib7/ecg-arrhythmia-classification-dataset) (used for training the machine learning model)

## Usage

1. Set up the hardware (ESP8266/Arduino + AD8232 sensor) and upload the firmware.
2. Install and run the Android app.
3. Connect the app to the device over WiFi.
4. Visualize ECG signals in real time.
5. Use the built-in analysis tool to classify heartbeats and detect arrhythmias.

> **Note:** This project code is outdated and may not work with the latest libraries without modifications.

## License

This project is licensed under the Apache 2.0 License.
