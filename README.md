# Sentiment Analysis Using SVM and Naïve Bayes

This project implements sentiment analysis on IMDb movie reviews using two machine learning models:
- Support Vector Machine (SVM)
- Naïve Bayes

The goal is to classify reviews as positive or negative using natural language processing (NLP) techniques.

---

## Project Structure
- `data/` — Contains the dataset (IMDb reviews ZIP file)
- `notebooks/` — Jupyter notebook for training and testing
- `reports/` — Project report and reference paper
- `requirements.txt` — Python dependencies

---

## Models and Methods
- Linear SVM
- Multinomial Naïve Bayes
- Preprocessing:
  - Tokenization
  - Stopword removal
  - Porter stemming
  - Bag-of-words feature extraction

---

## Results
- SVM outperformed Naïve Bayes across genres.
- Example accuracy:
  - SVM (Drama): 87.5%
  - Naïve Bayes (Drama): 80%

---

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Aryanadit/sentiment-analysis-svm-naive-bayes.git
    cd sentiment-analysis-svm-naive-bayes
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch the notebook:
    ```bash
    jupyter notebook notebooks/sentiment-analysis.ipynb
    ```

---

## Requirements
- Python 3.x
- scikit-learn
- pandas
- numpy
- nltk
- tqdm

---

## License
This project is licensed under the MIT License.
