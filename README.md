# Suicide-Risk-Assessment-Agent
Suicide Detection using Machine Learning is an NLP-based binary text classification project that predicts whether a given text indicates suicidal intent or non-suicidal content. Built using Python, TF-IDF, Logistic Regression, and Linear SVM with preprocessing, evaluation, and model deployment support.





# 🧠 Suicide Detection using Machine Learning

## 📌 Project Overview

This project is a Machine Learning and Natural Language Processing (NLP) application that classifies text into **Suicide** or **Non-Suicide** categories. It uses text preprocessing, TF-IDF vectorization, and Machine Learning algorithms to detect suicidal intent from user-written text.

---

## 🚀 Features

- Text preprocessing and cleaning
- TF-IDF feature extraction
- Logistic Regression model
- Linear SVM model
- Model evaluation using Accuracy, Classification Report, and Confusion Matrix
- Save trained model using Pickle (.pkl)
- Predict custom user input

---

## 📂 Project Structure

```
Suicide-Detection/
│
├── Suicide_Detection.csv
├── Suicide_Detection.ipynb
├── logistic_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
├── README.md
└── screenshots/
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Pickle

---

## 📊 Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Remove Missing Values
4. Remove Duplicate Data
5. Text Preprocessing
6. Convert Labels
7. Train-Test Split
8. TF-IDF Vectorization
9. Train Models
10. Evaluate Models
11. Save Best Model
12. Predict New Text

---

## 🤖 Algorithms Used

- Logistic Regression
- Linear Support Vector Machine (SVM)

---

## 📈 Model Evaluation

Evaluation Metrics:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Suicide-Detection.git
```

### Move into the Project Folder

```bash
cd Suicide-Detection
```

### Create Virtual Environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / Mac**

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Suicide_Detection.ipynb
```

Run all cells.

---

## 🧪 Predict New Text

Example:

```python
text = ["I am happy and enjoying my life"]

text = vectorizer.transform(text)

prediction = model.predict(text)

print(prediction)
```

---

## 💾 Save Model

```python
import pickle

pickle.dump(lr, open("logistic_model.pkl", "wb"))
pickle.dump(tfidf, open("tfidf_vectorizer.pkl", "wb"))
```

---

## 📦 Requirements

Create a file named **requirements.txt**

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Install

```bash
pip install -r requirements.txt
```

---

## 📸 Output

The project predicts whether the given text belongs to:

- Suicide
- Non-Suicide

It also displays:

- Accuracy
- Classification Report
- Confusion Matrix

---

## 👩‍💻 Author

**Dukka Dhanalaxmi**

GitHub: https://github.com/Dukkadhanalaxmi

LinkedIn: https://www.linkedin.com/in/dukka-dhanalaxmi-271823362

---

## ⭐ If you found this project helpful, please give it a Star on GitHub.
