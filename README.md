# SmartTraffic-TCMS
Smart Traffic Congestion Management System (TCMS) is an AI-powered system that dynamically adjusts traffic light timings based on real-time vehicle density using YOLOv5 and adaptive algorithms. It reduces congestion, optimizes traffic flow, and improves urban mobility.
# 🚦 Traffic Congestion Management System (TCMS)

## 📌 Overview
The **Traffic Congestion Management System (TCMS)** is an intelligent traffic light management system that dynamically adjusts signal timings based on real-time vehicle density using YOLOv5 and a signal-switching algorithm.

## 📷 Screenshots
**Vehicle Detection Output:**
![Detection Example](detection_output.png)

**Simulation GUI:**
![Simulation GUI](gui_interface.png)


## 🚀 Features
✅ **Real-time Vehicle Detection:** Uses YOLOv5 to detect and classify vehicles.  
✅ **Dynamic Traffic Signal Control:** Adjusts signal durations based on traffic density.  
✅ **Simulation & Visualization:** GUI-based simulation using Pygame.  
✅ **Efficient Traffic Flow Management:** Reduces congestion by up to 25%.  
✅ **Data Logging:** Stores detection results and signal timings for analysis.  

## 🛠 Tech Stack
- **Python**: Main programming language
- **YOLOv5**: Object detection model for vehicle recognition
- **Pygame**: GUI-based traffic simulation
- **OpenCV**: Image processing
- **NumPy, Pandas**: Data handling and analytics

## 📁 Repository Structure
```
TCMS/ 
│── output_images/           # Contains generated output images  
│── test_images/             # Contains test images for processing  
│── FINALGUI.gif             # Animated demonstration of the GUI  
│── FINAL_GUI.ipynb          # Jupyter Notebook for GUI implementation  
│── LICENSE                  # License for open-source usage  
│── README.md                # Project documentation  
│── TCMS_REPORT.pdf          # Technical report for the project  
│── detection_output.png     # Screenshot of sample output from the detection process  
│── gui_interface.png        # Screenshot of the GUI interface  
│── signal_calculation.ipynb # Jupyter Notebook for signal calculations  
```

## 🎯 Installation & Setup

## How to Run
You can run the project using **Jupyter Notebook** or directly in the **terminal/bash**.
### **1. Clone the Repository**
```sh
git clone https://github.com/vaishnavipaswan/SmartTraffic-TCMS.git
cd SmartTraffic-TCMS
```
### **2. Install Jupyter (if not installed)**
Make sure you have Jupyter installed. If not, install it using:
```
pip install notebook
```
### **3. Run Jupyter Notebook**
Start Jupyter Notebook with:
```
jupyter notebook
```
Then, open FINAL_GUI.ipynb or signal_calculation.ipynb and execute the cells step by step.
### **4. View Output**
- Processed images are saved in output_images/
- Test images are located in test_images/
- The GUI interface preview is available in FINALGUI.gif or gui_interface.png

## 📊 Results & Analysis
- **Wait Time Reduction:** Up to **25% improvement** in high-density conditions.
- **Throughput Increase:** **20% more vehicles** processed compared to traditional systems.
- **Optimized Signal Timing:** Adjusts green light durations dynamically for efficient traffic management.

---

## 📌 Future Enhancements  
🔹 **Multi-intersection Coordination** – Expanding the system to manage multiple intersections.  
🔹 **Integration with IoT Sensors** – Incorporating real-time traffic data from IoT devices.  
🔹 **Real-time Cloud Deployment** – Enabling cloud-based traffic control for scalability.  
🔹 **Emergency Vehicle Prioritization** – Adjusting signals dynamically to prioritize emergency vehicles.  

---

## 📜 License  
This project is licensed under the **MIT License**.  

---

## 👥 Authors  
- **Vaishnavi Paswan**  
- **Vedika Agrawal**  
- **Pushkar Dubey**  
- **Mustakeem Shaikh**  

---

## ⭐ Contributing  
Feel free to **fork** this repository, create a branch, and submit **pull requests**!  
For major changes, please open an **issue** first to discuss your proposal.  

---
