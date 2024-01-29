# Sentiment Analysis Project

This project aims to compare the performance of three different sentiment analysis models: VADER's model, Roberta model, and a Hugging Face pretrained model. Sentiment analysis is a natural language processing task that involves determining the sentiment polarity of a given text, i.e., whether the text expresses a positive, negative, or neutral sentiment.

## Models Used

1. **VADER's Model**: VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool specifically designed for social media texts. It relies on a list of lexical features and a set of grammatical rules to determine the sentiment of a text.
   
2. **Roberta Model**: Roberta is a transformer-based language model developed by Facebook AI. It is pretrained on a large corpus of text data and fine-tuned for various downstream tasks, including sentiment analysis.
   
3. **Hugging Face Pretrained Model**: Hugging Face provides a wide range of pretrained transformer-based models for natural language processing tasks. We'll be using one of their pretrained models for sentiment analysis.

## Dataset

The sentiment analysis models will be evaluated on the **Sentiment140 dataset**. This dataset consists of 1.6 million tweets labeled with sentiment polarity (positive or negative).

## Implementation

The project is implemented using Python and the following libraries:

- `NLTK`: For VADER sentiment analysis.
- `Transformers` (Hugging Face): For utilizing the Roberta model and the Hugging Face pretrained model.
- `pandas`: For data manipulation.
- `matplotlib` and `seaborn`: For data visualization.

## Usage

1. **Data Preprocessing**: The Sentiment140 dataset is preprocessed to remove noise, tokenize text, and perform any necessary transformations.
   
2. **Model Training and Evaluation**: Each model (VADER, Roberta, Hugging Face pretrained) is trained and evaluated on the Sentiment140 dataset. Evaluation metrics such as accuracy, precision, recall, and F1-score are calculated to assess the performance of each model.

3. **Comparison**: The performance of the three models is compared based on evaluation metrics and visualized using plots.

## Installation


## Results

The results of the sentiment analysis models are presented in tabular and graphical formats. These results include accuracy, precision, recall, and F1-score for each model.

## Conclusion

Based on the evaluation results, insights are drawn regarding the performance of VADER's model, Roberta model, and the Hugging Face pretrained model for sentiment analysis tasks.
