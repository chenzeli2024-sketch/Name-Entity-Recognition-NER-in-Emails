# Named Entity Recognition in Enron Meeting Emails

This project focuses on identifying human names in email text using three models:
- Latent Dirichlet Allocation (LDA)
- Random Forest
- Conditional Random Fields (CRF)

The dataset used is the [Enron Meeting Dataset](http://www.cs.cmu.edu/~enron/), which contains meeting-related emails with labeled names.

## Methods
- **Data Preprocessing**: Cleaning email bodies, removing stopwords, and formatting text for modeling.
- **LDA**: Unsupervised topic modeling to separate name tokens from other words.
- **Random Forest**: Supervised classification using word-level features (case, length).
- **CRF**: Sequence labeling to capture contextual patterns.

## Results
- Random Forest: 57.3% accuracy on name prediction
- LDA: Identified name-related topics but with false positives
- CRF: Precision 81.1%, Recall 74.4%

## Report
The full project report, including methodology and results, is available here:
[221final.pdf](221final.pdf)

## Note
The original source code is not available, but the report contains the complete workflow and results.
