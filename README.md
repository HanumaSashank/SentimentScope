# SentimentScope: Advanced Sentiment Analysis Web Platform
## Overview
SentimentScope is an AI-driven web platform designed for precise sentiment and emotion analysis across diverse text sources, including tweets, product reviews, and general user-generated content. By utilizing fine-tuned NLP models tailored to specific text types, the platform achieves higher accuracy with domain-specific sentiment insights and reduce edge-case errors for real-time sentiment analysis of diverse text sources and provides actionable insights for businesses, marketers, and researchers.
## Key Features
 - Multi-Model Integration: RoBERTa and DistilBERT models fine-tuned for different text domains (tweets, user-generated text, and product reviews).
 - Custom Preprocessing: Advanced cleaning, tokenization, and preparation tailored for each dataset.
 - Interactive Web Interface: Input text and receive sentiment predictions from purpose-trained models.
 - High Accuracy: Achieves up to 92% accuracy for emotion detection and 88% for sentiment classification.
 - Real-Time Applications: Ideal for customer feedback analysis, brand perception, and public opinion studies.
## System Components
 - Models and Datasets
  1. Twitter Sentiment Analysis:
     - Model: RoBERTa.
     - Dataset: Kaggle's Twitter sentiment dataset with 79,089 tweets.
     - Performance: 88% accuracy; F1-scores above 0.89.
  2. Amazon Product Reviews:
     - Model: DistilBERT.
     - Dataset: Amazon US Mobile Electronics Reviews (TensorFlow Datasets).
     - Performance: 86.97% accuracy, 83.69% recall.
  3. Text Emotion Detection:
     - Model: DistilBERT.
     - Dataset: Hugging Face emotion dataset with 20,000 tagged entries.
     - Performance: Accuracy improved from ~89% to ~92%.
 - Web Platform
   - Integrates all three models, displaying predictions from the model with the highest confidence score.
   - User-friendly interface for seamless interaction and result visualization.
## Methodology
 - Data Collection and Preprocessing
   - Sources: Twitter, Amazon, and Hugging Face datasets.
   - Processes: Removal of noise, tokenization, handling special characters, and transforming categorical targets into numerical formats.
 - Training and Model Fine-Tuning
   - Trained the models on their specific datasets, Hyperparameter tuning and validation for optimal performance.
   - Each model fine-tuned specifically for its dataset, ensuring domain-specific accuracy.
- Evaluation Metrics
  - Quantitative Measures: Precision, recall, F1 score, and accuracy.
  - Human Evaluation: 45 real-time examples tested, achieving 97.8% accuracy in expected outputs.
## Results
 - Emotion Detection: Validation loss reduced significantly, achieving high accuracy and balanced precision-recall metrics.
 - Twitter Sentiment Analysis: F1-scores above 0.89 across all sentiment classes.
 - Product Reviews: Improved consistency with robust accuracy for multi-class sentiment classification.
 - 45 real-time examples tested, achieving 97.8% accuracy in expected outputs.



















































SentimentScope is an advanced AI-driven web platform designed for precise sentiment and emotion analysis across diverse text sources, including tweets, product reviews, and
general user texts. The platform offers an interactive user experience, allowing users to input text and receive sentiment predictions from three purpose-trained models. 
Each model is dedicated to a specific type of user input and is accessible through dedicated buttons, enabling seamless model experimentation. By leveraging specialized models trained on
specific types of text data, SentimentScope achieves higher accuracy in sentiment analysis compared to generic models. The platform is ideal for businesses, marketers, and researchers
seeking to understand customer sentiment, brand perception, and public opinion trends. It provides valuable insights that can be used to inform marketing strategies, product development, and social science research.
