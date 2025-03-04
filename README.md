Markov Chain Text Generator

A Python-based text generator that uses a Markov chain model to create realistic text sequences. The model learns word transitions from input text and generates coherent sequences based on a given seed phrase.

Features

Preprocesses input text for efficient tokenization

Builds a Markov chain model with adjustable order

Generates text with optional randomness

Supports intelligent seed matching for better coherence

Installation

Ensure you have Python installed, then clone the repository:

git clone https://github.com/yourusername/markov-text-generator.git
cd markov-text-generator

Usage

Run the script and provide a seed phrase when prompted:

python markov_generator.py

Enter a starting word or phrase: Alice was
Generated Text:
Alice was beginning to get very tired of sitting by her sister on the bank.


Dependencies

Python 3.x

random

re

collections

License

This project is licensed under the MIT License.


