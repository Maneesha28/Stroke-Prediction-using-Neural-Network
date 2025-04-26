# 🧠 Stroke Prediction Using Neural Networks

This project predicts the likelihood of stroke using a neural network trained on health metrics including demographics, medical history, and lifestyle factors.

## 🚀 Features
- Preprocessing: Encoding, binning, SMOTE for class balancing
- Model: Feedforward neural network with dropout & L2 regularization
- Evaluation: Accuracy, precision, recall, F1, ROC-AUC, confusion matrix

## 🧾 Model Summary
- **Input:** 20 features  
- **Layers:** Dense (512 → 256 → 128) + Dropout  
- **Output:** Sigmoid  
- **Loss:** Binary crossentropy  
- **Optimizer:** SGD with learning rate decay  
- **Epochs:** 50, Batch size: 32

## 📊 Metrics

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | 74.11%    |
| Precision (1)  | 5.27%     |
| Recall (1)     | 76.40%    |
| F1 Score (1)   | 9.87%     |
| ROC AUC        | 0.81      |
