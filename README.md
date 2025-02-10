# Next Word Prediction with LSTM

![Streamlit Interface](./assets/screenshot.jpeg)  
*Screenshot of the Streamlit Application Interface*

## Overview
This project implements an LSTM-based Next Word Prediction model trained on Shakespeare's Hamlet text. The model predicts the next most likely words based on user input, demonstrating the capabilities of sequence modeling in Natural Language Processing (NLP). The solution is deployed as an interactive web application using Streamlit.

## Key Features
- **LSTM Neural Network**: Uses Long Short-Term Memory networks for sequence prediction
- **Real-time Predictions**: Provides instant word suggestions as users type
- **User-friendly Interface**: Clean and intuitive web interface powered by Streamlit
- **Modular Codebase**: Well-organized project structure for maintainability

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/sentence-predictor.git
cd sentence-predictor
```

2.Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3.Install dependencies:
```bash
pip install -r requirements.txt
```
4.Run the Streamlit application:
```bash
streamlit run src/app.py
```
