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
## Setup and Usage
 - Prerequisites
   - Python 3.7+
   - Required libraries: ```transformers, pandas, numpy, flask, scikit-learn, torch```
 - Running the Project
   1. Clone the repository: ```git clone https://github.com/YourUsername/SentimentScope.git```
   2. Install dependencies: pip install all the above mentioned libraries required for this project
   3. Start the web application: ```python WebApp.py```
   4. Access the application at ```http://localhost:3000```\
 **Web Application Interface**
![image](https://github.com/user-attachments/assets/32f4ddcb-6d13-4c76-a730-bcc57c7f8a91)
### For more details refer to the full [project report](https://github.com/user-attachments/files/18528659/Team_04_Milestone_05.2.pdf) and [project presentation](https://github.com/user-attachments/files/18528679/SentimentScope.pptx)



















































