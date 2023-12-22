# Trump Speech Corpus

This repository contains a corpus of Donald Trump's speeches collected from [THE MILLER CENTER](https://millercenter.org/the-presidency/presidential-speeches).

## Corpus Description

The corpus consists of speeches given by Donald Trump, with each speech stored in a separate text file. The files are located in the `Trump_speech_txt_files` directory.

## Data Collection Process

The data was collected by scraping speeches from  [THE MILLER CENTER](https://millercenter.org/the-presidency/presidential-speeches). Each speech is stored in a separate text file with a filename format of `SpeechTitle_date.txt`.

## Preprocessing and Annotations

The Jupyter Notebook (`preprocess_and_annotate.ipynb`) contains the code for preprocessing and annotating the text files. The preprocessing includes tokenization, lemmatization, and parts-of-speech tagging using spaCy. The annotated corpus is then saved as a CSV file (`annotated_corpus.csv`).

## CSV File Structure

The CSV file contains the following columns:

- Filename: The name of the original text file in the data folder.
- Title: The title of the speech.
- Document: The original text exactly as it appears in the text file.
- Noun: Preprocessed text of the document (lemmatized and containing only nouns).
- Tokens: Tokenized text of the document.
- Lemmas: Lemmatized text of the document.
- Parts-of-speech: Parts of speech of all the tokens in the document.

## Usage

To reproduce the process or perform additional analysis:

1. Open the Jupyter Notebook (`preprocess_and_annotate.ipynb`).
2. Run the cells in order to perform preprocessing and annotation.
3. The annotated corpus will be saved as a CSV file (`annotated_corpus.csv`).

Feel free to explore the dataset and use it for your own analysis.

## License

This dataset is provided for educational and research purposes. Please refer to the [data.millercenter](https://data.millercenter.org) for more details.

