# Analyzing the Emotional Tone of Donald Trump’s Tweets Before and After the 2016 U.S. Presidential Election

## Description

This project explores the evolution of Donald Trump’s emotional tone on Twitter across a critical political divide: before and after his 2016 presidential election. By applying deep learning techniques to over a decade of tweet data, it uncovers how sentiment and emotional expression in Trump’s communication shifted once he assumed office.

Leveraging state-of-the-art transformer models, this study aims not only to classify tweets by sentiment but to provide fine-grained emotion categorization and interpret underlying rhetorical shifts over time.

## Highlights

- **Dataset**: 56,000+ Trump tweets from 2009 to 2021, preprocessed and cleaned for analysis.
- **Models Used**: RoBERTa-based neural networks fine-tuned for:
  - Coarse sentiment classification (positive, negative, neutral)
  - Fine-grained emotion recognition (27 emotion categories)
- **Comparative Evaluation**: Models trained with and without class balancing (undersampling).
- **Key Insight**: Statistically significant shift in emotional tone post-election, with an increase in neutral or subtly negative expressions.
- **Interpretability**: Utilizes SHAP values to expose misclassifications influenced by sarcasm and implicit sentiment.

## Research Question

> *Is there a significant difference in the emotional tone of Donald Trump’s tweets before and after becoming president?*

The project uses statistical tests (e.g., chi-squared) and machine learning evaluations to answer this question, revealing that the post-election communication strategy indeed shifted.

## Methodology

1. **Preprocessing**: Cleaning text, removing links, expanding contractions, and lowercasing.
2. **Tokenization**: RoBERTa tokenizer prepares the input for model inference.
3. **Model Training**:
   - Sentiment-level classification (3 classes)
   - Emotion-level classification (28 labels with/without neutral)
4. **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score.
5. **Exploratory Data Analysis**: Time-based tweet activity, virality trends, and emotional distributions.
6. **Statistical Testing**: Chi-squared test confirms sentiment distribution changes are significant.

## Usage

This project can serve as:
- A case study in applying transformer models to political discourse.
- A foundation for emotion and sarcasm detection in social media.
- A reproducible sentiment analysis pipeline using real-world data.

