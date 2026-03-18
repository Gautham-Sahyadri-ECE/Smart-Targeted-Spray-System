# Smart-Targeted-Spray-System
# 🌱 Smart Targeted Spray Assistance System  

<p align="center">
  <img src="https://img.shields.io/badge/IoT-Enabled-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Integrated-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Prototype-orange?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" width="400"/>
</p>

---

## 💡 Problem Statement  

Modern agriculture still relies on **uniform pesticide spraying**, which leads to:  
- 🌍 Environmental pollution  
- 💸 Increased operational cost  
- 🌱 Damage to healthy crops  

Manual identification of diseased plants is inefficient and lacks precision.

---

## 🚀 Solution Overview  

The **Smart Targeted Spray Assistance System** integrates **Machine Learning with IoT hardware** to create a semi-automated spraying solution.

✔ Detect plant diseases using image processing  
✔ Enable manual + automatic spray control  
✔ Reduce unnecessary pesticide usage  
✔ Provide a base for precision agriculture systems  

---

## ⚙️ System Workflow  

<p align="center">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="400"/>
</p>

### 📷 Image Processing  
- Capture leaf images via camera  
- Preprocess using OpenCV (resize to 64×64)  
- Convert into feature vectors  
- Classify using supervised ML model  

---

### 🎯 Spray Mechanism  
- **Manual Mode** → Direct pump control  
- **Automatic Mode** → Triggered by detection/conditions  
- Controlled using ESP32 + Relay  

---

## 🧠 Machine Learning Pipeline  

- Detects patterns like:
  - Color variation  
  - Leaf spots  
  - Texture differences  

---

## 🔮 Future Enhancements  

🚀 Servo-based automatic targeting  
🎯 Precision spraying on infected regions  
☁️ Cloud dashboard for monitoring  
📊 Improved ML model accuracy  
🌿 Fully autonomous farming system  

---

## 🧰 Tech Stack  

| Category        | Tools Used |
|----------------|----------|
| Hardware       | ESP32, Relay, Water Pump, Servo Motors |
| Software       | OpenCV, Scikit-learn, Arduino IDE |
| Concepts       | IoT, Embedded Systems, Machine Learning |

---

## 🔌 Components  

- ESP32  
- Relay Module  
- Water Pump  
- Servo Motors (future scope)  
- Camera  

---

## 📂 Project Structure  
/code
├── esp32_code/
├── pump_control/
├── ml_model/
└── servo_control/ (future)

---

## 🎥 Demo  

<p align="center">
  <img src="https://media.giphy.com/media/26ufdipQqU2lhNA4g/giphy.gif" width="400"/>
</p>

👉 Add your demo video link here  

---

## 📸 Prototype Images  

👉 Add your real project images here  

---

## ✨ Key Highlights  

✔ Combines ML + Embedded Systems  
✔ Demonstrates real-time actuation  
✔ Scalable for smart farming  
✔ Sustainable and efficient approach  

---

## 📌 Conclusion  

This project demonstrates a shift from **traditional spraying methods** to **intelligent, controlled agricultural systems**, paving the way for future precision farming solutions.

<p align="center">
  <b>“Don’t spray everywhere. Spray where it matters.”</b>
</p>
