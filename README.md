# 🎓 Cutoff Predictor

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Streamlit-red?logo=streamlit)](https://cutoff-predictor.streamlit.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/harshitabalpande/cut_off)

A Machine Learning-based application designed to predict college admission cutoffs. This project aims to help students explore cutoff predictions and make informed decisions during the college admission process.

## 🌐 Live Demo

🚀 **Try the application here:** [Cutoff Predictor – Streamlit App](https://cutoff-predictor.streamlit.app/)

## 📌 Project Overview

College admission cutoffs can vary depending on several admission-related factors. The Cutoff Predictor project uses a trained Machine Learning model to generate cutoff predictions based on the inputs supported by the application.

The application is built using Python and Streamlit, providing an accessible interface for users to interact with the prediction system.

## ✨ Features

- 🤖 Machine Learning-based cutoff prediction
- 🖥️ Interactive Streamlit interface
- ⚡ Quick prediction results
- 📊 Data-driven predictions
- 🌐 Accessible through a live web application

## 🛠️ Technologies Used

- **Python** – Programming language
- **Streamlit** – Web application framework
- **Machine Learning** – Prediction model
- **Pickle** – Model serialization
- **Python Libraries** – Project dependencies

## 📂 Project Structure

```text
cut_off/
│
├── app.py              # Main Streamlit application
├── check_model.py      # Model checking script
├── model.pkl           # Saved Machine Learning model
├── requirements.txt    # Required Python libraries
├── runtime.txt         # Python runtime configuration
└── README.md           # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/harshitabalpande/cut_off.git
```

### 2. Navigate to the project directory

```bash
cd cut_off
```

### 3. Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal to access the application.

## 🔍 How It Works

1. The user enters the required information in the application.
2. The application processes the input data.
3. The trained Machine Learning model generates a prediction.
4. The predicted cutoff is displayed to the user.

*The exact input fields and prediction logic depend on the implementation.*

## 🎯 Project Objective

The objective of this project is to explore the use of Machine Learning for college admission cutoff prediction and provide students with an easy-to-use tool for exploring admission possibilities.

## 🔮 Future Improvements

- Improve model performance through evaluation and tuning.
- Include more recent admission cutoff data.
- Add college-wise and category-wise comparisons where supported by the dataset.
- Improve prediction accuracy and the user interface.
- Expand the dataset to cover more colleges and admission scenarios.

## 👩‍💻 Author

**Harshita Balpande**

B.Tech in Artificial Intelligence

- **GitHub:** [harshitabalpande](https://github.com/harshitabalpande)
- **Project Repository:** [Cutoff Predictor](https://github.com/harshitabalpande/cut_off)
- **Live Application:** [Open Cutoff Predictor](https://cutoff-predictor.streamlit.app/)

---

⭐ If you find this project useful, consider giving the repository a star!
