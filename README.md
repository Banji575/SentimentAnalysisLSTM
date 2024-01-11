# Sentiment Analysis with Bidirectional LSTM

## Description
This repository contains a sentiment analysis project on textual data using Bidirectional Long Short-Term Memory (LSTM) networks in TensorFlow. The project encompasses the entire workflow from data preprocessing and model creation to training, validation, and testing.

## Key Features
- Utilizes TensorFlow and Keras for building and training neural networks.
- Implements Bidirectional LSTM for improved contextual understanding of text.
- Processes real textual data and analyzes it for sentiment.
- Splits data into training, validation, and testing sets for robust model evaluation.
- Computes performance metrics including accuracy and confusion matrix.

## Getting Started
To get started with this project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/Banji575/SentimentAnalysisLSTM
cd SentimentAnalysisLSTM
# Install necessary dependencies, for example, via pip
pip install -r requirements.txt 
```

## Project Structure
- data_processing.py: Script for data preprocessing.
- model.py: Definition of the LSTM model for sentiment analysis.
- train.py: Script to train the model.
- evaluate.py: Script to evaluate the model's performance.

## Training and Evaluating the Model
To train the model, run the following command:

```bash
python train.py
```

After training the model, you can evaluate its performance using:

```bash
python evaluate.py
```

## Contributions
Any contributions, bug fixes, or feature enhancements are welcome.

## License
This project is distributed under the MIT License.
