# Smart Street Light System using IoT

A smart and energy-efficient street lighting system that automatically adjusts lighting based on environmental conditions and motion detection. This project, developed as part of my academic work, uses sensors and microcontrollers to optimize energy usage in public lighting infrastructure.

## 🌟 Features

* **Automatic Light Control:** Lights turn ON/OFF based on motion detection.
* **Ambient Light Detection:** Adjusts brightness based on surrounding light.
* **Energy Saving:** Lights remain off or dim when no motion is detected.
* **Real-World Testing:** Successfully built and tested on hardware.

## 🛠️ Tech Stack

* **Programming Language:** C++
* **Microcontroller:** ESP32 / Arduino-compatible board
* **Sensors:** LDR (Light Dependent Resistor), IR motion sensor
* **Connectivity:** Basic IoT infrastructure for remote updates and control (if extended)

## 📂 Repository Contents

```
├── main.ino   # Main Arduino logic controlling the street light behavior
├── Frontend
│   ├── js
│   └── images
├── README.md                # Project documentation
```

## ⚙️ How It Works

1. **LDR Sensor:**

   * Detects ambient light levels.
   * If it is dark, the system is activated.

2. **IR Motion Sensor:**

   * Detects movement near the streetlight.
   * If motion is detected, light turns ON.
   * If no motion is detected for a set period, light dims or turns OFF.

3. **Microcontroller:**

   * Reads sensor data and controls the light accordingly.

## 🧪 Implementation

* Code is written in **Arduino IDE**.
* Can be uploaded to any **ESP32 or Arduino Uno/Nano** board.
* Power-efficient LEDs are used for lighting.

## 🔮 Future Enhancements

* Add remote monitoring via Wi-Fi and a dashboard.
* Include solar power integration.
* Enable adaptive brightness based on traffic flow.

## 👨‍💻 Author

**Devraj Parmar**
[LinkedIn](https://linkedin.com/in/yourprofile)
