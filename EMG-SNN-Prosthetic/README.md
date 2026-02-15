# EMG-SNN-Prosthetic

An intelligent prosthetic arm control system using 
Electromyography (EMG) signals and a Spiking Neural Network (SNN).

Built on the STM32MP257F-DK platform, the system performs:

- EMG signal acquisition
- Spike encoding and preprocessing
- SNN training and weight export
- Real-time inference
- Motor/servo control

---

## Project Structure

- **Data_Preparation** – EMG preprocessing and spike encoding  
- **SNN_Training** – Model training and weight generation  
- **MCU_M33** – Cortex-M33 firmware (ADC, control, RPMsg)  
- **A35_Linux** – Cortex-A35 Linux-side inference  

---

Developed for STM Innovation Fair 2026.

