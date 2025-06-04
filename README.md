
# 👁️‍🗨️ Face Detection & Gender Classification

This project demonstrates face detection using the MTCNN library and gender classification using a pre-trained Xception model. It can detect multiple faces in an image or from a webcam, draw bounding boxes, and classify the gender of each detected face.

---

## 🎯 Project Objectives

- Detect faces in real-time or from uploaded images.
- Classify detected faces as **male** or **female** using a trained deep learning model.
- Visually mark detected faces with bounding boxes (blue for male, red for female).
- Count and display the number of males and females in the input image.
- Deploy the app for public use using **Streamlit Cloud**.

---

## 📦 Libraries Used / Tech Stack

- **Python** (Core language)
- **TensorFlow / Keras** (Model training and inference)
- **Xception Model** (Transfer learning for gender classification)
- **MTCNN** (Multi-task Cascaded Convolutional Networks for face detection)
- **Matplotlib** (For image plotting and drawing rectangles)
- **Streamlit** (Web deployment and interaction)
- **NumPy** (Numerical operations)
- **Pandas** (Optional for dataset analysis)
- **OpenCV** (Optional for camera interfacing)
- **Kaggle Datasets** (Used for model training)

---

## 📁 Dataset Sources

The model is trained on two datasets:

1. [Gender Classification Dataset (47K+ cropped face images)](https://www.kaggle.com/cashutosh/gender-classification-dataset)  
   ![Example 1](https://github.com/AbdassalamAhmad/Gender-Classification/blob/main/Dataset_examples/1st.jpg)

2. [Gender Recognition with 200K+ images (less cropped)](https://www.kaggle.com/as)
