# IndoBERT Thesis Classification

Semantic-Based Thesis Title Classification Using IndoBERT Embeddings: A Comparative Study of K-Nearest Neighbor and Decision Tree Algorithms.

---

## Overview

This repository contains the implementation of a semantic-based thesis title classification system using IndoBERT embeddings. The research aims to compare the performance of K-Nearest Neighbor (K-NN) and Decision Tree algorithms in classifying undergraduate thesis titles into predefined academic concentration fields.

The proposed approach utilizes IndoBERT to generate contextual text representations, enabling the classification models to capture semantic information beyond traditional lexical features.

---

## Research Objectives

The objectives of this study are:

* To implement semantic text representation using IndoBERT embeddings.
* To develop thesis title classification models using K-Nearest Neighbor (K-NN) and Decision Tree algorithms.
* To compare the classification performance of both algorithms.
* To evaluate model performance using Accuracy, Precision, Recall, and F1-Score metrics.

---

## Classification Categories

The thesis titles are classified into the following concentration fields:

* RPL (Rekayasa Perangkat Lunak / Software Engineering)
* TKJ (Teknik Komputer dan Jaringan / Computer Network Engineering)
* Multimedia

---

## Methodology

### 1. Data Collection

The dataset consists of undergraduate thesis titles collected from previous academic works and categorized according to their respective concentration fields.

### 2. Text Preprocessing

Several preprocessing techniques are applied to improve data quality, including:

* Case Folding
* Text Cleaning
* Normalization
* Stopword Removal
* Stemming

### 3. Semantic Feature Extraction

IndoBERT is used to transform thesis titles into dense semantic embeddings that capture contextual meaning.

### 4. Classification Models

The following machine learning algorithms are evaluated:

* K-Nearest Neighbor (K-NN)
* Decision Tree

### 5. Performance Evaluation

Model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Technologies Used

* Python
* Google Colab
* IndoBERT
* Transformers (Hugging Face)
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Sastrawi

---

## Repository Structure

```text
indobert-thesis-classification
│
├── IndoBERT_Thesis_Classification.ipynb
├── README.md
├── requirements.txt
├── LICENSE
│
└── results/
    ├── confusion_matrix_knn.png
    ├── confusion_matrix_dt.png
    └── model_comparison.png
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Afelino-Mclearen/indobert-thesis-classification.git
cd indobert-thesis-classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset.
3. Run all cells sequentially.
4. Train and evaluate the classification models.
5. Review the generated evaluation metrics and confusion matrices.

---

## Results

The study compares the performance of K-NN and Decision Tree models using IndoBERT embeddings. Performance evaluation is conducted using Accuracy, Precision, Recall, and F1-Score metrics, supported by confusion matrix analysis.

Example results and visualizations can be found in the `results/` directory.

---

## Dataset Availability

The dataset used in this study may not be publicly distributed due to academic and institutional considerations. Researchers interested in reproducing the study may use a similar thesis title dataset categorized into the specified concentration fields.

---

## Author

**Afelino Mclearen**

Bachelor Thesis Project
Department of Informatics Engineering

Research Area:

* Natural Language Processing (NLP)
* Machine Learning
* Text Classification
* Semantic Representation Learning

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.
