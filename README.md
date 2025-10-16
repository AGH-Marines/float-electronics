# AGH MARINES Measurement Float Electronics

This repository contains the electronic designs for the AGH MARINES autonomous measurement float.  
It includes schematics, PCB layouts, and block diagrams for the main control board, power distribution, and receiver modules.

---

## Project Structure

- **`Float_Main_PCB`** – Main PCB of the float, based on STM32F401, including EEPROM storage and NRF24 RF communication.  
- **`Float_Power_PCB`** – Power PCB featuring a 12V to 3.3V DC-DC step-down (buck) converter, stepper motor driver (DRV8825 StepStick), and filtering capacitors.  
- **`Float_Receiver_PCB`** – Receiver PCB, receiving data via NRF24 RF module and transmitting it to a PC via USB serial.

---

## Tools & Software

- **Altium Designer** – PCB and schematic design software

---