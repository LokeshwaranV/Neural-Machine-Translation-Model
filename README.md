# Neural Machine Translation (NMT) Model Building

## Problem Statement

Welcome to the project on Neural Machine Translation (NMT) model building as part of your course on Natural Language Processing. This project focuses on building an attention-based sequence-to-sequence model for translating Spanish sentences to English. The goal is to help a US-based life insurance company communicate effectively with the Spanish-speaking community in Mexico by providing a machine translation model for application request letters.

<img src="NMT.jpg" alt="image" width="600" >

### Background

The US-based life insurance company faces a challenge in communicating with the Spanish-speaking community in Mexico due to language barriers. To overcome this challenge and provide coverage to the locals, the company needs a machine translation model that can accurately translate application request letters from Spanish to English.

### Problem Statement

Your task is to build an attention-based sequence-to-sequence model that can effectively understand the context of Spanish sentences and translate them into clear and coherent English sentences. The model will help ensure seamless communication and provide coverage to the Spanish-speaking community in Mexico.

### Importance of the Assignment

Building a Spanish-to-English translation model will help you understand the core basics of an attention-based-sequence-to-sequence model. This assignment will also help you understand some essential data-cleaning tasks specific to the Spanish language, such as dealing with special characters.

## Tasks

1. **Data Cleaning**: Preprocess the Spanish and English data to remove special characters and unnecessary spaces.
   
2. **Tokenization**: Tokenize the cleaned data into words and create vocabulary dictionaries for both languages.
   
3. **Padding**: Pad the tokenized sequences to ensure they have the same length.
   
4. **Model Building**: Build an attention-based sequence-to-sequence model using TensorFlow and Keras.
   
5. **Model Training**: Train the model on the preprocessed data.
   
6. **Model Evaluation**: Evaluate the model's performance using BLEU score and other metrics.
   
7. **Inference**: Use the trained model to translate new Spanish sentences into English.

## Dataset

The dataset used is a paired corpus of English-Spanish, provided by Anki. The process to download the dataset is provided in the notebook.
