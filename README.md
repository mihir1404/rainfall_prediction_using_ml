# 🌧️ Rainfall Prediction Using Machine Learning

This project implements a machine learning pipeline to predict whether it will rain tomorrow based on meteorological data. The notebook explores data preprocessing, visualization, model training, and evaluation using standard ML techniques.

---

## 📌 Overview

- **Goal**: Predict `RainTomorrow` (Yes/No)
- **Tech stack**: Python, Jupyter Notebook, Scikit-learn, Pandas, Matplotlib, Seaborn
- **ML Models Used**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier

---

## 📁 Repository Structure

```
rainfall_prediction_using_ml/
│
├── rainfall_prediction_using_ml.ipynb   # Main Jupyter Notebook
├── README.md                            # Project documentation
```

---

## 📊 Dataset

- **Source**: Australian weather data
- **Features Include**:
  - MinTemp, MaxTemp
  - Rainfall
  - WindSpeed, WindDir
  - Humidity, Pressure
  - Cloud, Temp at 9am/3pm
  - RainToday, RainTomorrow (target)

> ⚠️ Ensure the CSV dataset (e.g., `Rainfall.csv`) is available in the notebook directory.

---

## 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/rainfall_prediction_using_ml.git
   cd rainfall_prediction_using_ml
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook rainfall_prediction_using_ml.ipynb
   ```

---

## 📈 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1 Score

---

## ✅ Dependencies

You can generate a `requirements.txt` file using the following:

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---



---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
