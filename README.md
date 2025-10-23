My project for the Deep Learning and Computer Vision project. RSNA Classification to identify fractured and non fractured bones.

# Cervical Spine Fracture Detection

This project focuses on detecting cervical spine fractures from medical DICOM images using deep learning techniques. Two models were implemented and compared: a **custom-built CNN** and a **ResNet18** transfer learning model.

## 🧠 Overview
- Preprocessed DICOM files into normalized PNG images. (branch: dataset-subsetting)
- Used a balanced dataset by computing **class weights** to handle data imbalance.
- Trained and validated both models using PyTorch.
- Evaluated using metrics: Accuracy, Precision, Recall, F1-score, and AUC.
- Visualized **confusion matrices** and **ROC curves** for model comparison.

## 🧩 Models
- **Custom CNN** — a simple convolutional neural network designed for baseline performance.
- **ResNet18** — a pretrained model fine-tuned for medical image classification.

## ⚙️ Tools & Libraries
- PyTorch  
- OpenCV  
- pydicom
- Pillow (PIL)
- NumPy
- Pandas
- Matplotlib
- sklearn  

## 📊 Results
ResNet18 outperformed the custom CNN in overall accuracy and AUC, demonstrating the advantage of transfer learning for medical imaging tasks.

## ⚖️ Ethics
All experiments followed medical data ethics standards, ensuring patient privacy and responsible use of medical imagery.
