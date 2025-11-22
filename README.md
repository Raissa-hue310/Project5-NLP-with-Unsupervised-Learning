# Project 5: Basic Natural Language Processing with Unsupervised Learning

## Overview

This project introduces fundamental Natural Language Processing (NLP)
techniques using the **20 Newsgroups dataset**.\
Students explore preprocessing, feature extraction, and unsupervised
learning through clustering.

## Contents

This submission includes: - A Jupyter Notebook containing all
preprocessing, feature extraction, clustering, and visualization code. -
A full PDF/Word report summarizing project methodology, results, and
insights. - Supporting files for reproducing the analysis.

## Key Steps Performed

### 1. Text Data Preparation

-   Loading the 20 Newsgroups dataset.
-   Preprocessing the text:
    -   Lowercasing\
    -   Removing punctuation\
    -   Removing stopwords\
    -   Tokenization

### 2. Feature Extraction

-   **Bag of Words (BoW)** for token frequency counts.
-   **TF-IDF** for weighted relevance-based term representation.
-   Optional **GloVe word embeddings** for semantic similarity.

### 3. Unsupervised Learning

-   **K-Means** clustering applied with `k = 20`.
-   Cluster themes analyzed via top TF-IDF terms.
-   Interpretation of topic groups across documents.

### 4. Evaluation

-   **Silhouette Score** to assess cohesion and separation of clusters.
-   Cohesion/separation metrics for cluster quality.

### 5. Visualization

-   **PCA** (2D projection) for overall structure.
-   **t-SNE** for detailed non-linear visualization.

### 6. Prediction

-   Demonstration of predicting cluster assignments for new, unseen
    documents.

## Deliverables Included

-   `Project5_NLP_Report.docx`
-   `Notebook.ipynb` (not generated here but required for submission)
-   All visualizations included within the notebook

## How to Run

1.  Install dependencies:

    ``` bash
    pip install scikit-learn nltk gensim matplotlib seaborn pandas numpy
    ```

2.  Run the notebook cell by cell.

3.  Ensure NLTK stopwords are downloaded:

    ``` python
    import nltk
    nltk.download('stopwords')
    ```

## Author

Prepared by: **Raïssa Matho Mekjele**\
Business Intelligence Analyst (Willis College)
