# Planetary Gear Actuation System

## 📌 Overview
This project presents the design and analysis of a planetary gear mechanism optimized for high torque output and compact motion transmission, developed using Fusion 360.

---

## Design Specifications

| Parameter | Value |
|----------|------|
| Gear Ratio | 1 : 6 |
| Module | 2 |
| Pressure Angle | 20° |
| Ring Gear Teeth (R) | 80 |
| Sun Gear Teeth (S) | 16 |
| Planet Gear Teeth (P) | 32 |
| Number of Planets | 3 |

---

## ⚙️ Gear Calculations

### Sun Gear
S = R / (Gear Ratio - 1)  
S = 80 / (6 - 1) = 16  

### Planet Gear
P = (R - S) / 2  
P = (80 - 16) / 2 = 32  

### Planet Condition
(R + S) / Np = (80 + 16) / 3 = 32 ✔ Valid  

---

## Kinematic Analysis

### Sun Gear → Planet Gear Rotation
Sun Rotation:  
360 + (360 / (80 / 16)) = 432°  

Planet Rotation:  
360°  

---

### Sun Gear → Carrier Rotation
Sun Rotation:  
360°  

Carrier Rotation:  
360 / 6 = 60°  

---

## Torque Calculation

Assumptions:
- Input Torque = 1 Nm  
- Gear Ratio = 6  
- Efficiency ≈ 90%  

T_out = T_in × Gear Ratio × Efficiency  
T_out = 1 × 6 × 0.9 = 5.4 Nm  

---

## Speed Reduction

Output Speed = Input Speed / Gear Ratio  

Example:
Input = 600 RPM  
Output = 100 RPM  

---

## Working Principle

- Ring gear is fixed  
- Sun gear acts as input  
- Planet gears distribute motion  
- Carrier provides reduced speed output  

Results:
- Increased torque  
- Reduced speed  
- Balanced load distribution  

---

## Applications

- Robotic arm joints  
- Industrial automation  
- Gear reduction systems  
- Precision actuation  

---

## Future Improvements

- Motor integration  
- Load and torque simulation  
- Material optimization  
- Bearing and shaft design  
- Real-time testing  

---

## 📷 Preview

![Planetary Gear](Images/Planetary_Gear.png)
![Top View](Images/Planetary_Gear1.png)

---

## Contact
Open for collaboration in robotics, embedded systems, and mechanical design.
