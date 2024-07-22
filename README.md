# Word2Vec Learning Project

## Overview

This project explores the fundamentals of Word2Vec, a popular technique in Natural Language Processing (NLP) for creating word embeddings. The project contains three main scripts that illustrate different approaches to implementing Word2Vec:

1. **`using_keras.ipynb`**: Implements Word2Vec using high-level libraries (Keras).
2. **`cooccurence.ipynb`**: Creates embeddings using the traditional co-occurrence matrix method.
3. **`word2vec.ipynb`**: Implements Word2Vec from scratch, employing the skip-gram technique to generate center and context pairs.

## File Descriptions

### `using_keras.py`

- **Purpose**: Demonstrates how to implement Word2Vec using Keras and other high-level libraries.
- **Key Libraries**: Keras, TensorFlow.
- **Overview**: This script leverages existing libraries to streamline the process of training Word2Vec models. It abstracts away the complexities of the underlying algorithms, making it easier to experiment with different configurations and parameters.

### `cooccurence.py`

- **Purpose**: Uses the traditional co-occurrence matrix approach to create word embeddings.
- **Key Concepts**: Co-occurrence matrix, Singular Value Decomposition (SVD).
- **Overview**: This script builds word embeddings by calculating word co-occurrence frequencies and applying matrix factorization techniques. It provides a foundational understanding of how embeddings can be derived from word co-occurrence data.

### `word2vec.py`

- **Purpose**: Implements Word2Vec from scratch using the skip-gram technique.
- **Key Concepts**: Skip-gram model, center and context pairs, neural network training.
- **Overview**: This script manually constructs and trains a Word2Vec model from scratch, focusing on the skip-gram approach. It creates center and context word pairs to learn embeddings, providing insights into the inner workings of the Word2Vec algorithm.


