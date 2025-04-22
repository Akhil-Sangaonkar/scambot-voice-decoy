# 🛡️ ScamCallBot: The Polite Indian AI That Wastes Scam Callers' Time


## 🛠️ Requirements

Ensure your environment meets the following requirements:

- **Python Version**: `3.11.12`

- **Libraries**:

  | Library   | Version  |
  |-----------|----------|
  | PyAudio   | 0.2.14   |
  | Whisper   | 20240930 |
  | Coqui TTS | 0.22.0   |

These versions are confirmed to work seamlessly together. Ensure all dependencies are installed as specified to avoid compatibility issues.

- **Ollama**: Install the Ollama Python library by running

  ```bash
  pip install ollama

## 🤖 LiveChatBot Class: A Voice-Enabled Time-Wasting Conversational Agent

The `LiveChatBot` class is designed to interact with scam callers, keeping them engaged by simulating a slightly confused but overly polite persona. It leverages speech recognition, language modeling, and text-to-speech synthesis to create an interactive voice-based agent.

### Key Components:
1. **Whisper Model** (Speech-to-Text)
   - The `LiveChatBot` uses OpenAI's `Whisper` model for transcribing audio input into text. This allows it to understand the scam caller's speech.

2. **Llama Model** (Language Model)
   - A language model (Gemma 3:1b) is used to generate a nonsensical, slightly confused response to keep the scam caller engaged.

3. **TTS Model** (Text-to-Speech)
   - The bot uses Coqui's `TTS` for converting text back into speech to respond to the scam caller in a natural-sounding voice.





