# Sentiment Analysis on Yelp Reviews

This project focuses on sentiment analysis of Yelp reviews using machine learning techniques, specifically leveraging a Transformer model with PyTorch and Hugging Face's BERT. The goal is to classify Yelp reviews into positive, negative, or neutral sentiments. The project was completed as a part of CSCE 633: Machine Learning at Texas A&M University.

## Overview

Sentiment analysis plays a crucial role in understanding user opinions and feedback, with applications ranging from business insights to product development. In this project, we implement sentiment analysis on Yelp reviews, aiming to classify the sentiment expressed in each review. We leverage machine learning techniques, including a Transformer model with PyTorch and Hugging Face's BERT, to achieve accurate sentiment classification.

## Key Components

- **Data Preprocessing**: Punctuation and stopwords were removed, and text was standardized to lowercase. Star ratings were categorized into positive, negative, and neutral sentiments to facilitate classification.
  
- **Model Training**: We employed transfer learning with a pre-trained BERT model and fine-tuned it on the Yelp reviews dataset. The model was trained to classify reviews into positive, negative, or neutral sentiments.

- **Evaluation**: The trained model was evaluated using a test dataset, achieving a test accuracy of 87.60%.

## Project Structure

- **data/**: Contains the Yelp reviews dataset.
  
- **notebooks/**: Jupyter notebooks used for data exploration, model training, and evaluation.

- **requirements.txt**: Lists the dependencies required to run the project. Refer to this file for installation instructions.

## Dependencies

Refer to the requirements.txt file for dependencies.

## Usage

1. Clone the repository: `git clone https://github.com/your_username/sentiment-analysis-yelp.git`
  
2. Install dependencies: `pip install -r requirements.txt`

3. Run the sentiment analysis model: `Open the Jupyter Notebook Sentiment_Analysis.ipynb and follow the instructions inside for running the sentiment analysis model.
`
## Acknowledgments

Special thanks to Professor [Dr. Bobak Mortazavi](https://engineering.tamu.edu/cse/profiles/mortazavi-bobak.html) for guidance and support throughout the course and project.
