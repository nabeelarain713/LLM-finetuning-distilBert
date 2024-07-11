# DistilBERT Fine-Tuned on IMDB Movies Dataset with PEFT LoRA

This repository contains the code and resources for fine-tuning a DistilBERT model on the IMDB movies dataset using PEFT (Parameter-Efficient Fine-Tuning) with LoRA (Low-Rank Adaptation). DistilBERT is a smaller, faster, and lighter version of BERT, and PEFT LoRA further optimizes the fine-tuning process to require fewer computational resources while maintaining high performance.

## Overview

The IMDB movies dataset is a popular dataset for sentiment analysis, containing movie reviews with corresponding sentiment labels. This project aims to fine-tune the DistilBERT model using PEFT LoRA to accurately classify the sentiment of movie reviews as positive or negative.

## Features

- **Fine-tuning with PEFT LoRA**: Step-by-step process for fine-tuning DistilBERT on the IMDB dataset using parameter-efficient fine-tuning methods.
- **Data Preprocessing**: Techniques for cleaning and preparing the IMDB dataset for training.
- **Model Training**: Scripts for training the model, including hyperparameter tuning.
- **Evaluation**: Methods for evaluating the model's performance, including accuracy and loss metrics.
- **Inference**: Example code for using the fine-tuned model to predict the sentiment of new movie reviews.

## Results

The fine-tuned DistilBERT model achieves high accuracy in classifying the sentiment of movie reviews. Detailed evaluation metrics and model performance are documented in the repository.

## Acknowledgments

- Hugging Face for providing the Transformers library.
- The IMDB dataset for providing the data used in this project.
