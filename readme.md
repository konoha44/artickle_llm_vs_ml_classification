# Optimize Big Data Classification: LLM vs Simple ML — Cost Savings Without Compromising Accuracy

This repository contains the code and resources used for the experiments discussed in the Medium article:  
**[Optimize Big Data Classification: LLM vs Simple ML — Cost Savings Without Compromising Accuracy](https://medium.com/@ivan.snegirev66/optimize-big-data-classification-llm-vs-simple-ml-cost-savings-without-compromising-accuracy-e940db924482)**

## Overview

In this project, we explore and compare three approaches to big data classification using the Amazon Reviews Polarity Dataset:
1. **LLM Only**: Classification with large language models (LLMs).
2. **LLM + Logistic Regression**: Combining LLM-labeled data with Logistic Regression on embeddings.
3. **LLM + Logistic Regression + Active Learning**: Enhancing the process with Active Learning for efficiency and cost reduction.

Our goal is to identify the best approach that balances **cost, speed, and accuracy** for real-world data classification tasks.

## Features
- End-to-end implementation of three classification approaches.
- Cost and time estimation tools based on OpenAI API usage.
- Active Learning framework to prioritize uncertain samples.
- Embedding generation using `SentenceTransformers`.
- Detailed performance analysis and metrics comparison.

## Dataset
The project uses the [Amazon Reviews Polarity Dataset](https://www.kaggle.com/datasets/xiangzhang/amazon-reviews-polarity) for binary sentiment classification.  
Dataset details:
- Prepared by Xiang Zhang and Yassir Acharki (2023).
- Published under the Apache 2.0 license.

You can download it from [Kaggle](https://www.kaggle.com/datasets/xiangzhang/amazon-reviews-polarity) or [Hugging Face](https://huggingface.co/datasets/amazon_reviews).
