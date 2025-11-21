# 🎧 Genshin Impact Dialogue Voice Dataset  
### Natural In-Game Storyline Speech from Ayaka, Keqing, Klee, and Nahida

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)  
[![Dataset on AI Studio](https://img.shields.io/badge/Dataset-AI%20Studio-blue)](https://aistudio.baidu.com/datasetdetail/252476/0)

This open dataset features **authentic, emotionally expressive dialogue** spoken by four iconic *Genshin Impact* characters—**Kamisato Ayaka**, **Keqing**, **Klee**, and **Nahida**—as heard in **main quests, world quests, and cinematic story scenes**.

Unlike combat barks or idle voice lines, these recordings capture **natural conversational speech**: rich prosody, contextual emotion, and narrative continuity—making them ideal for:

- 🎙️ **Speech Recognition (ASR)** with expressive intonation  
- 🗣️ **Text-to-Speech (TTS)** modeling of character-specific vocal styles  
- ❤️ **Emotion and speaker-style analysis**  
- 🤖 **Dialogue systems & role-playing AI research**

> ⚠️ **For non-commercial use only**. Audio is extracted from *Genshin Impact* (© miHoYo) and compiled by fans. This project is **not affiliated** with miHoYo or its subsidiaries.

---

## 📦 Dataset Structure

The dataset is organized into **one ZIP file per character**, using standardized English filenames for cross-platform compatibility:

```
genshin-dialogue-voices/
├── data.zip     ← Kamisato Ayaka (神里绫华)
├── keqing.zip    ← Keqing (刻晴)
├── klee.zip      ← Klee (可莉)
├── nahida.zip    ← Nahida (纳西妲)
└── README.md
```

Each archive contains:
- Multiple `.wav` audio clips (**16 kHz, mono**, typically 1–5 seconds)
- A `transcript.txt` file with **line-aligned Chinese transcripts**

### Example (`klee.zip` contents):

1.wav
2.wav
...
187.wav



🔹 The number in the filename (e.g., `1.wav`) matches the line number in `transcript.txt`.  
🔹 All audio is **manually segmented** from actual storyline dialogue in *Genshin Impact*.

---

## 🔗 Download

The complete dataset is hosted on **Baidu AI Studio**:  
👉 [https://aistudio.baidu.com/datasetdetail/252476/0](https://aistudio.baidu.com/datasetdetail/252476/0?login_type=weixin)

💡 **Note**: You’ll need to log in with a **WeChat or Baidu account** to download the files.

---

## 📜 License

This dataset is released under the **Creative Commons Attribution-NonCommercial 4.0 International License** ([CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)).

✅ **You are free to**:
- Use the data for academic research, personal projects, or non-commercial AI development  
- Share and adapt the dataset, provided you give appropriate credit

❌ **You may not**:
- Use it in any commercial product, service, or monetized application  
- Redistribute the raw audio as a standalone product  
- Claim ownership of the original voice lines

### Attribution Statement:
> "Voice data sourced from storyline dialogues in *Genshin Impact*, compiled by community contributors. Original audio © miHoYo."

---

## 🤝 Contributions Welcome!

Help improve this dataset by:
- Submitting corrections to `transcript.txt` (typos, mismatches)  
- Adding metadata (e.g., quest name, emotional label, scene context)  
- Sharing utility scripts (audio resampling, format conversion, etc.)

Feel free to open an **Issue** or **Pull Request**!

---

✨ *May your models speak with the grace of Ayaka, the resolve of Keqing, the joy of Klee, and the wisdom of Nahida.*

> Not affiliated with miHoYo or the creators of *Genshin Impact*.

--- 

