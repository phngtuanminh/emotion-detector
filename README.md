# EmoSense – AI Emotion Detector 🎭

> An AI-powered web application that detects and visualizes emotions in text using Claude AI (Anthropic).

---

## 📌 Project Overview

**EmoSense** is an AI-based web application built as part of a final project in the role of a software engineer. It analyzes any input text — such as messages, reviews, journal entries, or social media posts — and identifies the underlying emotions using natural language processing powered by the Claude AI API.

The application provides:
- 🎯 **Primary emotion detection** with confidence score
- 📊 **Emotion breakdown** across 8–10 emotion categories
- 🌈 **Sentiment classification** (Positive / Negative / Neutral / Mixed)
- 💡 **AI-generated insight** describing the emotional pattern

---

## 🚀 Features

| Feature | Description |
|---|---|
| Real-time Emotion Analysis | Analyzes text instantly via Claude AI API |
| Multi-emotion Detection | Identifies joy, sadness, anger, fear, anxiety, and more |
| Confidence Scoring | Each emotion is scored from 0–100% |
| Sentiment Analysis | Classifies overall sentiment of the text |
| Preset Samples | Predefined example texts for quick testing |
| Animated UI | Smooth animated bars and visual feedback |
| Responsive Design | Works on desktop and mobile |

---

## 🧠 AI Model

This project uses **Anthropic's Claude Sonnet** model (`claude-sonnet-4-20250514`) via the Anthropic Messages API.

The model is prompted to return structured JSON containing:
- Primary emotion and confidence level
- Scores for all detected emotions
- Overall sentiment classification
- A natural language insight

---

## 🗂️ Project Structure

```
emotion-detector/
│
├── index.html        # Main application file (HTML + CSS + JS)
└── README.md         # Project documentation
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Backend | Anthropic Claude API (claude-sonnet-4) |
| Fonts | Google Fonts (Syne, DM Mono) |
| Deployment | Static hosting (GitHub Pages / Netlify / Vercel) |

---

## ⚙️ How to Run

### Option 1 – Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/emotion-detector.git
   cd emotion-detector
   ```

2. Open `index.html` directly in your browser (no build step required).

> **Note:** The Anthropic API key is handled by the Claude.ai environment. If running outside Claude.ai, you will need to inject your own API key in the fetch headers inside `index.html`.

### Option 2 – Deploy on GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Set source to `main` branch, `/ (root)`.
4. Your app will be live at: `https://your-username.github.io/emotion-detector`

---

## 🎮 Usage

1. Type or paste any text into the input box.
2. Or click one of the **preset example buttons** to load a sample.
3. Click **"Analyze Emotions"**.
4. View the results:
   - Primary emotion with confidence bar
   - Full emotion breakdown with individual scores
   - Sentiment classification
   - AI-generated insight

---

## 🏷️ Emotion Categories

The app can detect the following emotions:

`joy` · `sadness` · `anger` · `fear` · `disgust` · `surprise` · `anticipation` · `trust` · `frustration` · `love` · `anxiety` · `nostalgia` · `pride` · `relief` · `envy` · `hope` · `loneliness` · `neutral`

---

## 📸 Screenshots

> The application features a dark-themed UI with animated gradient blobs, real-time bar chart animations, and color-coded emotion indicators.

---

## 📄 License

This project is submitted as a Final Project for educational purposes.

---

## 👤 Author

- **Project Name:** EmoSense – AI Emotion Detector  
- **Role:** Software Engineer (Final Project)  
- **AI Model Used:** Anthropic Claude Sonnet  
- **Year:** 2025

---

## 🙏 Acknowledgements

- [Anthropic](https://www.anthropic.com/) — for the Claude AI API
- [Google Fonts](https://fonts.google.com/) — for Syne & DM Mono typefaces
