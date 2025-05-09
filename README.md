# 🔊 Audio Amplifier Circuit

A low-power audio amplifier built using the **LM386 IC**, designed to faithfully reproduce audio signals with minimal distortion. This project demonstrates analog audio amplification using basic electronic components on both a breadboard and PCB.

---

## 🏫 Project Information

- **University:** Benha University, Faculty of Engineering (Shoubra)
- **Department:** Communications and Computer Engineering
- **Course:** Electronics

---

## 👩‍💻 Team Members

- Abdallah Mohamed Mohamed Galal  
- Abdelrahman Salah El-dein Abdelaziz  
- Mohamed Ahmed Mohamed Hassan  
- Farida Waheed Abdelbary  
- Razan Ahmed Fawzy  

---

## 📌 Project Overview

The purpose of this project is to:
- Amplify low-power audio signals for audible output through a speaker.
- Design and simulate the circuit using **Proteus** before real-world implementation.
- Build the final version on a **Printed Circuit Board (PCB)** for durability and performance.

---

## 🔍 Objectives

- Recreate input audio signals at appropriate volume and power.
- Ensure clarity with minimal distortion.
- Learn practical implementation of analog amplification.

---

## 🧠 System Features

- **Amplification IC:** LM386 low-voltage audio amplifier.
- **Output:** 4Ω, 3W speaker.
- **Input:** Via AUX cable (from phone or music player).
- **Volume Control:** 10kΩ potentiometer.
- **Power Source:** 9V battery.

---

## ⚙️ Components & Values

| Component              | Quantity | Value/Type         |
|------------------------|----------|--------------------|
| **LM386**              | 1        | Audio Amplifier IC |
| **Resistors**          | 4        | 1.2kΩ, 10Ω, 1kΩ (x2)|
| **Capacitors**         | 7        | 10nF, 0.1µF (x2), 10µF (x2), 100µF, 1000µF |
| **Potentiometer**      | 1        | 10kΩ               |
| **Speaker**            | 1        | 4Ω 3W              |
| **AUX Female Jack**    | 1        | Audio input jack   |
| **Battery**            | 1        | 9V                 |
| **Switch**             | 1        | ON/OFF rocker      |
| **Battery Connector**  | 1        | 9V clip            |
| **Terminal Blocks**    | 2        | 2-pin & 3-pin      |
| **PCB Board**          | 1        | Soldered design    |
| **Wires & Soldering Iron** | -    | For assembly       |

---

## 🧾 How It Works

1. The audio signal enters through the **AUX jack**.
2. The **LM386** amplifies the signal using components configured to boost gain.
3. The output passes through a **capacitor** to filter DC offset.
4. A **potentiometer** allows volume adjustment.
5. The final signal is sent to the **speaker** for sound output.
6. A **switch** controls power from a 9V battery.

---

## 🖼 Circuit Design Process

### 🔧 Project Stages:
- Designed and simulated in **Proteus 8.1**
- Validated component values and functionality
- Built circuit on **breadboard** for testing
- Finalized soldered **PCB version**
- Connected mobile device via AUX to play music

---

## 🧪 Testing Results

| Test Step                        | Expected Result          | Status |
|----------------------------------|---------------------------|--------|
| AUX input signal                 | Clean amplified output    | ✅     |
| Volume control via potentiometer| Adjustable output level   | ✅     |
| Component connection on PCB     | Functional after soldering| ✅     |
| Audio from mobile to speaker    | Clear and amplified sound | ✅     |

---

## 📷 Images

> Add these screenshots when uploading to GitHub:
- **Proteus simulation schematic**:
  ![image](https://github.com/user-attachments/assets/31845e1e-a22b-444a-8031-c43e6d48e8db)
- **Breadboard implementation**:
  ![image](https://github.com/user-attachments/assets/dcf7f2ce-3b09-493b-9693-981831f8d90f)
- **PCB design and final working product**:
  ![image](https://github.com/user-attachments/assets/fa59a727-b196-471b-8ca8-00bca063c4a8)
  ![image](https://github.com/user-attachments/assets/23ecfd0b-b458-4e58-8aab-8e974a608612)

---

## 🛠 Tools Used

- **Proteus 8.1** – Circuit simulation
- **Soldering Iron** – Component attachment
- **PCB Board** – Hardware integration
- **Multimeter** – Testing and measurement

