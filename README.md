# 🎮 T5 Game Commentator with Voice 🎙️

This project trains a **T5-small transformer model** to generate **natural language game commentary** from strategic game events (e.g., Clash Royale moves) and **speaks them out loud** using `gTTS`.

> ✅ Built and tested using **Google Colab**  
> 🎓 Created by: Revanth Reddy Avuthu

---

## 🔧 Tech Stack

- 🤗 Hugging Face Transformers (`T5ForConditionalGeneration`, `Trainer`)
- 🧠 Custom dataset in `.csv` format
- 🗣️ Text-to-speech using `gTTS`
- 🔊 Voice output inside Colab using `IPython.display.Audio`
- 📚 Data processing using `datasets` and `pandas`
