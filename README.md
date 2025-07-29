# 8-Bit Arcade Game for STM32

## Project Overview
A fast-paced 8-bit style arcade game developed in embedded C on the STM32F031X6 microcontroller. This project showcases real-time embedded programming, low-level hardware control, and system integration.

## 🔧 Key Skills Gained
- **Real-Time Programming:** Timers, music playback, LED animations  
- **Hardware Integration:** `GPIO`, `PWM`, `UART`  
- **State Management:** Menu transitions, lives, and scoring system  
- **Debugging:** Addressed timing and memory constraints  
- **Teamwork:** Coordinated embedded development with hardware testing

## 🎮 Game Features
- **45-second Timer:** Collect coins before time runs out  
- **Dual Controls:**
  - Physical buttons
  - Serial terminal (`A` = left, `D` = right)  
- **Visual Feedback:** LED life indicators, heart animations  
- **Audio:** Chiptune music + sound effects  
- **UI Screens:** Welcome and Game Over displays  

## ⚙️ Technical Setup

**Hardware:**  
- STM32F031X6 MCU  
- Breadboard with LEDs and buttons  

**Software:**  
- PlatformIO in VS Code  
- Serial terminal (e.g. PuTTY)  

## 🕹️ How to Play
1. Flash the binary to the STM32 board  
2. Use either:
   - Onboard buttons, or  
   - Serial keyboard input via terminal (`A` = left, `D` = right)  
3. Catch as many coins as possible before time or lives run out!

## 📺 Game Preview
[![Game Demo](https://img.youtube.com/vi/XXBCwJLTPe4/0.jpg)](https://youtu.be/XXBCwJLTPe4)
