Developed a Transformer-based sentiment analysis model using attention mechanisms.

# Sentiment Analysis using RNN and Transformer

## Project Overview
This project focuses on sentiment analysis using deep learning approaches. The IMDB dataset is utilized to train RNN-based and Transformer-based models for text classification.

## Dataset Details
- **Dataset**: IMDB Movie Review Sentiment Classification
- **Total Samples**: 50,000 (25K training, 25K testing)
- **Maximum Vocabulary Size**: 20,000 words
- **Maximum Sequence Length**: 200 words

## Models Implemented
1. **RNN-Based Models**
   - Bidirectional SimpleRNN
   - Bidirectional LSTM
   - Bidirectional GRU
2. **Transformer-Based Model**
   - Modified Transformer with Two Stacked Encoder Blocks

## Training Process
1. **RNN-Based Models**
   - Implemented three variations.
   - Trained on the IMDB dataset.
   - Evaluated using Confusion Matrix, Precision, Recall, and F1-Score.
   - Results visualized using bar plots.
2. **Transformer-Based Model**
   - Implemented Transformer with two stacked encoder blocks.
   - Trained on IMDB dataset.
   - Evaluated using Confusion Matrix and performance metrics.

## Results
For each model, the following were generated:
- Confusion Matrix
- Precision, Recall, and F1-Score

## File Structure
```

│── C1_RNN.ipynb
│── C2_Transformer.ipynb
│── C1_RNN.pdf
│── C2_Transformer.pdf
```

## How to Run
1. **Enable GPU Runtime** in Google Colab.
2. Run `C1_RNN.ipynb` to train and evaluate RNN models.
3. Run `C2_Transformer.ipynb` to train and evaluate Transformer model.
4. Evaluate final models and generate performance metrics.

## Author
Priyanka A  

