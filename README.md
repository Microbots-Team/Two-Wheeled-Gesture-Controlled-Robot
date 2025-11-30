# 🐢 Turtulisim Robot

A two-wheeled robot system 🤖 designed to be controlled in **two synchronized modes**:

 1️⃣ **Physical Robot Control** – commands sent to the real robot hardware  
 2️⃣ **TurtleSim Control** – the same commands mirrored inside the ROS TurtleSim environment  

Users can control both robots using:
- ⌨️ **Keyboard commands**, or  
- ✋ **Hand gestures** detected using computer vision  

This setup ensures that both the **real robot** and the **TurtleSim robot** move together in real time .

The system is built within the **ROS environment** for integrated control and processing.  


---

## 💡 Project Overview
The main goal of this project is to combine **ROS (Robot Operating System)**, **gesture recognition**, and **robot simulation** into one integrated control system.

A camera captures hand gestures, which are processed using **MediaPipe**, converted into ROS movement commands, and broadcast simultaneously to:
- 🚗 The physical two-wheeled robot  
- 🐢 The TurtleSim simulation  

This creates a synchronized, intuitive, and contact-free way to control both robots at the same time.

---

## ⚙️ Components and Parts Used
- 🧠 **ESP32** – serves as the main control and communication unit  
- ⚙️ **DC Motors** – provide motion for the two-wheel base  
- 🔌 **Motor Driver Circuit** – controls motor direction and speed  
- 🎥 **Camera** – captures the user’s hand gestures for processing

---

## 💻 Software and Tools Used
- 🦾 **ROS (Robot Operating System)** – for system integration, control, and simulation
- 🐢 **TurtleSim** – ROS simulation environment for testing robot motion  
- ✋ **Mediapipe** – for real-time hand gesture detection via computer vision  
- 🔧 **Arduino IDE** – for programming and controlling the ESP32 module

---

## 👨‍💻 Contributors:
Special thanks to :  
- **Ahmad Sheikh Daher** [LinkedIn](https://www.linkedin.com/in/ahmad-sheikh-daher/)  
- **May Homsi** [LinkedIn](https://www.linkedin.com/in/may-homsi-04764335b/)  
- **Izzat Kawadri** [LinkedIn](https://www.linkedin.com/in/izzat-kawadri/)

---

## 🚀 Future Improvements
- Integrate autonomous navigation alongside manual controls  
- Add obstacle detection using sensors (Ultrasonic / LiDAR)  
- Expand gesture vocabulary for more advanced robot behaviors  
- Visualize gesture tracking and robot paths in RViz  

---

## 📸 Demo
**Coming soon!**

---

**Made with ❤️ using ROS, TurtleSim, Mediapipe, and ESP32.**

