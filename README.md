# 🔘 ATmega16 LED Control with Button – Embedded Project

This project demonstrates a simple yet effective embedded system using **ATmega16** microcontroller. The goal is to control **7 LEDs** connected to the same port as a **push button**. When the user **presses the button**, all LEDs **turn on for one second**, then **turn off automatically**.

---

## 📁 Project Files

| File Name           | Description |
|---------------------|-------------|
| `FINALPROJECT.pdsprj` | Proteus project file – open with Proteus to view the full simulation |
| `FINA.hex`           | Compiled HEX file – upload into ATmega16 in Proteus to run the project |
| `README.md`          | Project documentation (this file) |

---

## 🌐 Live Preview

> https://github.com/user-attachments/assets/0b96aa93-12df-4462-8ce9-77088b4b2801
 ---

## 🧠 Project Overview

### 🔹 Objective

- Use **Port A** of **ATmega16** for both **output (LEDs)** and **input (Button)**.
- When the **button is pressed**, the 7 LEDs **turn on for 1 second**, then **automatically turn off**.

### 🔹 Components Used

- ATmega16 Microcontroller
- 7x LEDs
- 1x Push Button
- Resistors
- Breadboard or Proteus simulation
- Optional: External Crystal (for timing stability)

---

## 🔌 Circuit Description

- **PORTA** pins are connected to 7 LEDs (PA0 to PA6) and 1 push button (PA7).
- The push button is configured as input with internal or external pull-up.
- All LEDs are configured as outputs.
- On button press (logic low), the microcontroller turns on all LEDs, waits 1 second, then turns them off.

---

## ⚙️ How to Run the Simulation (Proteus)

1. Open `FINALPROJECT.pdsprj` in **Proteus**.
2. Double-click on the **ATmega16** component.
3. In the **Program File** section, load the `FINA.hex` file.
4. Run the simulation.
5. Press the virtual push button.
6. You should see all 7 LEDs turn on for 1 second, then turn off.

---


