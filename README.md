# Music_generator 🎵🤖

Generate AI-powered music from text prompts using [MusicGen](https://github.com/facebookresearch/audiocraft)!  
Create unique tracks in seconds with customizable style, duration, tempo, and volume.

## 🚀 Features

- 🎼 **Text-to-Music Generation:** Describe your desired music and let AI compose it!
- 🎹 **Style & Instrument Selection:** Choose from genres like cinematic, jazz, pop, piano, rock, and more.
- ⏱️ **Custom Duration & Tempo:** Control how long and fast your music plays.
- 🔊 **Volume Control:** Amplify or soften your generated track.
- 📈 **Waveform Visualization:** See the waveform of your music.
- ▶️ **Instant Playback:** Listen to your creation directly in the browser.
- 💾 **Download Option:** Save your generated music as a WAV file.

## 💡 Insights & Tips

- **Model Used:** [facebook/musicgen-small](https://huggingface.co/facebook/musicgen-small) by Meta AI.
- **Prompt Tips:**
  - Describe mood, genre, instruments, or atmosphere.
  - Example: `energetic electronic dance with deep bass`
  - Combine styles: `cinematic piano with orchestral strings`
- **Generation Details:**  
  After each generation, you’ll see the prompt, duration, tempo, and volume used.
- **Resource Usage:**  
  The app runs locally and uses your system’s CPU/GPU for inference.

## 🛠️ Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/Music_generator.git
    cd Music_generator
    ```
2. Install dependencies:
    ```sh
    pip install -r requirement.txt
    ```

## 📦 Dependencies

See [`requirement.txt`](requirement.txt) for all required packages.

## 💻 Usage

Run the Streamlit app:
```sh
streamlit run music.py
```

1. Select a style or enter your own prompt.
2. Adjust duration, tempo, and volume.
3. Click **Generate Music**.
4. Listen, visualize, and download your track!

## 📝 License

This project is for educational and research purposes.

---

Made with ❤️ using AI and [MusicGen](https://github.com/facebookresearch/audiocraft).
