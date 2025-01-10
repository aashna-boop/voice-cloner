# Voice Cloner with Tortoise-TTS  

A Python-based tool for voice cloning using [Tortoise-TTS](https://github.com/jnordberg/tortoise-tts). This tool allows you to create high-quality voice clones from short audio samples and generate text-to-speech (TTS) outputs in the cloned voice.

---

## Features  
- **High-Quality TTS**: Supports multiple quality presets (`ultra_fast`, `fast`, `standard`, `high_quality`).  
- **Voice Cloning**: Clone a voice by uploading 6-10 second WAV audio samples.  
- **Audio Output**: Generate and save speech outputs in WAV format.

---

## Requirements  
- Python 3.x  
- [Tortoise-TTS](https://github.com/jnordberg/tortoise-tts)  
- PyTorch  
- Transformers (version 4.19.0)  
- Additional dependencies in `requirements.txt`.  

---

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/jnordberg/tortoise-tts.git
   cd tortoise-tts
