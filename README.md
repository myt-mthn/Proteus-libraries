# Proteus Libraries

A curated collection of **custom Proteus (ISIS) simulation libraries** for commonly used sensors and electronic modules that are **not available by default** in Proteus.

This repository is intended for **students, educators, and embedded systems developers** who want to quickly simulate sensor-based projects in Proteus without creating library components from scratch.

---

## 📦 Included Libraries

The repository currently contains Proteus libraries for the following sensors:

* Flame Sensor
* Heart Rate Sensor
* Infrared (IR) Sensor
* Rain Sensor
* Touch Sensor
* Ultrasonic Sensor

Each sensor folder includes the required Proteus library files:

* `.LIB` – Component library file
* `.IDX` – Library index file

---

## 🛠 Requirements

* **Proteus Design Suite** (ISIS) – Version 8 or later recommended
* Basic knowledge of Proteus schematic simulation

---

## 🚀 Installation Steps

1. Download or clone this repository:

   ```bash
   git clone https://github.com/myt-mthn/Proteus-Libraries.git
   ```

2. Navigate to your Proteus installation directory. Typical path:

   ```
   C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\LIBRARY
   ```

3. Copy the required `.LIB` and `.IDX` files from this repository into the Proteus `LIBRARY` folder.

4. Restart Proteus (if already open).

5. In ISIS, click **P (Pick Devices)** and search for the sensor name to use it in your schematic.

---

## 🧪 Usage

* Place the sensor component into your Proteus schematic.
* Connect it to microcontrollers such as **Arduino, AVR, PIC, STM32, or ESP32** (depending on simulation requirements).
* Use appropriate test signals or virtual instruments to emulate sensor behavior.

> Note: These libraries are primarily for **functional and educational simulation**, not for precise analog modeling.

---

## 🎯 Applications

* Embedded systems learning
* Arduino and microcontroller tutorials
* Academic lab experiments
* Rapid prototyping of sensor-based projects
* Training demonstrations and simulations

---

## 📁 Repository Structure

```
Proteus-Libraries/
│
├── Flame Sensor/
├── Heart Rate Sensor/
├── IR Sensor/
├── Rain Sensor/
├── Touch Sensor/
└── Ultrasonic Sensor/
```

Each folder contains the corresponding `.LIB` and `.IDX` files.

---

## 🤝 Contributing

Contributions are welcome.

You may contribute by:

* Adding new Proteus libraries
* Improving existing components
* Providing documentation or examples

Please fork the repository and submit a pull request.

---

## ⚠ Disclaimer

These libraries are provided **for educational and simulation purposes only**. Behavior may differ from real-world hardware.

---

## 👤 Author

**Mathan MG**
Embedded Systems & Robotics Engineer
GitHub: [https://github.com/myt-mthn](https://github.com/myt-mthn)

---

## ⭐ Support

If you find this repository useful, consider giving it a ⭐ on GitHub to support the project.
