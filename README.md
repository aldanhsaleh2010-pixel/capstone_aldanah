# 🩸 Hemoglobin Disorder Classification Using Machine Learning and Neural Networks

---

# 📌 1. Introduction

In this project, different Machine Learning and Neural Network models were used to classify hemoglobin disorders based on medical and laboratory data.

I selected this dataset because blood disorders are an important healthcare topic, and I wanted to explore how AI models can help classify medical conditions using patient test results.

---

# 📊 2. Dataset Description

The dataset contains **3000 rows** and **34 columns**.  
The target variable is `variant_type`, which represents different types of hemoglobin disorders.

The dataset includes:
- Blood test measurements
- Clinical indicators
- Hemoglobin-related features
- Binary medical conditions

No missing values were found in the dataset.  
However, the classes were imbalanced because one class had significantly more samples than the others.

---

# 🤖 3. Models Used

Three Machine Learning models were trained and evaluated:

- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

Among these models, **Random Forest** achieved the best overall performance.

---

# 🧠 4. Neural Network

A Neural Network model was built using Keras Dense layers with ReLU and Softmax activation functions.

Dropout layers were added to reduce overfitting and improve generalization.  
The model was trained for 15 epochs using training and validation data.

Training and validation accuracy/loss curves were plotted to monitor the model’s learning process.

---

# 📈 5. Results & Comparison

The Neural Network achieved strong results on the dataset.  
However, Random Forest slightly outperformed the Neural Network in terms of Accuracy and F1-score.

The comparison showed that Random Forest was the most suitable model for this dataset, especially with the class imbalance problem.

---

# 🎯 6. What I Learned

Through this project, I learned how to:
- Prepare and preprocess datasets
- Train and compare different Machine Learning models
- Build a Neural Network using TensorFlow and Keras
- Evaluate classification models using multiple metrics

I also learned that more complex models are not always better, since Random Forest achieved better results than the Neural Network in this project.
