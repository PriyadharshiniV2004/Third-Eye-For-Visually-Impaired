# Third Eye for Visually Impaired 👓🔊

An assistive technology project designed to help visually impaired individuals navigate safely by detecting obstacles using ultrasonic sensing and providing audible alerts through a buzzer.

This system reduces dependency on walking sticks and enhances independent mobility by alerting users about nearby obstacles in real time.

---

## 📖 Project Overview

Visually impaired individuals often face challenges in detecting obstacles in their surroundings, which can lead to accidents and restricted mobility. Traditional aids such as walking sticks provide limited spatial awareness.

The **Third Eye for Visually Impaired** project proposes a wearable obstacle detection system integrated into a pair of glasses. The system continuously detects obstacles in front of the user and provides audio feedback using a buzzer to indicate proximity.

The device is designed to be:
- Portable
- Lightweight
- User-friendly
- Cost-effective

---

## 🎯 Objectives

- To assist visually impaired individuals in obstacle detection  
- To reduce accidents caused by unseen obstacles  
- To improve independent mobility  
- To design a simple and affordable assistive device  

---

## ⚙️ Principle of Operation

The system operates using **ultrasonic sensing technology**:

1. The ultrasonic sensor emits high-frequency sound waves.
2. These waves reflect back when they hit an obstacle.
3. The time delay between transmission and reception is measured.
4. The distance to the obstacle is calculated.
5. A buzzer produces an audible alert based on obstacle proximity.

The timing and sensitivity of the system are controlled using a **NE555 timer IC** along with resistors, capacitors, and a preset.

---

## 🧩 System Components

### Main Components
- Ultrasonic Sensor
- NE555 Timer IC
- Preset (10 kΩ)
- Resistors (1 kΩ)
- Capacitors (10 µF, 100 µF)
- Buzzer
- Power Supply (3.7V – 5V battery)
- Goggles (wearable frame)

---

## 🏗️ System Architecture

- **Input Unit:** Ultrasonic Sensor  
- **Processing Unit:** NE555 Timer IC with RC timing circuit  
- **Output Unit:** Buzzer (audio feedback)  
- **Power Unit:** Battery-based portable supply  

The system is mounted on a wearable frame (glasses) for hands-free operation.

---

## 🔌 Hardware Connections (Summary)

- Ultrasonic sensor trigger, VCC, and GND connected to NE555 IC  
- Echo pin connected to buzzer circuit  
- Preset used to adjust sensitivity  
- Capacitors and resistors define timing characteristics  

Detailed connections are provided in the `hardware/` folder.

---

## 🧪 Working Methodology

- Continuous ultrasonic pulse emission
- Echo detection from obstacles
- Distance-dependent timing signal generation
- Buzzer activation based on proximity
- Adjustable sensitivity using preset resistor

---

## 📊 Results and Observations

- The system successfully detects obstacles within a practical range.
- Audible alerts help users identify obstacle proximity.
- Sensitivity can be adjusted based on environment and user preference.
- The device is lightweight and easy to use.

---

## ⚠️ Limitations

- Cannot detect objects that do not reflect ultrasonic waves effectively (e.g., human body).
- Performance depends on component values and calibration.
- Limited directional awareness.

---

## 🔮 Future Enhancements

- Integration of PIR sensors for human detection  
- Directional audio alerts  
- Battery level indication  
- GPS-based navigation support  
- Mobile application integration  
- Lightweight and ergonomic redesign  

---

---

## 🧑‍💻 Contributors

- Nandhini S  
- **Priyadharshini V**  
- Vasunthira S  
- Vedha Varshini M  
- Sohini Mandal  

---

## 📜 License

This project is released under the MIT License and is free to use for academic and research purposes with proper attribution.
