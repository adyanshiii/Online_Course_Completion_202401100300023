# 🎓 Online Course Completion Prediction

This machine learning project aims to predict whether a student will complete an online course based on their activity logs such as videos watched, assignments submitted, and forum participation. The project uses a classification approach to support early intervention and increase course completion rates in e-learning platforms.

---

## 📁 Dataset

The dataset includes 100 samples with the following features:

- `videos_watched` – Number of lecture videos viewed
- `assignments_submitted` – Number of assignments turned in
- `forum_posts` – Posts made on course forums
- `completed` – Target variable indicating whether the student completed the course (`yes` or `no`)

---

## 📌 Objective

To build a predictive model using a supervised learning approach to classify students into two categories:
- Completed the course
- Did not complete the course

---

## 🛠️ Methodology

1. **Data Cleaning & Preprocessing**
   - Converted `completed` column from 'yes/no' to 1/0
   - Removed any missing or invalid entries
   - Standardized input features using `StandardScaler`

2. **Model Building**
   - Used a Random Forest Classifier
   - Train-test split: 80% training, 20% testing

3. **Evaluation**
   - Metrics: Accuracy, Precision, Recall
   - Confusion matrix and classification report for model analysis

---

## 📊 Results

- **Accuracy:** ~90%
- **Precision & Recall:** ~89–92%
- **Confusion Matrix:** Visual heatmap included in the output

---

## 📌 Dependencies

This project uses the following Python libraries:

```bash
pandas
numpy
seaborn
matplotlib
scikit-learn
