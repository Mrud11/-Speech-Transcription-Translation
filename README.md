# Speech-Transcription-Translation
🎙️ Whisper Speech Transcription &amp; Translation - This project uses OpenAI's [Whisper](https://github.com/openai/whisper) model to transcribe spoken English from `.wav` audio files and translate the transcription into Hindi and Marathi

# 🎙️ Whisper Speech Transcription & Translation App

This project uses OpenAI's [Whisper](https://github.com/openai/whisper) model to transcribe spoken English from `.wav` audio files and translate the transcription into **Hindi** and **Marathi** — all within a notebook.

# 🎤 Speech-to-Text Transcription using Whisper

This project demonstrates an end-to-end pipeline for converting audio recordings (.wav files) into human-readable text using OpenAI's Whisper model and Hugging Face Transformers.

## 📌 Features
- Transcribes `.wav` audio to text
- Supports English and other languages
- Reduces background noise using `noisereduce`
- Uses `librosa` and `torchaudio` for audio preprocessing
- Google Colab and Google Drive integration

## 🛠 Tech Stack
- Python
- OpenAI Whisper
- Hugging Face Transformers
- Torchaudio, Librosa
- Google Colab, Google Drive

## 🔧 Installation
```bash
pip install openai-whisper transformers torchaudio librosa noisereduce

🚀 How to Run
Upload your .wav audio files to Google Drive

Run the notebook in Google Colab

View the transcribed text output

Speech-to-Text-Transcription/
│
├── notebook/
│ └── Speech_to_Text_for_transcription_aug1.ipynb
├── audio_samples/ # (Optional folder with sample audios)
├── README.md
├── requirements.txt
└── LICENSE
---


