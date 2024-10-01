## Project: Abstractive Text Summarization By Fine-Tuning Transformer-Based Model

## Overview

This project involves fine-tuning pre-trained language model from Hugging Face to perform abstractive summarization on Amazon Food Reviews. The transformer-based  model used to generate coherent summaries of food review is PEGASUS.

## Dataset Description

**Title: Amazon Food Review Dataset**
Source:https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews?select=Reviews.csv

Details:
  - Contains roughly 500,000 food reviews from Amazon over a 10-year period
  - Features include: Product IDs, User IDs, plain text reviews, short review summaries, review ratings (1-5), and review helpfulness metrics
  - For this project, the focus is on the "review" and "summary" features
  - 5% of the total data was used for training & fine-tuning the model due to resource constraint.
  - The data was split into training (70%), evaluation (15%), test datasets (15%)

## Pre-trained Model Selection for Model Training & Fine-tuning

**PEGASUS (Pegasus-cnn_dailymail)**
Model URL: (https://huggingface.co/google/pegasus-cnn_dailymail)
Details:
   - Pre-trained model designed for abstractive text summarization
   - Transformer-based encoder-decoder model
   - Fine-tuned on CNN/Daily Mail dataset for text summarization

## Installation and Usage

*Prerequisites*
   - Python 3.7 or later
   - Jupyter Notebook
   - Required Python libraries: pandas, torch, tqdm, transformers, accelerate, rougue score, rouge, numpy, matplotlib, datasets, os


*Usage*
   - Open Jupyter Notebook
   - Download Dataset
   - Install required packages
   - Run the code 
   
