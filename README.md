# 🎓 Cutoff Prediction System

A Machine Learning-based project designed to predict college admission cutoffs using relevant admission-related data. The project aims to help students explore cutoff predictions and make more informed decisions while selecting colleges.

## 📌 Project Overview

Choosing a college can be challenging for students because admission cutoffs vary based on several factors. This project uses a trained Machine Learning model to estimate cutoffs based on the input features supported by the application.

## ✨ Features

- 🤖 Machine Learning-based cutoff prediction
- 📊 Data-driven predictions
- 🖥️ Interactive application interface
- ⚡ Quick prediction results
- 🎯 Helps students explore college admission possibilities

## 🛠️ Technologies Used

- **Python** – Core programming language
- **Machine Learning** – Prediction model
- **Pickle** – Saving and loading the trained model
- **Python Libraries** – Dependencies listed in `requirements.txt`

## 📂 Project Structure

```text
cut_off/
│
├── app.py              # Main application
├── check_model.py      # Model checking script
├── model.pkl           # Saved ML model
├── requirements.txt    # Required Python libraries
├── runtime.txt         # Python runtime configuration
└── README.md           # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the repository

bash
git clone https://github.com/harshitabalpande/cut_off.git

### 2. Open the project folder

bash
cd cut_off

### 3. Create a virtual environment (optional)

bash
python -m venv venv

Activate it on Windows:

bash
venv\Scripts\activate

### 4. Install dependencies

bash
pip install -r requirements.txt

### 5. Run the application

If the application uses Streamlit:

`bash
streamlit run app.py


Otherwise, run it using the framework specified in `app.py`.

## 🚀 How It Works

1. The user enters the required admission-related information.
2. The application processes the input.
3. The trained Machine Learning model (`model.pkl`) generates a prediction.
4. The application displays the predicted cutoff.

*The exact input fields and prediction logic depend on the implemented model.*

## 🎯 Project Objective

The main objective of this project is to explore how Machine Learning can be applied to admission cutoff prediction and help students make better-informed college selection decisions.

## 🔮 Future Improvements

- Add more admission-related datasets.
- Improve model performance through evaluation and tuning.
- Include college-wise and category-wise cutoff comparisons, where supported by available data.
- Develop a more user-friendly interface.
- Update the model with recent admission data.

## 👩‍💻 Author

**Harshita Balpande**

B.Tech – Artificial Intelligence

GitHub: [harshitabalpande](https://github.com/harshitabalpande)

---

⭐ If you find this project useful, consider giving the repository a star!
