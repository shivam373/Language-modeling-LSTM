# 📚 Language Modeling with LSTM

This project implements a **next-word prediction model** using an **LSTM-based language model** built with **TensorFlow**, **Keras**, **scikit-learn**, and **NumPy**. It's a great example of how to apply deep learning to natural language processing tasks, especially sequence prediction.

## 🚀 Features

- Train an LSTM-based language model on a custom text corpus
- Predict the next word given a sequence of words
- Built entirely using TensorFlow/Keras
- Simple and interactive Jupyter Notebook interface

## 🧠 Model Overview

The model is a sequential LSTM network that learns the structure and patterns of a text corpus and predicts the most likely next word in a given input sequence.

## 🛠️ Tech Stack

- 🧠 TensorFlow & Keras – Deep learning framework
- 📊 NumPy – Numerical operations and preprocessing
- 📈 scikit-learn – Utilities like `train_test_split`
- 📝 Jupyter Notebook – Development and experimentation

## 📂 Project Structure
Language-modeling-LSTM/ <br> 
  │  <br>
  ├── next_word_predictor_LSTM.ipynb # Main notebook with model training & prediction <br>
  ├── requirements.txt # List of dependencies <br>
  └── README.md # Project documentation <br>

## ✅ Installation

1. Clone the repository:

```bash
git clone https://github.com/shivam373/Language-modeling-LSTM.git
cd Language-modeling-LSTM
```
2. Install dependencies (recommended inside a virtual environment):
```bash
pip install -r requirements.txt
```
3. Launch the notebook:
```bash
jupyter notebook
```

🧪 How to Use
The notebook loads a sample text corpus and processes it.

Text is tokenized and sequences are created for training.

The LSTM model is trained on the sequences.

After training, you can input a phrase and the model will predict the next word.

Example input: "deep learning is"
Example output: "fun"

📈 Future Improvements
Add a larger or customizable dataset option

Improve text cleaning and preprocessing

Implement beam search or sampling for more creative predictions

Save and load trained models

🤝 Contributing
Contributions are welcome! If you find bugs or want to improve something, feel free to open an issue or a pull request.

