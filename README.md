# Next Word Predictor using LSTM

This project is a Deep Learning based Next Word Prediction system built using LSTM (Long Short-Term Memory) networks in TensorFlow/Keras.

The model is trained on Shakespeare's *Hamlet* text dataset and predicts the next word based on the given input sequence.

---

## Features

- Next word prediction using LSTM
- NLP text preprocessing using Tokenizer
- Streamlit web application
- TensorFlow/Keras implementation
- Trained on Shakespeare text dataset

---

## Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Streamlit
- NLP

---

## Project Structure

```bash
.
├── app.py
├── exp.ipynb
├── hamlet.txt
├── next_word_lstm.h5
├── tokenizer.pickle
├── requirements.txt
└── .gitignore
```

---

## Dataset

The dataset used is:

- Hamlet by William Shakespeare

---

## Installation

Clone the repository:

```bash
git clone https://github.com/priyanshuu-x/Next-Word-Predictor-LSTM.git
```

Move into the project folder:

```bash
cd Next-Word-Predictor-LSTM
```

Create virtual environment:

```bash
python -m venv venv
```

Activate virtual environment:

### Windows
```bash
venv\Scripts\activate
```

### Mac/Linux
```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run app.py
```

---

## How It Works

1. Text dataset is tokenized
2. Sequences are generated
3. LSTM model is trained on sequences
4. Model predicts probability distribution of next word
5. Word with highest probability is returned

---

## Future Improvements

- Add Transformer-based prediction
- Improve dataset size
- Deploy using Streamlit Cloud
- Add top-k predictions
- Add better UI

---

## Author
Priyanshu Singh
GitHub: https://github.com/priyanshuu-x
