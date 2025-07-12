# 📝 Automated Essay Scoring (AES) using NLP

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/competitions/asap-aes/data)

This project implements an **Automated Essay Scoring (AES)** system using deep learning and Natural Language Processing (NLP). It aims to emulate human evaluators by providing consistent and objective essay scores based on linguistic and semantic features.

---

## 🚀 Features

- 📚 **Preprocessing**: Clean text, tokenize, remove stopwords, and apply GloVe embeddings
- 🤖 **Model**: LSTM-based Recurrent Neural Network
- 📊 **Evaluation Metric**: Quadratic Weighted Kappa (QWK)
- 📁 **Dataset**: [ASAP AES Dataset (Kaggle)](https://www.kaggle.com/competitions/asap-aes/data)
- 🔄 **Score Normalization**: Map predicted values to valid scoring range

---

## 🧠 Techniques Used

- **Natural Language Processing (NLP)**
- **Word Embeddings (GloVe)**
- **LSTM RNN (Sequential Modeling)**
- **Custom Loss & Evaluation Function (QWK)**

---

## 🛠️ Installation

```bash
git clone https://github.com/abin2273/aes-nlp-project.git
cd aes-nlp-project
pip install -r requirements.txt
Requirements (main):

Python 3.8+

TensorFlow / Keras

Numpy, Pandas, Scikit-learn

NLTK

Matplotlib, Seaborn

📈 Usage
Download the dataset from the ASAP AES Kaggle competition

Place the dataset in the data/ folder

Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook project_AES_(NLP).ipynb
Evaluate model performance and visualize results.

📊 Example Output
Essay Score Prediction: 4.2 → Rounded to 4

Quadratic Weighted Kappa: 0.78+

Loss Curves and Score Distributions visualized

✅ Future Improvements
Integrate Transformer models (e.g., BERT-based scoring)

Add real-time essay grading UI with Streamlit

Support multilingual essay scoring

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or improve.

📄 License
This project is licensed under the MIT License.
