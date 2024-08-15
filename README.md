# Reddit Impacts Dataset
A Named Entity Recognition Dataset for Analyzing Clinical and Social Effects of Substance Use Derived from Social Media

## Overview

The Reddit-Impacts dataset is a specialized resource developed to facilitate the study of the clinical and social impacts of substance use disorders (SUDs) through Named Entity Recognition (NER). Derived from posts on Reddit, this dataset focuses on discussions related to the nonmedical use of substances, particularly opioids. The goal is to create a tool that aids in the automatic detection of the impacts of substance use, thereby supporting research and the development of public health strategies. This dataset was shared for #SMM4H 2024 Shared Task 4: Extraction of the clinical and social impacts of non-medical substance use from Reddit. 

## Key Features

**Dataset Composition:** The Reddit-Impacts dataset consists of 1,380 posts, with 23% containing annotated entities related to clinical and social impacts of substance use. The dataset includes annotations for 30 entity types, focusing on the most critical but often underrepresented aspects of substance use.

**Annotation Process:** Posts were manually annotated, focusing on identifying clinical impacts (e.g., health consequences) and social impacts (e.g., effects on relationships and communities) reported by Reddit users discussing substance use.

**Machine Learning Models:** Baseline performance for NER tasks was established using several models, including BERT, RoBERTa, DANN (a few-shot learning model), and GPT-3.5 in a one-shot setting.

