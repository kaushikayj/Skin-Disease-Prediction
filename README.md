# Skin Disease Prediction Using Machine Learning

This project uses machine learning models to predict skin diseases based on patient symptoms. It aims to assist in early diagnosis by providing an accurate prediction from a range of common skin conditions.

---

## 📂 Table of Contents

- [Demo](#-demo)
- [Problem Statement](#-problem-statement)
- [Technologies Used](#-technologies-used)
- [How It Works](#-how-it-works)
- [Dataset](#-dataset)
- [Model Used](#-model-used)
- [How to Run](#-how-to-run)
- [Results](#-results)
- [Future Work](#-future-work)
- [Contributors](#-contributors)
- [License](#-license)

---

## Demo

(Add a screenshot or link to your working web app or notebook output if available)

---

## 🧩 Problem Statement

Skin diseases often require professional diagnosis, which might not be accessible in all areas. This project provides a machine learning-based solution that predicts potential skin diseases using symptom data, helping bridge the gap in preliminary diagnosis.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit (for UI, if applicable)
- Matplotlib / Seaborn (for visualization)

---

## How It Works

1. Takes user input of visible symptoms.
2. Encodes the input to feed into the ML model.
3. Predicts the skin disease using trained classification models.
4. Displays the predicted result.

---

## 📊 Dataset

- The dataset contains symptoms and corresponding skin disease labels.
- Each row represents a combination of symptoms experienced by a patient.
- The target variable is the diagnosed skin disease.

---

## Model Used

- Decision Tree Classifier (or specify if you used Random Forest, SVM, etc.)
- Trained with labeled symptom data
- Evaluated using accuracy, precision, and recall

---

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/kaushikayj/Skin-Disease-Prediction.git
    cd Skin-Disease-Prediction
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the main script or app:
    ```bash
    python skin_disease_prediction.py
    ```

4. (Optional) If you used Streamlit:
    ```bash
    streamlit run app.py
    ```

---

## 📈 Results

- Achieved an accuracy of **XX%** on test data.
- Visualized feature importance and confusion matrix.
- Model successfully predicts diseases like eczema, psoriasis, acne, etc.

(Add charts if available.)

---

## Future Work

- Add image-based prediction using CNNs.
- Build a user-friendly web/mobile app interface.
- Improve dataset size and diversity.
---

> Feel free to fork this repo, suggest improvements, or contribute!
