# Language Detection Model using NLP

An end-to-end Machine Learning and Natural Language Processing (NLP) project that automatically identifies the language of a given text string. This model is trained on text samples spanning 17 different global languages and achieves a strong classification accuracy.

## 🚀 Features
* **Text Vectorization:** Utilizes `CountVectorizer` (Bag of Words approach) to tokenize and convert multilingual text strings into numerical feature matrices.
* **Multinomial Naive Bayes:** Implements a `MultinomialNB` classifier, which is highly efficient for text classification tasks with discrete features.
* **Interactive Inference:** Features a live user-input terminal interface within the Jupyter Notebook to test custom phrases in real time.

## 📊 Dataset & Class Distribution
The model was trained on a multi-language text dataset containing 17 languages. The distribution of data samples per language is structured as follows:

| Language | Sample Count | Language | Sample Count |
| :--- | :--- | :--- | :--- |
| **English** | 1385 | **Arabic** | 536 |
| **French** | 1014 | **Turkish** | 474 |
| **Spanish** | 819 | **German** | 470 |
| **Portuguese** | 739 | **Tamil** | 469 |
| **Italian** | 698 | **Danish** | 428 |
| **Russian** | 692 | **Kannada** | 369 |
| **Swedish** | 676 | **Greek** | 365 |
| **Malayalam** | 594 | **Hindi** | 63 |
| **Dutch** | 546 | | |

*Note: The dataset exhibits a slight class imbalance toward English, while Hindi represents the minority class with 63 samples.*

## 📈 Model Performance
* **Train/Test Split:** 67% Training, 33% Testing (`random_state=42`)
* **Evaluation Metric:** Model Accuracy Score
* **Result:** **95.31%** accuracy on unseen test data.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** `pandas`, `numpy`, `scikit-learn`

## 💻 How to Run Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/language-detection-nlp.git](https://github.com/YOUR_USERNAME/language-detection-nlp.git)
