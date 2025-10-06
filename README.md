# 🚦 Intelligent Traffic Violation Detection System

## 📜 Project Overview
The **Intelligent Traffic Violation Detection System** is an AI-powered solution designed to enhance road safety by automatically identifying and reporting traffic violations.  
By leveraging **computer vision** and **deep learning techniques**, this system detects violations such as red-light jumping, helmet non-usage, and lane violations, along with recognizing license plates for offender identification.

This system supports large-scale datasets and is designed for real-time scalability, enabling integration with smart city traffic monitoring.

---

## ✨ Features

- **Violation Detection**  
  Detects traffic violations including:  
  - Red-light jumping  
  - Helmet violations  
  - Lane violations
 
 

- **Object Detection**  
  Utilizes **YOLOv5/YOLOv8** for accurate detection of vehicles, helmets, and lane markings.

- **License Plate Recognition (OCR)**  
  Extracts and recognizes vehicle number plates using OCR.

- **Dataset Handling**  
  Supports large datasets for improved robustness and real-world applicability.

- **Evaluation Metrics**  
  - **YOLO Object Detection:** Precision, Recall, F1-Score, mAP  
  - **OCR:** Character Error Rate (CER), Word Accuracy  
  - **Overall System:** Accuracy, False Positive Rate, False Negative Rate  

---

## 📊 Datasets Used

1. **BDD100K (Berkeley DeepDrive)**  
   Traffic images with bounding box annotations.  
   [Dataset Link](https://bdd-data.berkeley.edu/)

2. **Traffic4Cast**  
   Urban traffic forecasting dataset.  
   [Dataset Link](https://www.iarai.ac.at/traffic4cast/)

3. **Kaggle Traffic Violation Datasets**  
   - Helmet detection  
   - Lane detection  
   - License plate recognition  
   [Dataset Link](https://www.kaggle.com/)

---

## 🛠️ Libraries & Tools

- **Deep Learning Frameworks:**  
  - PyTorch  
  - TensorFlow  
  - YOLOv5 / YOLOv8  

- **Data Handling:**  
  - FiftyOne  
  - OpenCV  
  - Pandas, NumPy  

- **OCR:**  
  - Tesseract OCR  
  - EasyOCR  

- **Visualization:**  
  - Matplotlib  
  - Seaborn  

- **Deployment:**  
  - GitHub (code repository)  
  - Netlify (front-end deployment, if applicable)  

---

## 🚀 Future Scope

- **Real-Time CCTV Integration** — Directly monitor live traffic feeds.  
- **Edge AI Deployment** — Low-latency detection on edge devices.  
- **Expanded Violation Detection** — Detect overspeeding, mobile phone usage while driving, seat belt violations, etc.  
- **Cloud-Based Violation Reports** — Generate and store reports accessible to authorities.  
- **Traffic Control Integration** — Automated traffic management based on detected violations and congestion.

---

## 📖 References

- [BDD100K Dataset](https://bdd-data.berkeley.edu/)  
- [Traffic4Cast Dataset](https://www.iarai.ac.at/traffic4cast/)  
- [Kaggle](https://www.kaggle.com/)  
- [YOLOv5 Documentation](https://docs.ultralytics.com/)  
- [Tesseract OCR](https://github.com/tesseract-ocr)

---

✅ **Conclusion**  
This project demonstrates how **AI and computer vision** can improve traffic management and road safety. By automating violation detection and offender identification, the system can reduce traffic law violations, improve enforcement efficiency, and save lives.

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0** (GPL-3.0).  


