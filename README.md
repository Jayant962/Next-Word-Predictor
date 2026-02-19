This project implements a Next Word Prediction model using an LSTM network trained on the Shakespeare text corpus.
Given a sequence of words, the model predicts the most probable next word.

Example:
Input: to be or not to
Output: be

Dataset

Shakespeare public domain text

Word-level tokenization

Custom vocabulary built from corpus

Approach

Text cleaning and preprocessing

Word-to-index mapping

Sequence generation with padding

LSTM-based language model (Embedding → LSTM → Linear → Softmax)

Trained for 20 epochs

Tech Stack

Python

PyTorch

NumPy

Use Case

Autocomplete systems, chatbots, and language modeling tasks.
