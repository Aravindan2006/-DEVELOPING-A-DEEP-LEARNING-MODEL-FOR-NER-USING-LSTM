# Ex 06 - Developing a Deep Learning Model for Named Entity Recognition (NER) Using LSTM

## Overview

This project focuses on developing a Deep Learning model for Named Entity Recognition (NER) using Long Short-Term Memory (LSTM) networks. NER is a Natural Language Processing (NLP) task that identifies and classifies entities such as person names, locations, organizations, dates, and other important information in text.

The model is trained on annotated text data and learns contextual relationships between words to accurately predict entity labels.

## Objectives

* Understand the concept of Named Entity Recognition (NER).
* Implement an LSTM-based deep learning model for sequence labeling.
* Train and evaluate the model on annotated text datasets.
* Analyze the performance of the model using evaluation metrics.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

## Dataset

The dataset consists of sentences where each word is associated with a corresponding entity tag such as:

* PER (Person)
* LOC (Location)
* ORG (Organization)
* MISC (Miscellaneous)
* O (Non-entity)

## Methodology

1. Data Collection and Preprocessing
2. Tokenization and Vocabulary Creation
3. Sequence Padding
4. Label Encoding
5. Building the LSTM-based NER Model
6. Model Training and Validation
7. Performance Evaluation
8. Entity Prediction on New Sentences

## Model Architecture

* Embedding Layer
* LSTM Layer
* Dropout Layer
* Dense Output Layer with Softmax Activation

## Results

The LSTM model successfully learns contextual word representations and predicts named entities with good accuracy. The model demonstrates the effectiveness of recurrent neural networks for sequence labeling tasks.

## Applications

* Information Extraction
* Chatbots and Virtual Assistants
* Search Engines
* Document Analysis
* Automated Content Processing

## Conclusion

This experiment demonstrates how LSTM networks can be applied to Named Entity Recognition tasks. The model effectively identifies and classifies entities in text, making it useful for various NLP applications.
