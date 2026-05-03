# Voice-Pro-Fork: Ultimate AI Voice & Video Dubbing Studio

**Voice-Pro-Fork** is an enhanced version of the original Voice-Pro project, transformed into a professional automated dubbing studio. This fork focuses on mass content localization and high-fidelity visual synchronization.

![ABUS-logo](docs/images/ABUS-logo.jpg)

---

## 🚀 Key Improvements in this Fork

1.  **Batch Dubbing (Mass Localization):**
    *   Fully implemented automated workflow for entire folders.
    *   Automatic matching of translated subtitles (SRT) with source videos.
    *   Seamless mixing of AI voiceovers with background audio (Instrumentals).

2.  **Integrated Lip-Sync:**
    *   Built-in support for **Wav2Lip** technology.
    *   Synchronizes video lip movements with the newly generated dubbed audio.
    *   Available for both single-file processing and batch mode.

3.  **Engine Optimizations:**
    *   Enhanced integration with state-of-the-art TTS engines: Edge-TTS, F5-TTS, CosyVoice, and Kokoro.

---

## 🛠 Installation Guide

### Prerequisites
*   **Python 3.10**
*   **Git**
*   **FFmpeg** (Must be added to your system PATH)
*   **NVIDIA GPU** (Highly recommended for Lip-Sync and advanced TTS)

### Setup Steps
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/perejaslav/voice-pro-fork.git
    cd voice-pro-fork
    ```
2.  **Run Configuration:**
    Execute `configure.bat` (Windows) or `configure.sh` (Linux) to set up the environment and dependencies.
3.  **Download Models:**
    Place Wav2Lip checkpoints (`wav2lip_gan.pth` and `s3fd.pth`) into the `model/lipsync/` directory.
4.  **Start the App:**
    Run `start.bat` and open the URL provided in the terminal (usually `http://127.0.0.1:7860`).

---

## 📖 Features

*   **YouTube Integration:** Download and process videos directly from URLs.
*   **Advanced ASR:** Multi-engine speech recognition (WhisperX, Faster-Whisper, etc.).
*   **High-Quality TTS:** Support for voice cloning and multilingual synthesis.
*   **RVC Support:** Change the dubbed voice to any specific persona.
*   **Video Enhancement:** Integrated RTX Video Super Resolution.

---

## ©️ Credits
Original Project: [ABUS Voice-Pro](https://github.com/abus-aikorea/voice-pro).
Fork Improvements: [perejaslav](https://github.com/perejaslav).

Licensed under MIT. See `LICENSE` for details.
