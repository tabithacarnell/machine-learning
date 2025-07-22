# Mini Project - Deceptive Story Classification

A mini project using machine learning through python to classify short narrative audio clips as either truthful or deceptive using the **MLEnd Deception** dataset.

---
## File Included

- *Notebook:* `miniproject.ipynb`

---

## Tools & Techniques  
- `librosa` for audio feature extraction (MFCC, ZCR, tempo, pitch, etc.)
- `matplotlib` and `seaborn` for visualisations 
- `scikit-learn` for model training (SVM, Logistic Regression, Decision Tree)  
- `StandardScaler` for Feature scaling 
- Train/test splits and validation  
- Classification metrics: Accuracy, F1-score, Confusion Matrix

---

## Insights  

- Audio clips were preprocessed and trimmed to 30 seconds.
- Two sets of features were extracted focusing on spectral and temporal properties.
- Models were trained on both datasets to classify stories as true or deceptive.
- SVM performed best overall, with ~73% accuracy on the combined training set and balanced F1-scores across classes.

---

## Data Source

- MLEnd Deception Dataset

---

> Developed as part of an academic project in 2024, with students across BUPT Beijing, BUPT Hainan, and QMUL London contributing to the MLEnd Deception Dataset containing over 3,000 data entries of truthful and deceptive stories recorded in both English and students' native languages. 
