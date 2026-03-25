# 🖐️ Bionic Robot Hand using Flex Sensors

##  Overview
This project implements a **bionic robotic hand** that mimics human finger movements using **flex sensors** and **servo motors**.  
Each finger is controlled independently, allowing the robot hand to replicate real hand gestures in real time.

The system reads the bending of each finger through flex sensors and maps it to corresponding servo motor angles.

---

##  Features
- Real-time finger motion replication  
- Independent control of 5 fingers  
- Simple and intuitive human-to-robot interaction  
- Analog sensor input mapped to servo positions  
- Lightweight and low-cost design  

---

## How It Works
- Each finger is equipped with a **flex sensor** that changes resistance when bent.  
- The Arduino reads analog values from the sensors.  
- These values are mapped to angles (0°–180°).  
- Each **servo motor** moves accordingly to replicate the finger movement.  

---

##  Hardware
- Arduino Uno  
- 5 × Servo Motors (one per finger)  
- 5 × Flex Sensors  
- Resistors (for voltage divider with flex sensors)  
- Power supply  
- Mechanical hand structure  

---

##  Pin Configuration
- Flex Sensors → Analog pins (A0 – A4)  
- Servo Motors → Digital PWM pins  

---


## 📸 Demo<img width="499" height="802" alt="Screenshot 2025-08-16 at 12 48 22 AM" src="https://github.com/user-attachments/assets/4a4dcaea-3b6c-43ef-8306-ffe074d84126" />



---

## 📈 Future Improvements
- Add wireless control (Bluetooth / nRF)  
- Improve finger precision using calibration  
- Integrate machine learning for gesture recognition  
- Add force feedback for realistic interaction  

