# Sarvam-2b Multilingual Indian Chatbot

This project implements a multilingual chatbot using the Sarvam-2b language model, capable of conversing in multiple Indian languages as well as English.

## Overview

The Sarvam-2b model is a powerful language model pre-trained on 4 trillion tokens, with a focus on 10 Indic languages and English. This chatbot leverages the model's capabilities to provide a user-friendly interface for multilingual conversations.

## Features

- Supports 11 languages: English, Bengali, Gujarati, Hindi, Kannada, Malayalam, Marathi, Oriya, Punjabi, Tamil, and Telugu
- Uses the Hugging Face Transformers library for text generation
- Implements a Gradio interface for easy interaction
- Includes relevance checking to ensure appropriate responses

## Requirements

- Python 3.x
- gradio
- transformers
- torch

## Installation

1. Clone this repository or download the Jupyter notebook.
2. Install the required packages:

```
pip install gradio transformers torch
```

## Usage

1. Run the Jupyter notebook or execute the Python script.
2. The Gradio interface will launch, providing a URL for accessing the chatbot.
3. Select your desired language from the dropdown menu.
4. Start chatting with the bot in the selected language!

## How it Works

1. The chatbot uses the Sarvam-2b model to generate responses.
2. It maintains conversation history to provide context for each interaction.
3. Multiple responses are generated for each input, and the most relevant one is selected.
4. If no relevant response is found, the user is prompted to rephrase their message.

## Limitations

- The quality of responses depends on the underlying Sarvam-2b model's capabilities.
- The chatbot may occasionally generate irrelevant or inconsistent responses.

## Future Improvements

- Fine-tune the model on more specific conversational data for each language.
- Implement more sophisticated relevance checking and response selection algorithms.
- Add support for more Indian languages and dialects.

## Acknowledgments

This project uses the Sarvam-2b model developed by Sarvam AI. Special thanks to the Hugging Face and Gradio teams for their excellent libraries.

