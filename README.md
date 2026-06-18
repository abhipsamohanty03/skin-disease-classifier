# 🔬 Skin Disease Classifier
A deep learning web app that classifies skin lesions into 7 categories
Using MobileNetV2 transfer learning trained on the HAM10000 dataset.

## Features
- 7-class skin lesion classification
- Transfer learning with MobileNetV2
- Grad-CAM heatmap visualisation
- Streamlit web interface with risk level indicators

## Tech Stack
Python · TensorFlow · Keras · Streamlit · OpenCV · scikit-learn

## Dataset
HAM10000 — 10,015 dermoscopy images across 7 disease classes
(Download from Kaggle separately — not included due to size)

## How to Run
pip install -r requirements.txt
streamlit run app.py

## Results
Test Accuracy: 92.4% | Macro F1 Score: 0.87
