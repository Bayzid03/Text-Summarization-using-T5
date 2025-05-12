# Text Summarization Project

This project implements text summarization using the T5 (Text-to-Text Transfer Transformer) model from the Hugging Face Transformers library. It provides a simple way to generate concise summaries from longer text inputs.

## Features

- Uses the pre-trained T5-small model for text summarization
- Simple and easy-to-use interface
- Configurable summary length and generation parameters
- CPU-based inference

## Requirements

- Python 3.x
- PyTorch
- Transformers library

## Installation

1. Clone this repository
2. Install the required packages:
```bash
pip install transformers torch
```

## Model Parameters

- `max_length`: Maximum length of the generated summary (default: 50)
- `num_beams`: Number of beams for beam search (default: 4)
- `length_penalty`: Length penalty for beam search (default: 2.0)
- `early_stopping`: Whether to stop the beam search when at least num_beams sentences are finished per batch (default: True)

## License

This project is open source and available under the MIT License. 