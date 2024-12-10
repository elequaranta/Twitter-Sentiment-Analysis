# Political Tweets Sentiment Analysis

## Context: 
**Class**: Data Mining and Text Mining, University of Illinois at Chicago (Fall 2023)
*1st year of Master's Degree in Computer Science coursework*

## Abstract: 
The aim of our project was the design of a pipeline for the sentiment classification of tweets on the two opponents of the 2012 United States presidential elections. We experimented with pretrained models to identify the best performing one on this specific task, and then used fine-tuning techniques to better refine its performance using the training data made available to us. We also tried to incorporate some Machine Learning algorithms to the pipeline, trying to correct possible biases of the sentiment classification model by predicting the final label from the different probabilities score for each class output by the fine-tuned model. However, this technique didn’t improve the results on the evaluation data, which stayed nearly the same.
For more details, please refer to the *Twitter Sentiment Analysis.pdf* file.

## Files: 
* **Finetuning notebooks**:
  - BERTweet_finetuned_final.ipynb: BERTweet fine-tuning (double model for two classes)
  - BERTweet_finetuned_unique.ipynb: BERTweet fine-tuning (single model for both classes)

* **Baseline models**:
  - BERTweet_baseline.ipynb: BERTweet model predictions (no fine-tuning)
  - RoBERTa_baseline.ipynb: RoBERTa model predictions (no fine-tuning)
  - VADER_baseline.ipynb: VADER model predictions (no fine-tuning)

* data_clean.ipynb: data preprocessing and cleaning
* Twitter Sentiment Analysis.pdf: project report with detailed explanations and reasoning
* results.ipynb: model loading and results predictions
* data directory: contains raw, clean versions of data and train/test splits used
