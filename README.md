# -Multi-Label-Emotion-Recognition-from-Text-

This repository contains a text classification model for multi-label emotion recognition, specifically designed to predict emotions from text inputs. The model utilizes a transformer-based architecture (e.g., BERT) fine-tuned on the **GoEmotions** dataset. The system can predict a wide range of emotions, including both positive and negative emotions, and it can categorize text with multiple emotions simultaneously.

## Features:
- **Multi-label Emotion Classification**: Predict multiple emotions per text.
- **Preprocessing**: Includes tokenization and other necessary preprocessing steps to prepare text data for the model.
- **Threshold Tuning**: Adjust the probability threshold to classify emotions based on a specified probability.
- **Model Evaluation**: Evaluation metrics such as F1-score and Hamming loss are tracked during training for performance assessment.
- **Flexible**: Easily adaptable for different datasets and classification tasks.

## Example Usage:
- **Input**: "The meeting went as expected, with no surprises."
- **Predicted Emotions**: 'neutral'

## Setup:
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Use the trained model to predict emotions from new text input.

## Metrics:
- F1 Score: Measures the balance between precision and recall.
- Hamming Loss: Measures the fraction of incorrect labels.

## Training:
The model is trained for 3 epochs, with a training loss of approximately 0.2993 and a validation loss of 0.2025. The training process tracked runtime and throughput metrics to optimize performance.

