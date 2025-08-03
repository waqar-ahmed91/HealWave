# 🌊 HealWave

**HealWave** is an AI-powered emotional and behavioral insight tool designed to analyze real-world therapeutic and coaching conversations. By leveraging advanced speech-to-text and language models, HealWave identifies deep conversational patterns helping users surface emotional blindspots, communication breakdowns, and growth opportunities.

---

## What is HealWave?

HealWave takes audio from therapy sessions, coaching calls, or personal reflections and returns structured, actionable insights. It highlights:

- 🔁 **Topic looping** revisiting the same emotional themes
- 💬 **Emotionally charged phrases** outbursts, pain, anger, sadness
- 🚪 **Avoidance behavior** shifting topics, dodging confrontation
- 🔄 **Contradictions** conflicting statements or blame shifting
- 👤 **Pronoun shifts** e.g., "I" to "you", "we" to "they"
- 🧾 **Concise session summaries** — focused around the actual speakers

---

## 🚀 Features

- 🎙️ **WhisperX**-based transcription (fast, accurate, speaker-aware)
- 💬 **OpenAI / Ollama integration** for conversation insight generation
- 📋 **Structured JSON output** with clear pattern detection
- 🧑‍💻 **Streamlit-based UI** for uploading audio and viewing results
- 📁 **CSV + JSON export** for historical tracking and post-session review
- 🔒 **Client name tagging** with timestamps for secure recordkeeping
- ⚡ **Append-only data logging** to prevent overwriting past session data
- 🔄 **Switch between OpenAI and local models** seamlessly

---

## 🛠 How It Works

1. **Upload audio** of a conversation (WAV/MP3).
2. **Transcription** is handled using WhisperX.
3. An **LLM analyzes** the transcript based on behavioral and psychological markers.
4. The output is a **structured JSON + summary** with actionable insights.
5. **CSV and JSON** files are stored or appended with session data and client name.

---

## 📂 Output Example

```json
{
  "looped_topics": ["fear of failure", "lack of control"],
  "emotional_phrases": ["I'm not good enough", "I hate this job"],
  "contradictions": ["I'm fine" vs "No one understands me"],
  "avoidance": ["Let’s not talk about that right now"],
  "pronoun_shifts": ["I → you", "we → they"],
  "summary": "Speaker 1 expresses anxiety about their career and avoids discussing personal relationships. Therapist encourages self-exploration."
}
```

---

## ✅ Use Cases

- 🧑‍⚕️ **Therapists & Psychologists** — Detect patterns for clinical insights
- 🧘‍♀️ **Life Coaches** — Identify blocks and breakthroughs
- 🧑‍💼 **Corporate Coaches** — Understand interpersonal blindspots
- 💬 **Individuals** — Self-reflect on conversations or journaling

---

## ⚙️ Requirements

- Python 3.9+
- `whisperx`
- `openai` or `ollama`
- `streamlit`
- `pandas`
- `datetime`, `os`, `json`, `uuid`

---

## 💡 Roadmap

- [x] Audio transcription with speaker diarization  
- [x] LLM-based conversation insight generation  
- [x] CSV/JSON export with timestamp & client name  
- [ ] Multi-language support  
- [ ] Dashboard with trend analysis across sessions  
- [ ] HIPAA-ready data encryption and access controls

---

## 🛡️ Disclaimer

HealWave is intended for **insight and reflection**, not as a replacement for licensed therapy. Always consult a qualified mental health professional for clinical decision-making.

---

## 🤝 Contributing

Want to improve the prompt engine, UI, or model switching logic? PRs are welcome!

---

## 📫 Contact

For questions, support, or collaboration opportunities, please contact:

**Waqar Ahmed**  
GitHub: [@waqar-ahmed91]
