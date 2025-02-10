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

##Project Structure
```bash
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
│   └── screenshot.jpeg
├── requirements.txt        # Dependency list
└── README.md               # Project documentation
```

## Model Architecture
The LSTM model architecture consists of:

Embedding Layer (100 dimensions)

LSTM Layer (150 units)

Dropout Layer (0.2 rate)

Dense Output Layer (Softmax activation)


## Contributing
Contributions are welcome! Please follow these steps:

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request
