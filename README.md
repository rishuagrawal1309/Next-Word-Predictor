# 🔮 Next Word Prediction using Deep Learning (LSTM)

Ever wondered how your keyboard knows what you’re going to type next?  
This project is a **Next Word Prediction system** built using **Deep Learning (LSTM)** that learns language patterns from text and predicts the most probable next word in a sentence.

---

## 🚀 Project Overview

This project implements a **Natural Language Processing (NLP)** model using **Long Short-Term Memory (LSTM)** networks to predict the next word in a given text sequence.  
The model is trained on a large corpus of text and captures **context, grammar, and sequential dependencies** in language.

It demonstrates how deep learning powers features like:
- Autocomplete
- Text suggestion
- Smart typing assistants

---

## 🧠 How It Works

1. **Text Preprocessing**
   - Tokenization
   - Sequence generation
   - Padding for uniform input length

2. **Model Architecture**
   - Embedding Layer
   - LSTM Layer(s)
   - Dense + Softmax Output Layer

3. **Training**
   - Categorical Cross-Entropy Loss
   - Adam Optimizer
   - Sequence-to-one prediction

4. **Prediction**
   - Given a sentence fragment, the model predicts the **most likely next word**

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **LSTM (Recurrent Neural Networks)**
- **NumPy**
- **Natural Language Processing (NLP)**

---

## 📊 Model Architecture

```text
Input Text → Tokenizer → Embedding Layer → LSTM → Dense → Softmax → Next Word
