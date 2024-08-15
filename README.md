# Reddit Impacts Dataset
A Named Entity Recognition Dataset for Analyzing Clinical and Social Effects of Substance Use Derived from Social Media

## Overview

The Reddit-Impacts dataset is a specialized resource developed to facilitate the study of the clinical and social impacts of substance use disorders (SUDs) through Named Entity Recognition (NER). Derived from posts on Reddit, this dataset focuses on discussions related to the nonmedical use of substances, particularly opioids. The goal is to create a tool that aids in the automatic detection of the impacts of substance use, thereby supporting research and the development of public health strategies. 

**This dataset was shared for #SMM4H 2024 Shared Task 4: Extraction of the clinical and social impacts of non-medical substance use from Reddit.**

**Codalab: https://codalab.lisn.upsaclay.fr/competitions/16648**

## Key Features

**Dataset Composition:** The Reddit-Impacts dataset consists of 1,380 posts, with 23% containing annotated entities related to clinical and social impacts of substance use. The dataset includes annotations for 30 entity types, focusing on the most critical but often underrepresented aspects of substance use.

**Annotation Process:** Posts were manually annotated, focusing on identifying clinical impacts (e.g., health consequences) and social impacts (e.g., effects on relationships and communities) reported by Reddit users discussing substance use.

**Machine Learning Models:** Baseline performance for NER tasks was established using several models, including BERT, RoBERTa, DANN (a few-shot learning model), and GPT-3.5 in a one-shot setting.

## Data Collection and Annotation

**· Data Source:** The dataset was curated from 14 opioid-related subreddits, selected for their relevance and high levels of user engagement. Posts were collected using the Python Reddit API Wrapper (PRAW).

**· Annotation:** A comprehensive manual annotation process was applied to identify and classify 30 different entity types, with a particular focus on the clinical and social impacts of substance use.

## Dataset Statistics

Training Data: 843 posts
Validation Data: 259 posts
Testing Data: 278 posts
Entity Types: 30, focusing on both personal information and medication-related entities.

## Baseline Models and Performance

**BERT and RoBERTa:** Transformer-based models fine-tuned on the full training dataset, although they struggled to detect the sparse clinical and social impact entities.

**DANN:** A few-shot learning model that achieved the highest F1-scores among the tested models when trained on the full dataset.

**GPT-3.5:** Evaluated in a one-shot setting, demonstrating higher accuracy in few-shot learning scenarios compared to traditional pre-trained models.

**Llama3:** 

## Usage

To use this dataset:

Download the Dataset: Access the dataset through the google group for #SMM4H 2024 shared task 4.
Model Training: Use the provided scripts to train NER models on the dataset.
Evaluation: Compare the performance of different models using the evaluation metrics provided.
