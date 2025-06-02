# 🌱 Smart Farming Tanoto Scholars Association (TSA) UB X IoT UB

![Implementasi](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/Dokumentasi-1_Implementasi.jpg)

## 📚 Background
Agriculture remains the backbone of food security in Indonesia. However, many small-scale farmers still rely on traditional irrigation methods and manual monitoring, which are time-consuming, inefficient, and prone to human error. These limitations often result in over-irrigation, under-fertilization, or poor soil condition management, impacting crop productivity and sustainability.

This project is implemented in **Pujon Village, Malang Regency**, where **TSA UB** and **IoT UB** aim to carry out a community service program. The initiative focuses on supporting the **local farming community in Pujon** by introducing technology-driven solutions to improve crop production outcomes.

## ❗ Problem Statement
Farmers face challenges in:
* Monitoring soil and environmental conditions in real-time.
* Determining optimal irrigation timing and nutrient application.
* Minimizing water and fertilizer waste.

Manual practices make it difficult to maintain consistency and precision in agricultural operations.

## 🌟 Objective
This project aims to:
* Develop an Internet of Things (IoT)-based system for remote irrigation control.
* Enable real-time monitoring of soil and atmospheric parameters.
* Assist farmers in making data-driven decisions to optimize crop yield and resource usage.

---

## ♻️ System Flowchart
This smart farming consists of two systems:

**a. Remote Irrigation Control**

![Flowchart – Irrigation System](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/flowchart-irrigation.png)

**b. Environmental and Soil Condition Monitoring**

  * Air Temperature 🌡️
  * Air Humidity 💧
  * Soil Temperature 🌱
  * Soil Moisture 🌾
  * Soil pH 🧪
  * Soil NPK Levels ⚗️

![Flowchart – Monitoring System](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/flowchart-monitoring.png)

---

## 🧰 Components Used
**Microcontroler**
  * ESP32

**Sensors**
  * DHT22 (air temperature and humidity)
  * NPK sensor (7in1: NPK levels, soil pH, soil moisture, soil temperature) + MAX485 (to communicate with ESP)

**Actuator**
  * Solenoid Valve 12VDC + relay module 2 channel 5V
    
**Database**
  * Google Firebase
    
**App**
  * Kodular

**Others**
  * Power supply 12V 5A
  * Step down DC-DC
  * Outdoor electrical panel box
  * Sprinkler and drip hose

---

## 🔌 Circuit Schematic
![Schematic Documentation](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/Dokumentasi-10_Skematik.png)

---

## 📐 PCB Design
**a. Remote Irrigation Control**

![PCB Documentation](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/Dokumentasi-2_PCB.jpg)

**b. Environmental and Soil Condition Monitoring**

![PCB Documentation](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/Dokumentasi-3_PCB.jpg)

---

## 📱 Application Design
We use Kodular to make functional app which shows data from Google Firebase

a. Designing UI

![Application Development](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/Dokumentasi-7_Pembuatan%20Aplikasi.jpg)

b. Creating app logic with drag-and-drop Kodular's feature

![Application Development](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/Dokumentasi-8_Pembuatan%20Aplikasi.jpg)

c. Final app look

![Application Development](https://raw.githubusercontent.com/stnrliza/iot-smart-farming/main/images/Dokumentasi-9_Pembuatan%20Aplikasi.jpg)

---

## 📂 File Structure (To be added soon)
* `PCB.fzz` – Fritzing design
* `wiring.json` – Pin mapping
* `app_ui.png` – Application mockup
* `flowchart.drawio` – System flowchart
* `sensor_test.csv` – Sample sensor data
* `firmware.ino` – ESP32 firmware

---

## 👥 Development Team
* Tanoto Scholars Association (TSA) UB
* IoT UB

---

## 🌍 Impact & Alignment
* Supports sustainable agriculture through smart technology (SDGs: 2, 9, 12, 13)
* Empowers small-scale farmers with accessible digital solutions
* Enhances student understanding of real-world IoT application

---

> *This repository is part of a personal project portfolio and showcases our collaborative work in developing practical IoT solutions for agriculture.*
