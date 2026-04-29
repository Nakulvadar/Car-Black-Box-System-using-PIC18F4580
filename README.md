# 🚗 Car Black Box System with Real-Time Event Logging using PIC18F4580

---

## 📌 Overview

This project implements an embedded **Car Black Box System** that records real-time vehicle data such as speed, gear position, and timestamped events. The system stores logs in EEPROM and allows retrieval via UART, similar to an automotive event data recorder.

---

## ⚙️ Features

* ⏱ Real-Time Clock integration (DS1307)
* 📊 Speed measurement using ADC
* ⚙️ Gear position tracking via keypad
* 💾 EEPROM-based event logging (circular buffer)
* 📟 16x2 LCD dashboard display
* 📋 Menu-driven user interface
* 📤 UART-based log download
* 🕒 Time configuration with user input

---

## 🛠️ Hardware Components

* PIC18F4580 Microcontroller
* DS1307 RTC Module
* 16x2 LCD Display
* Matrix Keypad
* EEPROM (Internal)
* ADC Input (Speed simulation)

---

## 💻 Software Tools

* MPLAB X IDE
* XC8 Compiler
* Embedded C

---

## 📂 Project Structure

```
car-black-box/
│
├── src/
│   ├── main.c
│   ├── black_box.c
│   ├── adc.c
│   ├── clcd.c
│   ├── uart.c
│   ├── eeprom.c
│   ├── ds1307.c
│   ├── keypad.c
│
├── include/
│   ├── black_box.h
│   ├── adc.h
│   ├── clcd.h
│   ├── uart.h
│   ├── eeprom.h
│   ├── ds1307.h
│
├── docs/
│   ├── hardware_setup.jpg
│   ├── lcd_output.jpg
│
├── README.md
└── .gitignore
```

---

## 🚀 Working Principle

1. System reads speed from ADC input
2. Gear input is captured using keypad
3. Time is fetched from DS1307 RTC
4. Data is stored in EEPROM as event logs
5. LCD displays real-time dashboard
6. Logs can be viewed or downloaded via UART

---

## 📌 Applications

* Vehicle monitoring systems
* Accident data recording
* Driver behavior analysis
* Embedded automotive systems

---

## 🔧 Key Concepts Used

* Embedded C Programming
* Peripheral interfacing (ADC, UART, I2C)
* EEPROM memory management
* Real-Time Clock handling
* State machine-based menu system

---

## 📈 Future Improvements

* CAN communication (automotive standard)
* GPS integration for location tracking
* SD card storage for extended logging
* RTOS-based task management

---

## 👨‍💻 Author

Nakul Anil Vadar
Embedded Systems & IoT Developer

---
