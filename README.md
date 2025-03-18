
# STT-Whisper Speech-to-Text Transcription

## Overview
This project uses OpenAI's Whisper model for speech-to-text (STT) transcription of MP3 audio files. It supports both OpenAI's Whisper API and Hugging Face's implementation for local transcription.

## Features
- Transcribes MP3 audio files into text
- Uses OpenAI's Whisper API for best accuracy
- Falls back to Hugging Face's Whisper model if API is unavailable
- Handles long audio files automatically
- Works in Jupyter Notebook, Google Colab, and local terminals

## Installation
To install the required dependencies, run:
```bash
pip install openai pydub transformers torchaudio
