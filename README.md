# 🚀 Transformer-Based French → English Neural Machine Translation

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red.svg)]()
[![NLP](https://img.shields.io/badge/Domain-NLP-green.svg)]()
[![Transformer](https://img.shields.io/badge/Architecture-Transformer-orange.svg)]()

## 📌 Project Overview

This project implements a **Transformer-based Neural Machine Translation (NMT)** system for translating **French sentences into English**. Inspired by Google's landmark research paper **"Attention Is All You Need"**, the model is built using PyTorch and leverages self-attention mechanisms to learn contextual representations for high-quality machine translation.

The project includes model development, training pipelines, FastText-based embeddings, experimental notebooks, and a Streamlit-based web application for interactive translation.

---

## 🎯 Objectives

* Build a Transformer architecture from scratch.
* Understand and implement self-attention mechanisms.
* Perform French → English neural machine translation.
* Compare traditional sequence-to-sequence approaches with Transformer models.
* Deploy a user-friendly web interface for inference.

---

## 🧠 Key Features

✅ Transformer Architecture implemented from scratch

✅ Multi-Head Self Attention

✅ Positional Encoding

✅ Encoder–Decoder Framework

✅ Feed Forward Neural Networks

✅ FastText Word Embeddings

✅ Sequence-to-Sequence Learning

✅ French → English Translation

✅ Interactive Web Application

✅ Modular and Reusable Codebase

---

## 🏗️ Architecture

The model follows the architecture proposed in:

> Vaswani et al., "Attention Is All You Need", NeurIPS 2017

### Core Components

* Input Embeddings
* Positional Encoding
* Multi-Head Attention
* Encoder Layers
* Decoder Layers
* Feed Forward Networks
* Residual Connections
* Layer Normalization
* Softmax Output Layer

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Deep Learning

* PyTorch
* fastai

### NLP

* FastText Embeddings
* Neural Machine Translation
* Sequence Modeling

### Deployment

* Streamlit

### Data Processing

* NumPy
* Pandas

### Visualization

* Matplotlib

---

## 📂 Project Structure

```text
ML-DL-1-main/
│
├── Fr2En_MachineTranslation_experiment.ipynb
├── Fr2En_MachineTranslation_final.ipynb
├── fastext_embeddings.py
├── notebook2script.py
│
├── modules/
│   ├── model.py
│   ├── callbacks.py
│   └── __init__.py
│
├── transformer/
│   └── model.py
│
├── WebApp/
│   ├── app.py
│   ├── modules/
│   └── transformer/
│
├── Snapshots/
│   ├── AttentionScore_Calc.png
│   ├── MultiHead_Attention.png
│   ├── Decoder_stru.png
│   └── ...
│
└── Attention_is_all_you_need.pdf
```

---

## 🔬 Machine Learning Concepts Covered

### Deep Learning

* Neural Networks
* Sequence Modeling
* Gradient Optimization

### Natural Language Processing

* Tokenization
* Embeddings
* Neural Machine Translation
* Language Representation

### Transformer Concepts

* Self Attention
* Multi Head Attention
* Positional Encoding
* Encoder-Decoder Architecture
* Residual Connections
* Layer Normalization

---

## 📊 Results

The Transformer model successfully learns contextual relationships between French and English sentence pairs and generates meaningful translations using attention-based sequence modeling.

Key achievements:

* Better contextual understanding compared to traditional RNN-based approaches
* Parallelized training through self-attention
* Improved long-range dependency capture
* Efficient inference through Transformer architecture

---

## 💻 Running the Project

### Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Training Notebook

```bash
jupyter notebook Fr2En_MachineTranslation_final.ipynb
```

### Launch Web Application

```bash
cd WebApp
streamlit run app.py
```

---

## 📈 Future Improvements

* Integrate Pretrained Transformer Models
* Fine-tune on Larger Parallel Corpora
* Add BLEU Score Evaluation
* Deploy on AWS EC2
* Dockerize the Application
* Implement Beam Search Decoding
* Support Multiple Languages

---

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience with:

* Transformer Architecture
* Attention Mechanisms
* Neural Machine Translation
* PyTorch Model Development
* Deep Learning Workflows
* NLP Pipelines
* Model Deployment using Streamlit

---

## 📚 References

1. Vaswani et al., *Attention Is All You Need* (2017)
2. PyTorch Documentation
3. fastai Documentation
4. FastText Documentation

---

## 👨‍💻 Author

**Abhinav Kumar**

Machine Learning | Deep Learning | NLP | Generative AI

🔗 GitHub: https://github.com/abhinav8002/Generative-LLMs

If you found this project useful, consider giving it a ⭐ on GitHub.
