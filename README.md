# 🧠 MindSense-AI: Emotional Intelligence & Adaptive Wellness Companion

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Transformers](https://img.shields.io/badge/🤗_Transformers-NLP-yellow?style=for-the-badge)](https://huggingface.co/docs/transformers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

## 🏛️ Project Overview

MindSense-AI is an intelligent mental wellness companion that leverages Natural Language Processing to analyze emotional states in real-time. By interpreting the sentiment, tone, and underlying context of user input, the system delivers adaptive, personalized recommendations aimed at improving emotional well-being — bridging the gap between raw text data and empathetic, actionable support.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🎭 **Emotion Detection** | Analyzes text input to classify underlying emotional states with high accuracy. |
| 🎯 **Adaptive Recommendations** | Generates personalized wellness suggestions based on detected mood patterns. |
| 📊 **Sentiment Tracking** | Monitors emotional trends over time to surface meaningful patterns. |
| 💬 **Interactive Interface** | Clean, conversational Streamlit UI for seamless real-time interaction. |

---

## 🛠️ Technical Architecture

### How It Works

1. **Input Processing** — User text is captured through the Streamlit interface.
2. **NLP Pipeline** — Transformer-based models analyze the text for emotional and sentiment signals.
3. **Classification** — The system maps detected patterns to specific emotional states.
4. **Recommendation Engine** — Adaptive logic generates contextually relevant wellness suggestions.
5. **Feedback Loop** — Results are displayed instantly, enabling continuous, real-time interaction.

### Tech Stack

| Component | Tool Used |
|---|---|
| **Language** | Python 3.10+ |
| **NLP Engine** | 🤗 Transformers, NLTK |
| **Web Interface** | Streamlit |
| **ML Utilities** | Scikit-learn, Pandas, NumPy |

---

## 🚀 How to Run

1. **Clone the repository**
```bash
   git clone https://github.com/shubham333k/MindSense.git
   cd MindSense
```

2. **Install dependencies**
```bash
   pip install streamlit transformers nltk scikit-learn pandas numpy
```

3. **Launch the app**
```bash
   streamlit run app.py
```

4. Open `http://localhost:8501` in your browser to start interacting with MindSense-AI.

---

## 📂 Repository Structure

```
MindSense/
├── app.py                 # Main Streamlit application (entry point)
├── sentiment.py            # Emotion & sentiment detection logic
├── mental_state.py          # Tracks and manages user's mental state
├── recommender.py           # Generates adaptive wellness recommendations
├── therapist_model.py       # Core AI model for therapeutic responses
├── history_store.py         # Handles storage/retrieval of conversation history
├── mental_history.db        # SQLite database storing user mental-health history
├── utils.py                 # Helper/utility functions
├── LICENSE                  # MIT License
└── README.md                # Project documentation
```
---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Connect & Collaborate

**Shubham Kumar**
*Computer Science (AIML) Undergraduate*

- 💼 LinkedIn: [shubham-kumar-565040253](https://www.linkedin.com/in/shubham-kumar-565040253/)
- 🐙 GitHub: [@shubham333k](https://github.com/shubham333k)
- 📧 Email: shubhamjhanjhot333k@gmail.com

*Built with the goal of making mental wellness support more accessible through AI-driven emotional intelligence.*
