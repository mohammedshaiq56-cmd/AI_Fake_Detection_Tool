# AI_Fake_Detection_Tool
AI-powered fact-checking engine with real-time web search, voice assistant, bias analysis, AI content detection, and source credibility scoring. Built with React + Groq (Free API).


# ⬡ FactCheck.ai

> **Stop Trusting. Start Verifying.**

An AI-powered fact-checking platform that takes any article, essay, or text and runs it through a 5-stage verification pipeline — extracting claims, searching real-time web evidence, scoring sources, detecting AI-generated content, analyzing bias, and delivering a full accuracy report in under 60 seconds.

Built for the **AI Fact-Check & Claim Verification Hackathon**.
Powered entirely by **free APIs** — no credit card required.

---

## 🚀 What It Does

Paste any news article or text → get a complete fact-check report with:

- ✅ **Verdict per claim** — True / False / Partially True / Unverifiable
- 🔍 **Live web search** — every claim verified against real-time sources
- 🤖 **AI content detection** — probability score for AI-generated vs human-written
- ⚖️ **Bias analysis** — political lean, tone, objectivity, and emotional language
- ◉ **Source credibility** — every source rated High / Medium / Low by domain
- 🎙️ **Voice assistant** — dictate text, issue voice commands, hear reports read aloud
- 📊 **Analytics dashboard** — accuracy trends, verdict distribution, history
- ⎙ **PDF & JSON export** — download your full report

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 5-Stage Pipeline | Extract → Search → Verify → Analyze → Report |
| Claim Extraction | AI isolates every verifiable atomic fact from your text |
| Real-Time Evidence | Groq `compound-beta` searches the live web per claim |
| Verdict Engine | TRUE / FALSE / PARTIALLY TRUE / UNVERIFIABLE + confidence % |
| Source Credibility | Domain tier database (Reuters = High, Reddit = Low) |
| AI Text Detection | Probability ring + detection signals + combined verdict |
| Combined Verdict | "AI-Generated + Mostly False" or "AI-Generated but Accurate" |
| Bias Analysis | Political lean spectrum, tone, objectivity, loaded terms |
| Voice Assistant | Speech input, 10 voice commands, full TTS report readout |
| Check History | 50 reports saved locally — searchable and re-loadable |
| Analytics | Canvas-rendered charts — accuracy trend + verdict donut |
| PDF Export | Print-formatted dark-theme report with all claims |
| JSON Export | Full structured report data for downstream use |

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18 + Vite 5 |
| LLM | Groq `llama-3.3-70b-versatile` (claim extraction, AI detection, bias) |
| Web Search | Groq `compound-beta` (built-in live Google Search grounding) |
| Voice Input | Web Speech API — SpeechRecognition |
| Voice Output | Web Speech Synthesis API (chunked + Chrome resume fix) |
| Charts | Canvas 2D API — zero chart libraries |
| Storage | localStorage — no backend, no database |
| Styling | Inline styles — zero CSS dependencies |
| Build | Vite 5 → static `dist/` |

---

## 🆓 Free API — No Credit Card Needed

Uses **Groq** free tier:

| Limit | Free Tier |
|---|---|
| Requests/day | 14,400 |
| Tokens/day | 500,000 |
| Web Search | ✅ Included (compound-beta) |
| Cost | **$0.00** |

Get your key in 30 seconds → **[console.groq.com/keys](https://console.groq.com/keys)**
```

---

**GitHub Topics** (add these as tags on your repo):
```
react  vite  groq  llm  fact-checking  misinformation  ai  voice-assistant  
web-speech-api  bias-detection  ai-detection  hackathon  javascript  nlp
```

---

**About section** (the short blurb on the right sidebar):
```
AI-powered fact-checking with real-time web search, voice assistant, bias & AI detection. Free (Groq API). React + Vite.
