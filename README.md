# Spam-Ham Classification

## Overview

This project is a **Spam-Ham Classification** system that identifies whether a given text message is spam or not. We used **Bag of Words (BoW)** and **TF-IDF (Term Frequency-Inverse Document Frequency)** as feature extraction techniques and trained various machine learning models to classify messages accurately.

## Dataset

The dataset consists of labeled messages where each message is categorized as either **spam** or **ham** (not spam). It was preprocessed and cleaned before being used for model training.

## Approach

The project follows a structured approach:

### 1. Data Preprocessing & Cleaning

- Removed special characters, punctuation, and extra spaces.
- Converted text to lowercase.
- Tokenized words and removed stopwords.
- Applied stemming

### 2. Feature Engineering

- Converted the text into numerical form using **Bag of Words (BoW)** and **TF-IDF**.

### 3. Train-Test Split

- Split the dataset into **training** and **testing** sets to evaluate model performance.

### 4. Model Training


- **Naïve Bayes**


### 5. Model Evaluation

- Evaluated models using **accuracy, precision, recall, and F1-score**.
- Compared the performance of BoW vs. TF-IDF across different models.

## Installation & Usage

### Prerequisites

Ensure you have Python installed along with the following libraries:

```bash
pip install numpy pandas scikit-learn nltk 
```

### Running the Project

1. Clone the repository:

```bash
git clone https://github.com/mridulchdry17/spam-ham-classification.git
cd spam-ham-classification
```

2. Run the Python script:

```bash
python main.py
```

## Results

- TF-IDF performed better than BoW 
- The final model achieved **98.02% accuracy**

## Future Improvements

- Implement deep learning models like LSTMs or Transformers
- Enhance preprocessing with advanced NLP techniques.
- Deploy the model as a web or mobile application.

## License

This project is open-source and available under the MIT License.

---

### 🚀 Happy Coding! 🎯

