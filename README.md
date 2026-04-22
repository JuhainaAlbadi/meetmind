# 🧠 MeetMind — AI Meeting Minutes Generator

> Transform messy meeting transcripts into structured, actionable insights in seconds — powered by Claude AI.

![MeetMind Demo](screenshot.png)

---

## ✨ What it does

Paste any meeting transcript and MeetMind instantly extracts:

- 📋 **Executive Summary** — concise 2-3 sentence overview
- ✅ **Action Items** — tasks with assignees and deadlines
- ⚡ **Key Decisions** — what was agreed upon
- 🔮 **Next Steps** — what happens after the meeting

No more spending 15–20 minutes writing meeting notes manually.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Engine | Claude API (claude-sonnet) |
| Styling | Custom CSS with CSS Variables |
| Fonts | Google Fonts (DM Serif Display, DM Mono, Syne) |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/JuhainaAlbadi/meetmind.git
cd meetmind
```

### 2. Get a Claude API key
Sign up at [console.anthropic.com](https://console.anthropic.com) and create an API key.

### 3. Run it
Just open `index.html` in your browser — no build tools or dependencies needed.

> **Note:** The app calls the Anthropic API directly from the browser. For production use, route API calls through a backend to protect your API key.

---

## 📸 Demo

Try it with the built-in sample transcript by clicking **"Load sample transcript"**, then hit **Generate Meeting Minutes**.

---

## 🧩 How it works

```
User pastes transcript
        ↓
Transcript sent to Claude API with structured prompt
        ↓
Claude returns JSON with summary, actions, decisions, next steps
        ↓
UI renders results in an interactive dashboard
```

The prompt engineering is designed to extract **named assignees**, **specific deadlines**, and **concrete decisions** — not vague summaries.

---

## 💡 Use Cases

- **Startups** — keep remote teams aligned after standups
- **Universities** — summarize study group or project meetings
- **Corporates** — automate HR, IT, and PM meeting documentation

---

## 🗺️ Roadmap

- [ ] Export to PDF / Word
- [ ] Support audio file input (Whisper API transcription)
- [ ] Slack / Teams integration
- [ ] Multi-language support (Arabic 🇴🇲)

---

## 👩‍💻 Author

**Juhaina Albadi**
BSc Computer Engineering Student

[![GitHub](https://img.shields.io/badge/GitHub-JuhainaAlbadi-181717?style=flat&logo=github)](https://github.com/JuhainaAlbadi)

---
