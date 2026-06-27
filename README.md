# Voice Chatbot with Whisper + OpenRouter + Streamlit

A complete Arabic voice chatbot that converts speech to text using Whisper, generates AI responses via OpenRouter, and outputs audio using gTTS.

## Features

- Speech-to-Text using OpenAI Whisper
- AI-powered responses via OpenRouter (GPT-4o-mini)
- Text-to-Speech using gTTS
- Streamlit web interface
- Export responses as PDF
- Support for both voice and text input

## Technologies

| Component | Technology |
|-----------|-----------|
| STT | OpenAI Whisper |
| LLM | OpenRouter (GPT-4o-mini) |
| TTS | gTTS |
| UI | Streamlit |
| Audio Recording | sounddevice |
| PDF Export | reportlab |

## How It Works

1. User speaks or types a question
2. Whisper converts speech to text (if using voice)
3. OpenRouter generates AI response
4. gTTS converts response to speech
5. Response displayed and played back

## Notes

- API key for OpenRouter is required (replace in code)
- Whisper model downloads on first run (~139MB)

## Author

Fatma Abdullah
