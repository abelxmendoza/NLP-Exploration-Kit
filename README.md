# Natural Language Processing Project

## Introduction

Welcome to the Natural Language Processing (NLP) project! This project is part of a series of experiments in the field of artificial intelligence and language understanding. In this particular project, we'll dive into NLP to build a model that understands and generates human-like text.

## Project Overview

The main goal of this project is to create a natural language processing AI. We will follow a structured approach, including data analysis, data preparation, model definition, training, and inference. Below, we provide an overview of each step.

## Step 1: Data Analysis and Preparation

To build a natural language processing AI, we start by analyzing and preparing our data. This involves:

### 1.1 Data Gathering

We begin by importing John Green's transcripts from Vlogbrothers videos, which serve as our dataset for this project.

### 1.2 Data Preprocessing

Next, we preprocess the data, including tokenization, sentence splitting, and data splitting into training and validation sets.

### 1.3 Data Statistics

We analyze the dataset's statistics, such as the number of lexical types and tokens.

### 1.4 Vocabulary Analysis

We explore the vocabulary to identify frequently occurring words and rare words in the dataset.

### 1.5 Cleaning Rare Words

Some rare words are simplified to improve the model's ability to learn.

### 1.6 Handling Numbers and Endings

We apply rules to handle numbers and word endings, enhancing data consistency.

### 1.7 Revisiting Data Cleaning

We clean the data further, ensuring it's ready for model training.

### 1.8 Replacing Rare Words

We replace rare lexical types with 'unk' to assist the model in handling unknown words.

### 1.9 Final Look at Rare Words

We observe the rarest words and ensure they won't affect model performance significantly.

## Step 2: Model Definitions

In this step, we define the architecture of our natural language processing model. Key components include:

### 2.1 Word-to-Number Conversion

We create a mapping from words to numbers, allowing our model to work with numerical data.

### 2.2 Data Batching

We prepare the data in batches for efficient training.

### 2.3 Model Architecture

We design an encoder-decoder architecture with embedding layers and an LSTM-based RNN for language modeling.

## Step 3: Model Training

This step involves training the NLP model. We train the model over multiple epochs, optimizing it to predict the next word in a sequence. Key training components include:

### 3.1 Training Function

We define the training function to perform backpropagation and optimize model weights.

### 3.2 Evaluation Function

We create an evaluation function to assess the model's performance on validation data.

### 3.3 Training Loop

We iterate over epochs, training the model and monitoring perplexity as a performance metric.

## Step 4: Inference

Finally, we use the trained model to generate text. We implement a sampler to produce creative and diverse sentences. We provide a starting sentence and let the model generate the rest.

## Usage

To utilize this project, you can follow the provided code in the Google Colab notebook named "CCAI08: Lab B - Natural Language Processing v2.0." Feel free to experiment with different prompts, training durations, and hyperparameters to enhance the model's language generation capabilities. You can also clone this repo and run it 

[https://colab.research.google.com/drive/1DjtWqJjuy4mBvOkLqMPIfqjiIINpftJq?usp=sharing](https://colab.research.google.com/drive/1DjtWqJjuy4mBvOkLqMPIfqjiIINpftJq?usp=sharing)

## Conclusion

Natural language processing is an exciting field, and this project showcases the creation of an AI that can generate human-like text. While our model is just the beginning, it demonstrates the potential for AI to generate creative and engaging content.

We encourage you to explore further, train the model with more data, and continue experimenting with NLP techniques. The possibilities are endless!

Enjoy your journey into the world of Natural Language Processing!


# Acknowledgments

We would like to extend our gratitude to [Jabril](https://www.youtube.com/watch?v=kZWum5omEv4), the host of the PBS Crash Course AI series. His educational content has been a valuable source of inspiration and knowledge throughout this project. We highly recommend checking out his videos for a deeper understanding of artificial intelligence and its applications.

# License

This project is licensed under the [MIT License](). You are free to use, modify, and distribute the code and associated documentation for both personal and commercial purposes. Please refer to the [LICENSE]() file for more details on the terms and conditions of this open-source license.
