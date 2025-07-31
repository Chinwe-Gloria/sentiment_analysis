# Sentiment Analysis on IMDb Movie Reviews using RNNs

This is a Natural Language Processing (NLP) project where I built a deep learning model to perform binary sentiment classification (positive or negative) on IMDb movie reviews.

## Project Highlights

- Built a basic RNN using `SimpleRNN`
- Enhanced the model with:
  - LSTM (Long Short-Term Memory)
  - Dropout for regularization
  - Batch Normalization
  - Model evaluation using confusion matrix and classification report
  - Visualizations of training history (accuracy/loss)
  - Custom review prediction support

## Dataset
- IMDb Movie Reviews Dataset  
- Preprocessed and tokenized via Keras  
- `num_words=10,000`, `max_len=200`

## Model Architecture (Enhanced)
Embedding → LSTM → BatchNormalization → Dropout → Dense

## Final Model Performance
- Validation Accuracy: 82.6%
- F1 Score: 0.84
- Confusion Matrix: Balanced performance on both positive and negative classes

## Visualizations
- Training vs. Validation Loss and Accuracy
- Confusion Matrix

## Prediction on Custom Input
Includes a method to test your own movie review text and predict its sentiment.

## Libraries Used
TensorFlow / Keras
Matplotlib, Seaborn
Scikit-learn
