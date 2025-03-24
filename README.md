# QR Code Authentication: Detecting Original vs Counterfeit Prints

## 📌 Project Overview  
This project aims to develop a machine learning model that can distinguish between **original QR codes (first prints)** and **counterfeit copies (second prints)**. Counterfeit detection is crucial in various industries like finance, pharmaceuticals, and ticketing systems.  

We use two approaches:  
✔ **Traditional Machine Learning (SVM)** – Uses handcrafted features for classification.  
✔ **Deep Learning (CNN)** – Uses convolutional layers to automatically extract patterns.  

---

## 📂 Dataset Description  
The dataset consists of QR code images with embedded copy detection patterns:  
- **First prints** – Original QR codes with embedded security features.  
- **Second prints** – Counterfeits created by scanning and reprinting first prints.  

---

