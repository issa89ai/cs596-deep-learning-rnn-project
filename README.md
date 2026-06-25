# CS596 – Special Topics on Deep Learning: RNN Project

## 📘 Course Information

- **Course:** CS596 – Research Topics in Computer Science (Special Topics on Deep Learning)  
- **Term:** Winter 2024  
- **Institution:** Bishop's University  
- **Project Type:** Final Project  
- **Topic:** Recurrent Neural Networks for Financial Time-Series Forecasting  

---

## 📌 Project Overview

This project explores **Recurrent Neural Networks (RNNs)** using **PyTorch**, with a focus on sequence modeling applied to financial time-series data (Apple stock prices from Yahoo Finance).

The project covers dataset preprocessing, model implementation, training, evaluation, and comparative analysis across RNN architectures.

---

## 🧠 Topics Covered

- Recurrent Neural Networks (RNN)
- LSTM and GRU architectures
- Sequence modeling and time-series forecasting
- PyTorch model implementation and training
- Model evaluation and performance comparison

---

## 📊 Dataset

- **Source:** Yahoo Finance
- **Stock:** Apple Inc. (AAPL)
- **Files:**
  - `yahoo finance dataset/AAPL_train_data.csv` — training data (historical prices)
  - `yahoo finance dataset/AAPL_test_data.csv` — test data
- **Features:** Date, Open, High, Low, Close, Adj Close, Volume

---

## 🛠️ Technologies Used

- Python 3
- PyTorch
- NumPy, Matplotlib
- Jupyter Notebook / Google Colab

---

## 📂 Repository Structure

```
cs596-deep-learning-rnn-project/
├── notebooks/
│   ├── CS596 Final Project.ipynb              # Main experiments notebook
│   └── CS596 Final Project Group FP B.ipynb  # Group version
├── yahoo finance dataset/
│   ├── AAPL_train_data.csv
│   └── AAPL_test_data.csv
├── report/
│   └── CS596 Final Project Group_FP B.pdf
├── docs/
│   └── CS596 Final Project Group_FP B.docx
├── .gitignore
└── README.md
```

---

## ▶️ How to Run

1. Open the notebook in Jupyter or Google Colab:
   ```bash
   jupyter notebook "notebooks/CS596 Final Project.ipynb"
   ```

2. Install required libraries:
   ```bash
   pip install torch torchvision numpy matplotlib pandas
   ```

---

## 📝 Notes

This project was developed as part of an academic course.  
The code is intended for educational and research purposes only.

## 👤 Author

**Ahmad Issa**  
Machine Learning Engineer | AI & Data Science  
[GitHub](https://github.com/issa89ai) · [LinkedIn](https://linkedin.com/in/ahmadissa)
