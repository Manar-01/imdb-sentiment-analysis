# IMDB Sentiment Analysis

This project focuses on **Text Classification** by performing **Sentiment Analysis** on IMDB movie reviews. Sentiment Analysis involves extracting opinions and sentiments from textual data. Using Scikit-Learn, this project demonstrates the use of regression models to predict whether a movie review is positive or negative.

---

## Features

- **Dataset**: IMDB movie review dataset with 50,000 labeled reviews (50% positive, 50% negative).
- **Preprocessing**:
  - Tokenization and vectorization of text data.
  - Transformation of text into numerical features using Bag of Words.
- **Model**:
  - Use regression models ( Logistic Regression) from Scikit-Learn.
- **Evaluation**:
  - Assess the model using metrics like accuracy, precision, recall, and F1-score.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
```

### Install Dependencies
Ensure you have Python 3.7+ and install the required libraries:
```bash
pip install -r requirements.txt
```
## How to Run
1. Open the notebook:
``` bash
jupyter notebook qa_rag_climate_fever.ipynb
```
or use google colab 

2. Follow the steps in the notebook to:
- Load and preprocess the dataset.
- Train a regression model for sentiment prediction.
- Evaluate the model's performance on the test dataset.
- Visualize results.

## Dataset
The IMDB dataset consists of 50,000 movie reviews, evenly split between positive and negative sentiments. The dataset is available through Scikit-Learn's datasets module or can be downloaded from external sources. It is divided into:

- Training set: 25,000 reviews.
- Test set: 25,000 reviews.
  
## Dependencies
- numpy
- pandas
- matplotlib
- scikit-learn
- nltk
- tensorflow
  
Install them using the requirements.txt file.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgments
- The IMDB dataset is a standard benchmark dataset for sentiment analysis tasks.
- This project uses Scikit-Learn for machine learning and text processing.
