# 🔮 Next Word Prediction using LSTM (Deep Learning NLP)

This project implements a **Next Word Prediction system** using **Recurrent Neural Networks (RNN)** with **LSTM layers**.  
The model learns sequential language patterns from text data and predicts the most probable next word for a given input sentence.

---

## 📌 Project Overview

Next Word Prediction is a core task in **Natural Language Processing (NLP)**.  
This project uses a deep learning–based LSTM architecture to capture long-term dependencies between words.

**Example:**
```
Input  : To be or not to be
Output : considered
```

---

## 🧠 Model Architecture

The model is built using **TensorFlow / Keras** with the following layers:

- Embedding Layer – Converts words into dense vector representations  
- LSTM Layer (return_sequences=True) – Learns contextual dependencies  
- Dropout Layer – Reduces overfitting  
- Second LSTM Layer – Extracts higher-level sequence features  
- Dense Output Layer (Softmax) – Predicts the next word from the vocabulary  

---

## ⚙️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Jupyter Notebook  
- Natural Language Processing (NLP)

---

## 📂 Project Structure

```
LSTM-RNN/
│
├── experiments.ipynb
├── hamlet.txt
├── requirements.txt
└── README.md
```

---

## 🔄 Data Preprocessing

- Text cleaning and tokenization  
- N-gram sequence generation  
- Padding sequences to fixed length  
- One-hot encoding of target labels  

---

## 📉 Training Details

- Loss Function: Categorical Crossentropy  
- Optimizer: Adam  
- Evaluation Metric: Accuracy  

---

## ▶️ How to Run

1. Clone the repository
```
git clone https://github.com/your-username/next-word-prediction-lstm.git
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Open Jupyter Notebook
```
jupyter notebook experiments.ipynb
```

4. Run all cells to train and test the model

---

## 🚀 Applications

- Text auto-completion  
- Chatbots  
- Writing assistants  
- Language modeling  
- NLP-based systems  

---

## 📌 Future Enhancements

- Train on larger datasets  
- Improve predictions using Beam Search  
- Add Transformer-based models  
- Deploy as a web application  

---

## 👤 Author

**Aryan Gupta**  
Information Technology Student  
Machine Learning | Deep Learning | NLP  

---

⭐ If you like this project, give it a star!

