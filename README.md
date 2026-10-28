# RNN Sentiment Analyser

A Jupyter Notebook project that classifies IMDB movie reviews as positive or
negative sentiment using text preprocessing, TF-IDF features, and a PyTorch
RNN.

## Files

- `Codes.ipynb` - preprocessing, training, and evaluation workflow
- `IMDB Dataset.csv` - IMDB reviews and sentiment labels

## Setup

Install the required Python packages:

```bash
pip install pandas nltk scikit-learn torch jupyter
```

## Run

1. Keep `Codes.ipynb` and `IMDB Dataset.csv` in the same directory.
2. Start Jupyter:

   ```bash
   jupyter notebook
   ```

3. Open `Codes.ipynb` and run the cells in order. The notebook downloads the
   required NLTK tokenizer and stopword data, trains the RNN, and prints test
   accuracy.
