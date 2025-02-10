Next Word Prediction with LSTM

Screenshot of the Streamlit Application Interface

Overview

This project implements an LSTM-based Next Word Prediction model trained on Shakespeare's Hamlet text. The model predicts the next most likely words based on user input, demonstrating the capabilities of sequence modeling in Natural Language Processing (NLP). The solution is deployed as an interactive web application using Streamlit.

Key Features

LSTM Neural Network: Uses Long Short-Term Memory networks for sequence prediction

Real-time Predictions: Provides instant word suggestions as users type

User-friendly Interface: Clean and intuitive web interface powered by Streamlit

Modular Codebase: Well-organized project structure for maintainability

Installation

Clone the repository:

git clone https://github.com/yourusername/sentence-predictor.git
cd sentence-predictor

Set up a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

Run the Streamlit application:

streamlit run src/app.py

Project Structure

sentence-predictor/
├── data/                   # Text data for training
│   └── hamlet.txt          
├── models/                 # Pretrained models and tokenizer
│   ├── next_word_lstm.h5
│   └── tokenizer.pkl
├── notebooks/              # Jupyter notebook for experimentation
│   └── experiments.ipynb  
├── src/                    # Streamlit application source code
│   └── app.py              
├── assets/                 # Screenshots and visual assets
│   └── screenshot.png
├── requirements.txt        # Dependency list
└── README.md               # Project documentation

Model Architecture

The LSTM model architecture consists of:

Embedding Layer (100 dimensions)

LSTM Layer (150 units)

Dropout Layer (0.2 rate)

Dense Output Layer (Softmax activation)

