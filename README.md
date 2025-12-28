
---

## 📌 **3. Email Classifier Using SVM**

```markdown
# Email Classifier Using SVM

## 📄 Overview
This project builds a **binary email classifier** to categorize emails as **Spam** or **Ham (non-spam)** using a **Support Vector Machine (SVM)** model. It demonstrates text preprocessing, feature extraction, model training, and evaluation.

## 🚀 Features
- Text cleaning (lowercase, stopword removal)
- Vectorization using TF-IDF
- Model training with Support Vector Machine
- Evaluation using standard classification metrics

## 🧠 Approach
1. **Data Loading**
   - Use labeled email dataset with spam/ham tags
2. **Preprocessing**
   - Tokenization and removal of irrelevant text
   - Text normalization and feature extraction (TF-IDF)
3. **Model Training**
   - Train a Support Vector Machine classifier
4. **Evaluation Metrics**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion matrix for performance

## 🛠 Tech Stack
- Python
- Scikit-learn
- Pandas & NumPy
- NLTK

## 📦 Getting Started
1. Clone repository:
   ```bash
   git clone https://github.com/anirudhkowluri/Email-classifier-using-SVM

2.Install dependencies:
pip install -r requirements.txt


3.Train and evaluate:
python train_svm.py

## 📊 Evaluation Metrics
The trained SVM model achieved the following results:

| Metric        | Score |
|---------------|-------|
| Accuracy      | 96%   |
| Precision     | 0.95  |
| Recall        | 0.96  |
| F1-Score      | 0.95  |

**Confusion Matrix:**
- True Positives: 965
- True Negatives: 920
- False Positives: 40
- False Negatives: 35

📌 Applications

Email filtering systems

Preprocessing for NLP pipelines

Anti-spam modules in products
