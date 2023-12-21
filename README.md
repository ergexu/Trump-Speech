# Presidential Speeches Corpus

This repository contains a dataset of speeches delivered by U.S. Presidents, with a focus on Donald Trump and Joe Biden. The original data was obtained from [source_name](https://millercenter.org/the-presidency/presidential-speeches). The initial dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/littleotter/united-states-presidential-speeches?select=corpus.csv), but it only includes speeches up to Sept. 25th, 2019. To include speeches from Sept. 25th, 2019, until now, additional data was collected by web scraping and integrated into a new file, `all_presidential_speeches.csv`.

## Corpus Description

The dataset comprises speeches from Donald Trump and Joe Biden during their respective presidential terms. The goal is to analyze the language used by these two presidents in their speeches.

## Target Audience and Intended Use

The target audience for this corpus includes researchers, linguists, and anyone interested in studying the language patterns of U.S. Presidents. The intended use is for natural language processing (NLP) and linguistic analysis.

## Text Selection Criteria

The speeches of Donald Trump and Joe Biden were selected based on their respective presidencies.

## Data Collection Process

The original data was obtained from [United States Presidential Speeches](https://www.kaggle.com/datasets/littleotter/united-states-presidential-speeches?select=corpus.csv), and additional speeches from Sept. 25th, 2019, until now, were collected by web scraping.

## Cleaning and Preprocessing

The Jupyter Notebook (`preprocessing_and_analysis.ipynb`) includes code for text cleaning, tokenization, lemmatization, and part-of-speech tagging using the SpaCy library.

## Annotations

The processed data includes cleaned text and lemmatized nouns. The annotations aim to facilitate linguistic analysis and NLP tasks.

## File Formats

- Original data: CSV format (`all_presidential_speeches.csv`).
- Processed data: CSV format (`processed_trump_biden_transcripts.csv`).

## Quality Checks

No specific quality checks have been performed, but the data cleaning and preprocessing steps were designed to enhance the quality of the text.

