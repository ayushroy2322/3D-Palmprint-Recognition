# 3D Palmprint Biometric Recognition
A deep learning-based biometric system using pseudo-3D reconstruction and attention networks, achieving near 100% accuracy.


## Overview
This project presents a hybrid biometric recognition system using pseudo-3D reconstruction and deep learning techniques. The system improves robustness against illumination and positional variations compared to traditional 2D approaches.

Developed as part of a research project at NMIT.
---

## Methodology
- Pseudo-3D reconstruction using Frankot–Chellappa algorithm  
- Feature extraction using HSANet, MobileNetV3, and PCANet  
- Supervised classification for biometric recognition  

---

## Results
The system was evaluated on the IIT Delhi palmprint dataset using multiple performance metrics.

Key performance Metrics are shown below

### 📊 Accuracy Comparison
Comparison of PCANet, HSANet, and MobileNetV3 performance.
<img width="640" height="480" alt="accuracy_no_title" src="https://github.com/user-attachments/assets/3cede4bc-f65c-4933-8e1e-cee4643a7388" />


### 📈 ROC Curve Analysis
ROC curves showing classification performance across models.
<img width="640" height="480" alt="roc_no_random" src="https://github.com/user-attachments/assets/0e3af450-21cb-464e-b97f-dfd09af632a5" />

### 📉 CMC Curve Analysis
Recognition accuracy across rank levels.
<img width="640" height="480" alt="cmc_final" src="https://github.com/user-attachments/assets/47ef35bc-3371-449f-a961-4bbaca600c04" />

---

## Performance Highlights
- Achieved near **100% accuracy** using HSANet  
- Significantly improved performance over PCANet and MobileNetV3  
- Low Equal Error Rate (EER ≈ 0.01–0.02)  
- Strong class separability using attention-based feature extraction  

---

## Deployment
- Successfully deployed on **NVIDIA Jetson Nano**  
- Demonstrated feasibility for real-time edge AI applications  
- Efficient resource utilization on embedded hardware  

---

## Dataset
- IIT Delhi Palmprint Dataset  
- ~230 subjects with 6 samples each  
- Total ~1380 grayscale images  

---

## Tech Stack
- Python  
- MATLAB  
- Deep Learning  
- Computer Vision  

---

## Files
- Research Paper (PDF)  
- Accuracy Graph  
- ROC Curve  
- CMC Curve  

---

## Conclusion
This project demonstrates that combining pseudo-3D reconstruction with attention-based deep learning significantly improves biometric recognition performance. The system is efficient, scalable, and suitable for real-world deployment on embedded devices.

---
## Reference
This work is based on a conference paper titled:
"Performance Analysis of 3D Palmprint Human Biometric Recognition System using Hierarchical Spatial Attention Network".


## Author
Ayush Anthony Roy
