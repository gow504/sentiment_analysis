# sentiment_analysis

# Sentiment Analysis Using LSTM (PyTorch)

A deep learning project that performs **binary sentiment classification** on movie reviews using a **Long Short-Term Memory (LSTM)** neural network implemented in **PyTorch**. The model is trained on the IMDB Movie Reviews dataset to classify reviews as **positive** or **negative**.

---

## Overview

This project demonstrates an end-to-end Natural Language Processing (NLP) pipeline, including text preprocessing, vocabulary creation, sequence encoding, model training, and sentiment prediction using an LSTM-based neural network.

---

## Features

* Text preprocessing and cleaning
  
* Stop-word removal

* Tokenization

* Vocabulary generation

* Sequence encoding and padding

* LSTM-based sentiment classification

* Model training and evaluation

* GPU support using PyTorch (if available)

---

## Dataset

* **Dataset:** IMDB Movie Reviews Dataset

* **Task:** Binary Sentiment Classification

* **Classes:**

  * Positive

  * Negative

---

## Technologies Used

* Python

* PyTorch

* Pandas

* NumPy

* NLTK

* Matplotlib

* Seaborn

* Scikit-learn

---

## Project Workflow

1. Load the IMDB movie reviews dataset

2. Clean and preprocess text

3. Remove stop words

4. Build vocabulary

5. Convert text into numerical sequences

6. Pad sequences

7. Split data into training and testing sets

8. Build an LSTM model using PyTorch

9. Train the model


10. Evaluate model performance

11. Predict sentiment for new reviews


---

## Model Architecture

* Embedding Layer


* LSTM Layer

* Fully Connected Layer

* Sigmoid Activation


---

## Evaluation Metrics

* Accuracy

* Loss

* Training Performance

* Validation Performance


---

## Installation

```bash
git clone https://github.com/gow504/machine_learning.git

cd machine_learning

pip install torch pandas numpy nltk matplotlib seaborn scikit-learn
```

---

## Run the Project

Launch Jupyter Notebook and open:

```text
sentiment_analysis_using_lstm_pytorch.ipynb
```

Run all cells sequentially to preprocess the data, train the model, and evaluate its performance.

---

## Project Structure

```text
sentiment_analysis_using_lstm_pytorch.ipynb
README.md
```

---

## Learning Outcomes

This project demonstrates practical knowledge of:

* Natural Language Processing (NLP)

* Text preprocessing

* Tokenization

* Sequence modeling

* Deep Learning with PyTorch

* Long Short-Term Memory (LSTM)

* Binary text classification

* Sentiment Analysis


---

## Future Improvements

* Use pre-trained word embeddings (GloVe or Word2Vec)

* Implement attention mechanisms

* Compare LSTM with GRU and Transformer models

* Deploy the model using Streamlit or Flask

* Add hyperparameter tuning and model checkpointing


---

## License


This project is intended for educational and learning purposes.
