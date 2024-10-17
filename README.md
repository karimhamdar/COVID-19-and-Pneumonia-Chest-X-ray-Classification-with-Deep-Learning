# Project Title: Classification of Chest X-Rays Using Deep Learning

## Problem Definition
This project aims to diagnose respiratory conditions using chest X-ray images, categorizing them into three classes: **COVID-19**, **non-COVID pneumonia**, and **normal conditions**.

## Objectives
- **Model Comparison:** Evaluate and compare the performance of different deep learning models.
- **Preprocessing Analysis:** Investigate the effects of preprocessing techniques on model accuracy.
- **Effects of Data Augmentation:** Assess how data augmentation influences model performance.

## Models Used
- **ResNet**
- **DenseNet**
- **Custom CNN**

## Preprocessing Techniques
1. **Resizing:** Utilized `cv2.INTER_NEAREST` to resize images to **224x224**.
2. **Padding:** Applied padding to maintain image dimensions.
3. **Grayscale Conversion:** All images were converted to grayscale.
4. **Data Augmentation:** Employed on both resized and padded datasets.

## Authors
- Davide Christian Mancosu Bustos
- Karim Eugenio Hamdar

## Supervisor
- Prof. Giovanni Da San Martino

## Contact
- Email: [karimhamdar09@gmail.com](mailto:karimhamdar09@gmail.com)
- LinkedIn: [linkedin.com/in/karim-hamdar-326046327](https://www.linkedin.com/in/karim-hamdar-326046327)
