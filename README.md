# AI-Powered Traffic Control System 🚦

A smart system that intelligently manages traffic lights by adjusting their durations in real time, using computer vision (OpenCV) and neural networks to respond to actual road conditions.

---

## 📜 Overview of the Project

Urban traffic congestion is a growing concern, contributing to lost time, commuter frustration, and increased pollution. Traditional traffic lights operate on fixed timers, lacking responsiveness to changing traffic conditions.

This project introduces a **real-time adaptive traffic control system** that employs **AI and computer vision** to analyze traffic flow and intelligently adjust signal timings, reducing bottlenecks and enhancing traffic efficiency.

---

## 🎯 Project Theme: AI-Based Traffic Control

**Challenge:**  
Build an intelligent system that uses lane-specific traffic data to dynamically determine signal durations, leveraging tools like OpenCV and neural networks.

---

## ✨ Key Features

- **Live Traffic Monitoring:**  
  Uses OpenCV to capture and evaluate vehicle density from live video streams for each lane.

- **Intelligent Signal Timing:**  
  Neural networks predict the most efficient green light duration for each direction to ease traffic flow.

- **Self-Learning Capabilities:**  
  Improves accuracy over time by learning from previously recorded traffic patterns.

- **Expandable Design:**  
  Easily adaptable to multiple junctions and different traffic environments.

- **Eco-Conscious Functionality:**  
  Lower vehicle idle time leads to reduced fuel consumption and greenhouse gas emissions.

---

## 💻 Tech Stack

- **Vision Processing:** OpenCV  
- **AI & Prediction Models:** TensorFlow (Custom-built Neural Networks)  
- **Server-Side:** Python Flask  
- **User Interface:** React.js for visualizing traffic conditions in real time  

---

## ⚙️ Installation & Setup  

Follow these steps to set up the project on your local machine:  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/microstarinc/AI-traffic-management-system.git  
 
2. **Install Dependencies**  
   ```sh
   pip install -r requirements.txt
3. **Run the Application**  
   ```sh
   bash run.sh
 4. **Access the Frontend Dashboard**  
  
   Open your browser and navigate to  ``` http://localhost:3000``` to view real-time traffic data.


---

### 🚀 Future Enhancements  

1. **Smart City Integration:**  
  Collaborate with municipalities to integrate this system into existing smart city infrastructure.  

2. **Traffic Pattern Prediction:**  
  Predict future traffic patterns using historical data for proactive congestion management.  

3. **Emergency Vehicle Priority:**  
  Detect emergency vehicles and modify traffic light timings to clear their path.
