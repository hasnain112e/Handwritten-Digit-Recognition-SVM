# Handwritten-Digit-Recognition-SVM
# 🖊️ Handwritten Digit Recognition - SVM Classifier

## 📌 Project Overview
This project implements a handwritten digit recognition system using the **Support Vector Machine (SVM)** algorithm.  
The model is trained on the **scikit-learn digits dataset** (8x8 pixel grayscale images of digits 0-9) and predicts the digit shown in an image.

## 📊 Dataset
- **Source:** `load_digits()` from scikit-learn
- **Images:** 8x8 pixels, grayscale
- **Classes:** Digits 0–9
- **Total Samples:** 1797

## 🚀 Steps Performed
1. Loaded the digits dataset from sklearn.datasets
2. Visualized sample digit images
3. Flattened images into 64-length feature vectors
4. Split dataset into training (80%) and testing (20%) sets
5. Trained an **SVM classifier** with:
   - kernel='rbf'
   - gamma=0.001
   - C=10
6. Evaluated the model:
   - Accuracy score
   - Classification report
   - Confusion matrix heatmap
7. Visualized model predictions on random test images

## 🛠 Technologies Used
- Python
- scikit-learn
- Matplotlib
- Seaborn

## 📈 Output
- **Accuracy:** ~XX% (replace with your score)
- Confusion matrix showing classification results
- Sample predictions on unseen test images

## 🔧 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/Handwritten-Digit-Recognition-SVM.git
cd Handwritten-Digit-Recognition-SVM

# Install dependencies
pip install scikit-learn matplotlib seaborn

# Run Jupyter Notebook
jupyter notebook handwritten_digit_svm.ipynb
