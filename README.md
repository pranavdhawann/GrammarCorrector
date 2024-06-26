# GrammarCorrector
This project provides a script to correct grammatical errors in English sentences using a pre-trained transformer model. It uses a deep learning model to identify and correct grammatical errors in text.

## Table of Contents
  - [Table of Contents](#table-of-contents)
  - [About Transformers](#about-transformers)
  - [Usage](#usage)
  - [Method](#method)
  - [Requirements](#requirements)
  - [Example Output](#example-output)
  - [Future Work](#future-work)
  - [Contributing](#contributing)

## About Transformers
The Transformers library by Hugging Face revolutionizes natural language processing (NLP) with an easy-to-use interface for state-of-the-art models like BERT, GPT, and T5. It supports both PyTorch and TensorFlow, ensuring versatility and accessibility. Key features include a vast model hub, robust tokenization, and straightforward fine-tuning capabilities. The library is backed by comprehensive documentation and a vibrant community. Practical applications span sentiment analysis, text summarization, machine translation, question answering, and text generation. By democratizing access to advanced NLP tools, the Transformers library enables rapid development and deployment of sophisticated language processing applications.

## Usage
To use the grammar error corrector script, follow these steps:

1. Clone the repository:
   ```
    git clone https://github.com/pranavdhawann/GrammarCorrector.git
    cd GrammarCorrector
   ```
2. Create a virtual environment:
   ```
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```
3. Install dependencies:
   ```
    pip install -r requirements.txt
   ```
4. Run the Script:
   ```
    python grammarcheck.py
   ```

## Method
1. Tokenization: The input sentence is tokenized into a format suitable for the model.
2. Model Inference: The tokenized sentence is passed through the pre-trained model to generate a corrected sentence.
3. Decoding: The output from the model is decoded back into a human-readable format.

## Requirements
1. Python 3.8+
2. Torch
3. Transformers

## Example Output
1. Original: She don't like to play basketball.
   Corrected: She doesn't like to play basketball.

2. Original: I goes to the market every Sunday.
   Corrected: I go to the market every Sunday.

3. Original: He has ate dinner already.
   Corrected: He has eaten dinner already.
   
## Future Work
- [ ] Add Support for Different Document Types such as Word (.docx), and others.
- [ ] Add support for Multiple Languages: Extend the model to support grammar correction in other languages.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.
