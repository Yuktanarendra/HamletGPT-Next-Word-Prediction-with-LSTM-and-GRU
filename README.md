# HamletGPT – Next Word Prediction using LSTM & GRU

## 📖 Project Overview

HamletGPT is a Deep Learning and Natural Language Processing (NLP) project that predicts the next word in a sequence using Recurrent Neural Networks (RNNs). The project implements two advanced sequence modeling architectures:

* **LSTM (Long Short-Term Memory)**
* **GRU (Gated Recurrent Unit)**

The models are trained on the complete text of William Shakespeare’s *Hamlet* to learn contextual relationships, language patterns, and sequential dependencies for intelligent next-word prediction.

An interactive **Streamlit web application** is also developed to allow users to generate predictions in real time and compare the outputs of both LSTM and GRU models.

---

# 🚀 Features

* Implementation of both **LSTM** and **GRU** architectures
* Text preprocessing and sequence generation
* Tokenization and sequence padding
* Deep learning model training using TensorFlow/Keras
* Real-time next-word prediction
* Interactive Streamlit web application
* Saved trained models for faster inference
* Tokenizer persistence using Pickle

---

# 🛠️ Tech Stack

* Python
* TensorFlow
* Keras
* NLTK
* NumPy
* Pandas
* Scikit-learn
* Streamlit
* Deep Learning
* Natural Language Processing (NLP)

---

# 📂 Project Structure

```bash
HamletGPT-Next-Word-Prediction-with-LSTM-and-GRU/
│
├── next_word_prediction.py
├── streamlit_app.py
├── hamlet.txt
├── next_word_lstm.h5
├── GRU-MODEL.h5
├── tokenizer.pickle
├── requirements.txt
└── README.md
```

---

# ⚙️ How It Works

## 1️⃣ Data Loading

The Hamlet text dataset is loaded using the NLTK Gutenberg corpus or text file.

## 2️⃣ Text Preprocessing

* Convert text into lowercase
* Remove unnecessary characters
* Tokenize text into sequences

## 3️⃣ Sequence Generation

Input sequences are generated using n-gram token patterns.

Example:

```text
To be
To be or
To be or not
```

## 4️⃣ Padding

Sequences are padded to maintain uniform input length.

## 5️⃣ Model Training

Both LSTM and GRU models are trained using:

* Adam Optimizer
* Categorical Crossentropy Loss Function

## 6️⃣ Prediction

The trained model predicts the most probable next word based on the given input sequence.

---

# 🧠 Model Architectures

## 🔹 LSTM Model

* Embedding Layer
* LSTM Layer (150 units)
* LSTM Layer (100 units)
* Dropout Layer (0.2)
* Dense Output Layer with Softmax Activation

## 🔹 GRU Model

* Embedding Layer
* GRU Layer (150 units)
* GRU Layer (100 units)
* Dropout Layer (0.2)
* Dense Output Layer with Softmax Activation

---

# 💻 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/your-username/HamletGPT-Next-Word-Prediction-with-LSTM-and-GRU.git

cd HamletGPT-Next-Word-Prediction-with-LSTM-and-GRU
```

---

# 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Train the Models

```bash
python next_word_prediction.py
```

This will generate:

* `next_word_lstm.h5`
* `GRU-MODEL.h5`
* `tokenizer.pickle`

---

# 🌐 Run Streamlit Application

```bash
streamlit run streamlit_app.py
```

Open browser:

```text
http://localhost:8501
```

---

# 📊 Key Concepts Implemented

* Natural Language Processing (NLP)
* Sequence Modeling
* Recurrent Neural Networks (RNNs)
* LSTM Networks
* GRU Networks
* Deep Learning
* Tokenization & Padding
* Predictive Text Generation

---

# 🎯 Future Improvements

* Transformer-based architecture integration
* GPT-style text generation
* Beam Search Decoding
* Multi-sentence text generation
* Attention Mechanism integration
* Deploy using Docker & Cloud Platforms

---

# 📸 Demo

Live Demo:
https://shorturl.at/nQz2Z

---

# 🤝 Contributions

Contributions, issues, and feature requests are welcome!

---

# 📜 License

This project is open-source and available under the MIT License.




