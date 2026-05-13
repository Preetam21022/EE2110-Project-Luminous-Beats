# 🎶 EE2110 Project: Luminous Beats

**Course Code:** EE2110  
**Objective:** Design a system that lights LEDs in response to sound without using any digital components or microcontrollers.

---

## 📌 Project Overview

*Luminous Beats* is an analog electronics project where LEDs respond to sound intensity in real time using a microphone-based sensing system and transistor switching. The entire system is built using discrete components, focusing on analog signal processing and switching circuits.

---

## 💡 Initial Idea

We initially planned to build the system using:

- Electret condenser microphone  
- Discrete BJT preamplifier stage  
- BC547 transistor LED driver  

However, due to the unavailability of a condenser microphone, we had to revise the design approach.

---

## 🔧 Final Design

We redesigned the system using:

- HW-484 V0.2 sound sensor module  
- 47kΩ base resistor  
- 5× BC547 transistor switches  
- 5 LEDs  
- 9V power supply  

The HW-484 module includes an internal microphone amplifier, which significantly improved stability and simplified the circuit design.

---

## ⚙️ How It Works

- The microphone detects sound waves and produces a small analog voltage signal.  
- The HW-484 module amplifies and conditions this signal.  
- The output is fed to the base of BC547 transistors through a 47kΩ resistor.  
- Each transistor acts as a switch to control individual LEDs.  
- LED activation depends on sound intensity levels.

---

## 📊 Results

- Real-time analog response  
- 5-level LED indication based on sound intensity  
- No microcontrollers or programming involved  
- Low-cost implementation (~BDT 270)  

---

## 🧠 Learning Outcome

One key insight from this project was that building the amplification stage manually would have provided deeper understanding of analog signal conditioning and biasing techniques.

However, using the HW-484 module helped achieve a stable and reliable system, making the project practical and fully functional.

---

## 🏷️ Tags

#CircuitDesign #AnalogElectronics #TransistorSwitching #EE2110 #UniversityProject