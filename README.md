Arduino NTC Temperature Monitor 
 
A Wokwi-simulated Arduino project that monitors ambient temperature using an NTC Thermistor and provides visual feedback via a 3-LED indicator system (Green, Yellow, Red).
 
eatures
- Accurate temperature sensing using the **Steinhart-Hart equation**.
- Real-time Serial Monitor output.
- **Visual Alerts:**
  - 🔵 Below 20°C: All LEDs OFF (Cold)
  - 🟢 20°C - 30°C:Green LED ON (Normal)
  - 🟡 30°C - 40°C:Yellow LED ON (Warning)
  - 🔴 Above 40°C:Red LED ON (Danger/Hot)
 
Components (Simulated)
1. Arduino Uno
2. NTC Temperature Sensor (Analog)
3. LEDs:1x Red, 1x Yellow, 1x Green
4. Resistors: 3x 220Ω (for LEDs)
 
Wiring Diagram
1. NTC Sensor (Signal):  A0
2.  Green LED: Pin 11
3.  Yellow LED: Pin 12
4.  Red LED: Pin 13
5.  All Grounds: GND
 
Code Logic
The project uses a non-linear conversion formula to translate analog resistance into Celsius.
