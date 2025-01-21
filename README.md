# RoadVision: Traffic Sign Recognition Using YOLOv8 🚦  

**RoadVision** is a real-time traffic sign recognition system for autonomous vehicles, utilizing the **YOLOv8 Small (YOLOv8s)** model. This project focuses on enhancing road safety and efficient navigation by enabling vehicles to detect, classify, and respond to traffic signs in real-time.  

---

## 🌟 Key Features  

- **Real-Time Detection**: Processes live video feeds with minimal latency for prompt vehicle response.  
- **High Accuracy**: Optimized for detecting various traffic signs under diverse lighting and weather conditions.  
- **Efficient Model**: Uses YOLOv8 Small, balancing speed and accuracy for deployment on edge devices.  
- **Scalable Framework**: Easily integrates with autonomous vehicle systems for seamless navigation.  

---

## 🚀 Project Objectives  

1. Develop a **real-time system** for detecting and classifying traffic signs.  
2. Optimize **YOLOv8 Small** for speed and accuracy in diverse environments.  
3. Integrate the detection system with vehicle platforms for responsive navigation.  
4. Enhance safety and efficiency in autonomous driving.  

---

## 🛠️ Implementation Details  

- **Model**: YOLOv8 Small (YOLOv8s)  
  - Input size: **640x640 pixels**   
- **Dataset**: https://universe.roboflow.com/road-safety-sexzp/road-safety-oayis.  
- **Training Environment**:  
  - Conducted on a **P100 GPU** using **Kaggle Notebooks**.  
  - Trained for **100 epochs**.  

---

## 📊 Results & Performance  

- The YOLOv8 Small model achieved **high detection accuracy** for various traffic signs, including stop signs, speed limits, and warning symbols.  
- Demonstrated **real-time processing** of video frames with minimal latency, ensuring compatibility with autonomous vehicle decision-making systems.  
- Final outputs included annotated **.avi files**, showcasing effective detection in diverse conditions.  
