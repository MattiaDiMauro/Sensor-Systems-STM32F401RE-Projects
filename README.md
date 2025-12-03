# STM32 Projects  

**Authors:** Albrigi P., Biondi F., Castelli L., Di Mauro M., Niro C.  
**Politecnico di Milano – 2025**

Series of hands-on embedded projects developed on the **STM32F401RE** Nucleo board using **STM32CubeIDE**.  
The projects cover embedded programming, peripheral configuration and integration of sensors and actuators.

## Main Topics
- GPIO configuration  
- Timers & Interrupts  
- PWM generation  
- DMA for UART / ADC / I²C  
- ADC acquisition (potentiometer, temperature sensor, Vref)  
- Communication interfaces: **USART**, **SPI**, **I²C**  
- LCD Display  
- Keyboard scanning  
- MEMS accelerometer (I²C + I²C DMA)  
- IR Tx/Rx communication  
- LED Matrix (SPI)  
- Microphone-based interaction  
- Speaker driver for audio playback  

All projects are written in **C** and include `.ioc` configuration files.

---

## Requirements
- **STM32CubeIDE**
- **C**
- **Visual Studio Code** 

---

## How to Use the Projects
1. Open STM32CubeIDE  
2. Create a new STM32 project with the ioc. file in the "Homework xx" folder
3. Copy and paste the main code from the "Homework xx" folder
4. Build and flash to the board

---

## Repository Structure

Each homework/project has:
- `/Src` and `/Inc` folders
- The `.ioc` file
- Lab report

---

## License
Educational purposes – Politecnico di Milano (2025)
