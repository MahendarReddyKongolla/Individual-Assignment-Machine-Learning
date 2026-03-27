# Individual-Assignment-Machine-Learning
Vehicle Image Classification: Baseline CNN, MobileNetV2 and Fine-tuning

#  Vehicle Image Classification using CNN and Transfer Learning (MobileNetV2)

##  Overview
This project presents an end-to-end image classification pipeline for vehicle recognition using deep learning. It compares a baseline Convolutional Neural Network (CNN) with a transfer learning approach using MobileNetV2, including fine-tuning.

The objective is to demonstrate how transfer learning improves accuracy, generalisation, and efficiency compared to models trained from scratch.

---

##  Features
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Baseline CNN model  
- Transfer Learning using MobileNetV2  
- Fine-tuning for performance improvement  
- Model evaluation (Accuracy, Precision, Recall, F1-score)  
- Confusion matrix and prediction visualisation  

---

##  Dataset
Vehicle Classification Dataset (Kaggle):  
https://www.kaggle.com/datasets/mohamedmaher5/vehicle-classification  

Classes included:
- Auto Rickshaws  
- Bikes  
- Cars  
- Motorcycles  
- Planes  
- Ships  
- Trains  

The dataset is balanced with approximately 800 images per class.

---

##  Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

##  Models Implemented

### 1. Baseline CNN
- 3 Convolutional layers (32, 64, 128 filters)  
- MaxPooling + Dense + Dropout  
- Accuracy: **83.2%**

---

### 2. MobileNetV2 (Frozen)
- Pre-trained on ImageNet  
- Base layers frozen  
- Custom classification head  
- Accuracy: **99.3%**

---

### 3. Fine-Tuned MobileNetV2
- Top layers unfrozen  
- Low learning rate (1e-5)  
- Accuracy: **99.4%**

---

##  Model Performance

| Model                    | Accuracy |
|--------------------------|----------|
| Baseline CNN             | 83.2%    |
| MobileNetV2 (Frozen)     | 99.3%    |
| Fine-Tuned MobileNetV2   | 99.4%    |

---

##  Key Insights
- Transfer learning provides a significant performance boost  
- Fine-tuning improves feature adaptation and accuracy  
- Pre-trained models outperform CNNs trained from scratch  
- Feature quality is more important than model complexity  

---

##  Results
The project includes:
- Accuracy and loss curves  
- Confusion matrices  
- Prediction visualisations comparing models  

---

##  How to Run

1. Clone the repository from GitHub to your local machine.

2. Navigate to the project folder using terminal or command prompt.

3. Install all required libraries using the requirements.txt file.

4. Open the Jupyter Notebook included in the repository.

5. Run all cells step-by-step to reproduce results, including training, evaluation, and visualisations.

---
