# 🧠 RealityCheck: News Bias & Credibility Analyzer

**RealityCheck** is an AI-powered tool designed to detect **political bias**, **sentiment**, and **credibility** in news headlines or full articles. Built for transparency and awareness in media consumption, this tool offers:

- 🔍 Bias classification (Left, Center, Right)
- 😊 Sentiment analysis (Positive, Negative, Neutral)
- ✅ Credibility estimation (High, Medium, Low)
- 📊 Live charts + textual explanation
- 🧾 Works offline (no API key required)

---

## 🚀 Demo

### 🧠 RealityCheck: News Bias & Credibility Analyzer
**[🚀 Try the Live Notebook →](https://app.scribbler.live/?jsnb=github:adityasingh-0803/realitycheck-news-bias-analyzer/Realitycheck.jsnb)**

![Demo Screenshot](https://github.com/user-attachments/assets/33571628-43dc-4ab3-96f1-89641b3f9f92)


---

## 📦 Features

- 🔍 NLP-based bias detection
- 📈 Pie charts for bias/sentiment/credibility
- 🗃️ JSNB notebook format — ideal for hackathons
- 🧠 Local ML model — no need for OpenAI API key
- 📤 GitHub integration for versioning

---

## 📂 Folder Structure

| Path              | Description                      |
|-------------------|----------------------------------|
| `notebook/`       | Scribbler-compatible `.jsnb`     |
| `utils/`          | ML + NLP helper functions        |
| `assets/`         | Screenshots, logos               |
| `models/`         | Pretrained model files (optional)|
| `requirements.txt`| Python dependencies              |

---

## 🧠 How It Works

The notebook takes a news article or headline and:
1. Detects **keywords** associated with left/right-leaning language.
2. Analyzes **sentiment polarity** (positive, neutral, negative).
3. Checks for **trust signals** like length, clickbait, unknown phrases.
4. Displays results with **pie charts** and **natural language explanation**.

---

## 🔧 Requirements

```bash
pip install -r requirements.txt

