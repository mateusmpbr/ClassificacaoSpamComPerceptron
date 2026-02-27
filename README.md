# Perceptron Spam Classifier

This project implements a simple Perceptron-based binary classifier to detect spam e-mails. It is a Python implementation created as part of an Artificial Intelligence course during a Bachelor's degree in Information Systems at UFOP.

**Project Overview:**

- **Goal:** Train a Perceptron to classify e-mail messages as "spam" or "not spam" using basic text features.
- **Approach:** A single-layer Perceptron (linear classifier) trained with a labeled dataset. Preprocessing includes simple tokenization and feature extraction to convert text into numeric vectors.

**Features:**

- Minimal, easy-to-understand Perceptron implementation.
- Example preprocessing of raw email text into features.
- Training loop with weight updates using the Perceptron learning rule.

**Requirements:**

- Python 3.7+ (recommended)
- Standard library only (no external dependencies required). If you add optional helpers, list them here.

**Installation:**

1. Clone the repository:

   git clone https://example.com/your-repo.git
   cd ClassificacaoSpamComPerceptron

2. (Optional) Create and activate a virtual environment:

   python3 -m venv venv
   source venv/bin/activate

3. Run the example script or use the `perceptron.py` module directly.

**Usage:**

- The main script is `perceptron.py`. It contains the Perceptron implementation and a basic example of training and evaluating the model.
- To run the script:

  python3 perceptron.py

Customize the training data and hyperparameters inside the script or extend it to accept command-line arguments.

**Training & Evaluation:**

- Prepare a labeled dataset of e-mails with two classes: spam (1) and not-spam (0).
- Convert each e-mail into a numeric feature vector (e.g., token counts or presence/absence of keywords).
- Train the Perceptron with the training set, then evaluate accuracy on a held-out test set.

**Project Structure:**

- `perceptron.py` — Perceptron implementation and example usage.
- `README.md` — This file.

**Extending this project:**

- Improve preprocessing (stopwords, stemming, TF-IDF).
- Add command-line arguments for dataset paths and hyperparameters.
- Add automatic train/test split and evaluation metrics (precision, recall, F1).

**License:**

- See the `LICENSE` file for license details.

**Author:**

- Project created for an AI course at UFOP.
