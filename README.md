# 🌱 Smart Targeted Spray Assistance System  

![IoT](https://img.shields.io/badge/Domain-IoT-green)
![ESP32](https://img.shields.io/badge/Microcontroller-ESP32-blue)
![ML](https://img.shields.io/badge/Technology-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Project-Prototype-yellow)

**An IoT + Machine Learning based smart spraying system that detects plant diseases and demonstrates automated pesticide spraying.**

---

## 📌 Project Overview

This project presents a **smart spraying assistance system** designed to improve efficiency in agricultural pesticide usage.

The system uses a **camera and a trained Machine Learning model** to analyze plant leaf conditions. Based on detection, it enables **automatic pump activation**, along with a **manual control mode** for demonstration.

The prototype showcases the transition from **traditional spraying methods to intelligent, data-driven agriculture**, with a vision toward precise targeted spraying.

---

## 🏗 System Architecture
Camera Input (Leaf Images)
│
▼
Machine Learning Model (Disease Detection)
│
▼
ESP32 Controller
│
├── Manual Mode (User Control)
│
└── Automatic Mode (Detection Trigger)
│
▼
Relay Module
│
▼
Water Pump
│
▼
Spray Output

---

## ⚙️ Hardware Components

* ESP32 Microcontroller  
* Relay Module  
* Water Pump  
* Servo Motors (for future targeting)  
* Camera (ESP32-CAM / Laptop Camera)  
* Power Supply  

---

## 🧠 Machine Learning Approach

The system uses a **supervised learning model** trained on labeled images of plant leaves.

### Workflow:
- Image collection (healthy & diseased leaves)  
- Preprocessing using OpenCV:
  - Resize to 64×64  
  - Convert to numerical pixel values  
- Flattening into feature vectors  
- Training using Scikit-learn classifier  

The model identifies:
- Color variations  
- Spots  
- Texture differences  

---

## 📡 System Functionality

### Manual Mode  
Allows direct control of the pump for spraying.

### Automatic Mode  
Pump is triggered automatically when:
- A condition is met  
- Or a diseased pattern is detected  

---

## 🚀 Features

* Smart disease detection using ML  
* Manual + automatic spraying system  
* Real-time actuation using ESP32  
* Low-cost and scalable prototype  
* Foundation for precision agriculture  

---

## 📂 Repository Structure
smart-targeted-spray-system
│
├── esp32-code
│ └── pump_control.ino
│
├── ml-model
│ └── train_model.py
│
├── images
│ └── prototype.jpg
│
├── diagrams
│ └── system_architecture.png
│
└── README.md


---

## 🔮 Future Improvements

* Servo-based automatic nozzle targeting  
* Image-to-coordinate mapping for precise spraying  
* Fully automated disease detection and action  
* IoT dashboard for remote monitoring  
* Improved ML model with larger datasets  

---

## 🎯 Applications

* Precision agriculture  
* Smart farming systems  
* Sustainable pesticide management  
* Crop health monitoring  

---

## ✨ Conclusion

This project demonstrates a step toward **intelligent agricultural systems**, reducing unnecessary chemical usage and improving farming efficiency.

> “Don’t spray everywhere. Spray where it matters.”
