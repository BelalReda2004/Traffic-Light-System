# 🚦 Arduino Traffic Light System

## 🔍 Project Overview
This project simulates a **realistic traffic light system** for two intersecting roads using an **Arduino Nano**, **LEDs**, **push buttons**, and a **7-segment display**. It responds dynamically to road congestion, with a countdown during signal transitions for better user feedback.

---

## ⚙️ How the System Works

The system uses **push buttons** to simulate road congestion. Based on the button pressed (representing traffic on that road), the system:
- Switches traffic flow by alternating the red and green lights between Road 1 and Road 2.
- Displays a countdown timer on a **7-segment display** during each transition.
- Uses **yellow LEDs** to signal upcoming changes, mimicking real traffic light behavior.

---

## 🧠 Traffic Light Logic

1. **Button Press Detection**
   - If **Road 1** is busy → Road 2 gets green, Road 1 goes red.
   - If **Road 2** is busy → Road 1 gets green, Road 2 goes red.

2. **Countdown Transition**
   - A timer is shown on the 7-segment display during each light change.

3. **Signal Flow**
   - Green → Yellow → Red → Switch roads.

---

## 🧰 Components Used

| Component             | Quantity | Purpose                                  |
|----------------------|----------|------------------------------------------|
| Arduino Nano         | 1        | Controls the logic and signal switching  |
| 7-Segment Display    | 1        | Shows countdown during transitions       |
| LEDs (Red, Yellow, Green) | 6    | Simulate traffic lights on both roads    |
| Push Buttons         | 2        | Simulate road congestion                 |
| Resistors (220Ω–330Ω)| 6+       | Current limiting for LEDs & buttons      |
| Breadboard           | 1        | Circuit assembly without soldering       |
| Jumper Wires         | —        | Connections between components           |

---

## 🔌 Circuit Design
- **LEDs** and **buttons** are connected to digital pins on the Arduino.
- **Resistors** are used in series with LEDs to prevent damage.
- The **7-segment display** is connected through digital pins with multiplexing or direct drive.

---

## 🧪 Learning Outcomes
✅ Control multiple outputs (LEDs) with Arduino  
✅ Read and debounce button inputs  
✅ Interface and drive a 7-segment display  
✅ Design logical signal transitions based on real-world traffic systems

---

## 🛠️ Tools & Software
- **Arduino IDE** – For writing and uploading the sketch  
- **Breadboard** – For prototyping and testing the circuit  
- **Proteus / Tinkercad** *(optional)* – For simulation and visualization

---

## 🚀 Getting Started

1. Assemble the components as per your schematic.
2. Upload the Arduino sketch via Arduino IDE.
3. Press a button to simulate congestion.
4. Watch the lights and 7-segment display respond!

---

## 📸 Preview  
<img width="1416" height="792" alt="Simulation" src="https://github.com/user-attachments/assets/b13fc0c6-5e42-4ec0-a9df-3d4ecb6a07c9" />


---

## 📚 Educational Value

This project is a **great introduction** to embedded systems and digital control using Arduino. It mimics real-life traffic logic and teaches core concepts like:

- Input handling  
- Output sequencing  
- Countdown timers  
- User interaction  
- Real-time logic control  
