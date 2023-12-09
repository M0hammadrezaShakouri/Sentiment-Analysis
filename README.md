# Sentiment-Analysis

## Data Preprocessing:

The data undergoes preprocessing to enhance its quality:

- Removal of special characters.
- Elimination of single characters and spaces.
- Conversion of all words to lowercase.

## LSTM Neural Network Model:

The project utilizes an LSTM neural network model with pre-trained word embeddings based on Glove embeddings (`glove.6B.50d`) from a large Twitter US Airline database.

## Steps for Result Improvement and Analysis:

1. Integration of Dropout layers to prevent overfitting.
2. Adjustment of the learning rate from 0.1 to 0.001 for fine-tuning.
3. Set the batch size to 200 for efficient training.
4. Incorporation of validation data for performance assessment.

These measures collectively optimize the model's performance and facilitate comprehensive result analysis.

