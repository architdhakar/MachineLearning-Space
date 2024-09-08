Emoji Predictor Using RNN (LSTM Model)
This project is an emoji prediction system built using Recurrent Neural Networks (RNN) with LSTM layers. The model is trained on the Twitter dataset and leverages pre-trained GloVe embeddings for learning word representations.

Table of Contents
Overview
Features
Installation
Dataset
Data Preprocessing
Model Architecture
Training
Results
How to Use
References
Overview
The project uses a deep learning approach to predict emojis based on the input text. It involves:

Data cleaning
Embedding learning with GloVe
Text tokenization
Model training with RNN (LSTM)
Features
Preprocesses text data to remove unnecessary characters.
Learns word embeddings using pre-trained GloVe.
Predicts the most relevant emoji based on the input text.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-repo/emoji-predictor.git
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Dataset
The model was trained using a Twitter dataset that includes text and corresponding emojis. The data was preprocessed to clean text, tokenize it, and prepare it for model input.

Data Preprocessing
The preprocessing steps include:

Removing URLs, mentions, and special characters from text.
Tokenizing the text using Keras' Tokenizer.
Padding sequences to ensure uniform input size for the LSTM model.
Converting emojis to categorical labels.

Embedding Layer
The model uses pre-trained GloVe embeddings to convert words into dense vectors. This helps the model learn better word relationships, which enhances emoji prediction.

Model Architecture
The model is built using RNN's LSTM layers to capture temporal dependencies in the text.

Embedding Layer: Uses GloVe embeddings.
LSTM Layer: Captures the sequence dependencies.
Dense Layers: Outputs the probabilities for each emoji class.

Training
The model was trained for multiple epochs, using a categorical cross-entropy loss function. Early stopping was applied to avoid overfitting.

Training Configuration
Batch Size: 64
Epochs: 20
Optimizer: Adam

Results
After training, the model was able to predict emojis with reasonable accuracy based on the input text. 
The model will output the most relevant emoji for the provided text.
References
GloVe: Global Vectors for Word Representation
Twitter dataset (source of the data).
