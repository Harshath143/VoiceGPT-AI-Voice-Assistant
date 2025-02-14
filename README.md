# VoiceGPT-AI-Voice-Assistant


VoiceGPT is a voice-activated AI chatbot that listens to user input, processes it with NLP, and responds with text-to-speech output. It utilizes speech recognition, a Transformer-based chatbot model, and speech synthesis.

## Features
- **Speech Recognition**: Converts spoken language into text using Google Speech Recognition.
- **AI Chatbot**: Processes user input using Facebook's Blenderbot model.
- **Text-to-Speech (TTS)**: Converts AI-generated responses into spoken output using `pyttsx3`.
- **Continuous Listening**: Listens for user commands and engages in conversation.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/VoiceGPT.git
cd VoiceGPT
pip install -r Requirements.txt
```
## Dependencies
Refer to `requirements.txt` for required libraries.


Download the Transformer model:
```python
from transformers import BlenderbotForConditionalGeneration, BlenderbotTokenizer
model_name = "facebook/blenderbot-400M-distill"
tokenizer = BlenderbotTokenizer.from_pretrained(model_name)
model = BlenderbotForConditionalGeneration.from_pretrained(model_name)
```
Download Link
https://huggingface.co/facebook/blenderbot-400M-distill/tree/main

## License
MIT License
