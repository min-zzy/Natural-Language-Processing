# NLP Projects: POS Tagging and Pretrained Language Models

This repository contains my implementations for two key assignments in Natural Language Processing (NLP): Part-of-Speech (POS) Tagging using Neural Networks and exploring Pretrained Language Models.

## Project 1: Neural Networks for POS Tagging

This assignment focuses on building and experimenting with neural networks for POS tagging of English tweets. The approach involves using a feed-forward neural network that predicts the POS tag of a word token given its context. 

### Data

- Training, development, and devtest sets of annotated English tweets.
- Word embeddings from the skip-gram model trained on English tweets.

### Model Architecture

- A feed-forward neural network with word embeddings and context window.
- Experimentation with different context window sizes and feature engineering.

## Project 2: Pretrained Language Models

This assignment explores the use of BERT and GPT-2 pretrained language models for downstream tasks.

### Tasks

1. **Classification with BERT [CLS] Features**
   - Implementing a classifier using [CLS] token features from BERT.
   - Experimentation with frozen and fine-tuning BERT features.

2. **Comparison of Pooling Techniques**
   - Investigating the effectiveness of different pooling techniques like first-token, mean pooling, and max pooling.

3. **Fine-tuning BERT**
   - Fine-tuning the last two layers of BERT and comparing results with frozen features.

4. **GPT-2**
   - Implementing GPT-2 as a feature extractor for classification tasks.

## Repository Structure

- `data/`: Contains datasets used in the assignments.
- `results/`: Contains output results and analysis.
