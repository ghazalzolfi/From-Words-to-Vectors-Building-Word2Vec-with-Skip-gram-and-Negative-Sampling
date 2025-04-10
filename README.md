
# Word2Vec: Skip-Gram with Negative Sampling (NLP)

This repository provides a complete and practical implementation of the Word2Vec algorithm, specifically focusing on the Skip-Gram model combined with negative sampling. Using the Text8 dataset derived from Wikipedia, the project emphasizes understanding, training, and analyzing word embeddings—dense vector representations capturing semantic relationships between words.

### Project Overview:

### 1. Dataset and Preprocessing:
- **Dataset**: Text8, consisting of the first 100 million bytes of plain text from Wikipedia, suitable for demonstrating the capabilities of word embedding techniques.
- **Preprocessing Steps**:
  - Removed stopwords to exclude frequently occurring but semantically irrelevant words.
  - Subsampled frequent words based on Mikolov's heuristic formula to balance common and rare word representation effectively.

### 2. Skip-Gram Model:
- **Objective**: Predict surrounding context words from a given target word to capture semantic and syntactic relationships.
- **Implementation**:
  - Developed the Skip-Gram model using TensorFlow, focusing on efficient training and embedding quality.
  - Generated context-target pairs for training, optimizing the representation of words within vector space.

### 3. Negative Sampling:
- **Purpose**: Improved training efficiency by differentiating true context-target pairs from negative (unrelated) samples.
- **Approach**:
  - Implemented negative sampling to significantly reduce computation during training.
  - Ensured embeddings reflect meaningful semantic distinctions.

### 4. Embedding Evaluation:
- Assessed embeddings qualitatively through semantic similarity and analogy tasks.
- Visualized embeddings using dimensionality reduction techniques such as t-SNE, clearly showcasing learned relationships.

### Key Outcomes:
- Enhanced understanding of the Skip-Gram model and negative sampling.
- Practical experience in preprocessing and preparing large textual datasets.
- Ability to analyze and interpret the semantic quality of word embeddings.

### Libraries and Tools Used:
- Python
- TensorFlow (Modeling and Training)
- NumPy (Numerical Computations)
- Gensim, TensorFlow Datasets (Dataset Handling)
- NLTK (Text Preprocessing)
- Matplotlib, Seaborn (Visualization)
- scikit-learn (Embedding Analysis)

This project provides foundational insights into NLP, focusing on advanced embedding techniques crucial for various downstream natural language applications.
