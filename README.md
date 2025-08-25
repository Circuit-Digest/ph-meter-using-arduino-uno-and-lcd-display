# pH Meter using Arduino Uno  

[![Arduino Uno](https://img.shields.io/badge/Board-Arduino%20Uno-blue?logo=arduino)](https://store.arduino.cc/products/arduino-uno-rev3) 
[![Arduino C++](https://img.shields.io/badge/Language-Arduino%20C++-brightgreen?logo=c%2B%2B)](https://www.arduino.cc/reference/en/) 
[![CircuitDigest Project](https://img.shields.io/badge/Project-CircuitDigest-red)](https://circuitdigest.com)  

---

## 🔗 Tutorial Link  
➡️ [pH Meter using Arduino Uno](https://circuitdigest.com/microcontroller-projects/arduino-ph-meter)  

## 📂 Project Type  
➡️ [Arduino Project](https://circuitdigest.com/arduino-projects)  

---

## 🖼️ Main Project Image  
![pH Meter using Arduino Uno](https://circuitdigest.com/sites/default/files/projectimage_mic/pH-Meter-using-Arduino-UNO.jpg)  

---

## 🚀 Features  
- Measures pH value of liquid solutions in real-time.  
- Uses a **Gravity Analog pH Sensor** for accurate readings.  
- Displays measured pH value on a **16x2 LCD with I2C module**.  
- Calibration support for improved accuracy.  
- Portable and low-cost design for water quality monitoring.  

---

## 🛠️ Hardware Requirements  

| Component               | Quantity | Description |
|--------------------------|----------|-------------|
| Arduino Uno              | 1        | Main microcontroller board |
| 16x2 LCD Display         | 1        | Alphanumeric display |
| I2C Module for LCD       | 1        | Interface module to reduce wiring |
| Gravity Analog pH Sensor | 1        | pH probe with signal conditioning board |
| Breadboard & Wires       | -        | For connections |
| Power Supply (USB/5V)    | 1        | To power Arduino |

---

## ⚙️ How It Works (Step-by-Step)  
1. The **pH electrode** is dipped into a liquid sample.  
2. The probe generates a small voltage based on hydrogen ion concentration.  
3. The **pH sensor board** amplifies and conditions the signal.  
4. The analog output is fed into **Arduino Uno (A0 pin)**.  
5. Arduino processes the input, applies calibration, and calculates the **pH value**.  
6. The result is displayed on the **16x2 LCD via I2C module**.  

---

## 🔌 Circuit Connection  

### Circuit Diagram  
![Arduino pH Meter Circuit Diagram](https://circuitdigest.com/sites/default/files/circuitdiagram_mic/Arduino-pH-Meter-Circuit-Diagram.png)  

### Pin Mapping Table  

| Arduino Pin | pH Sensor Board Pin |
|-------------|----------------------|
| 5V          | V+                   |
| GND         | G                    |
| A0          | Po                   |

---

## 🧠 Troubleshooting  

| Issue                        | Possible Cause | Solution |
|-------------------------------|----------------|----------|
| LCD not displaying            | Wrong I2C address | Scan I2C address and update code |
| pH values unstable            | Probe not submerged properly / electrical noise | Use proper grounding and ensure probe is clean |
| Incorrect pH reading          | Calibration needed | Adjust calibration value in code |
| Arduino not powering          | Faulty USB cable / power supply | Replace cable or use 5V adapter |

---

## 📱 Applications  
- Water quality monitoring (aquariums, pools, tanks).  
- Agriculture (soil and nutrient solution testing).  
- Industrial process monitoring.  
- Environmental research and wastewater treatment.  

---

## 🔮 Future Enhancements  
- Add **temperature compensation** for more accurate pH readings.  
- Use **OLED/TFT display** for better UI.  
- Wireless data logging using **ESP32/Wi-Fi**.  
- Integration with IoT dashboards for remote monitoring.  

---

## 🧪 Technical Specifications  

| Parameter                  | Value |
|-----------------------------|-------|
| Supply Voltage (Sensor)     | 3.3 – 5.5V |
| Detection Range             | 0 – 14 pH |
| Accuracy                    | ±0.1 @ 25°C |
| Operating Temperature Range | 5 – 60°C |
| Probe Internal Resistance   | <250MΩ |
| Arduino Operating Voltage   | 5V |

---

## 🔗 Links  
- 📘 [pH Meter using Arduino Uno](https://circuitdigest.com/microcontroller-projects/arduino-ph-meter)  
- 📘 [Arduino Projects](https://circuitdigest.com/arduino-projects)  
- 📘 [Arduino IDE Download](https://www.arduino.cc/en/software)  
- 📘 [Arduino Uno Datasheet](https://docs.arduino.cc/resources/datasheets/A000066-datasheet.pdf)  
- 📘 [Interfacing 16x2 LCD with Arduino](https://circuitdigest.com/microcontroller-projects/interfacing-16x2-lcd-with-arduino)  
- 📘 [LiquidCrystal_I2C](https://github.com/johnrickman/LiquidCrystal_I2C)  

---

## ⭐ Support  
This project is published on **[CircuitDigest](https://circuitdigest.com)** – your hub for electronics projects, tutorials, and resources.  

---

## 🔖 Keywords  
`Arduino pH Meter` `pH Sensor with Arduino` `Water Quality Monitoring Arduino` `Gravity Analog pH Sensor` `Arduino Uno LCD Display`  
