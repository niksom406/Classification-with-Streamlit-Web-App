# 🌸 Iris Flower Classification - Streamlit Web App

A simple and interactive web app built using **Streamlit** to classify iris flowers using a **Random Forest Classifier**. Users can input flower measurements using sliders and instantly get a predicted species.

---

## 🚀 Features

- Live prediction of Iris flower species
- Clean and responsive UI using Streamlit sidebar
- Uses **scikit-learn**'s built-in Iris dataset
- Fast and accurate model: Random Forest Classifier

---

## 📊 Dataset

- Built-in **Iris dataset** from `scikit-learn`
- Features:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- Target classes:
  - Setosa
  - Versicolor
  - Virginica

---

## 🧠 Model

- **Random Forest Classifier** (from `sklearn.ensemble`)
- Trained on the entire dataset during runtime
- Predicts based on user-input feature values

---

## 🖥️ App Interface

Users interact with the app via sidebar sliders:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

Upon changing values, the app displays the **predicted iris species** instantly.

---

## ▶️ How to Run

### 🔧 Prerequisites

Make sure you have Python installed. Then install the required libraries:

```bash
pip install streamlit pandas scikit-learn
```

### 🏃 Run the App

```bash
streamlit run app.py
```

Your default browser will open the app automatically.

---

## 📁 File Structure

```
Classification-with-Streamlit-Web-App/
├── app.py             # Main Streamlit application
├── README.md          # Project documentation
└── requirements.txt   # (Optional) Dependencies file
```

---

## 📦 Optional: `requirements.txt`

Create this file to simplify environment setup:

```
streamlit
pandas
scikit-learn
```

---

## 📄 License

This project is open-source and free to use for educational and research purposes.

---

## 🙌 Acknowledgements

- [Streamlit](https://streamlit.io/)
- [scikit-learn](https://scikit-learn.org/)
- Iris dataset by Ronald Fisher
