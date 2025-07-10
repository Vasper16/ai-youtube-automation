# AI-Powered YouTube Automation Pipeline

This project is a fully automated, AI-powered video generation pipeline built using [n8n](https://n8n.io/). It streamlines the entire YouTube content creation process—from topic ingestion to video upload—without requiring manual editing or narration.

## 🚀 Features

- ✨ LLM-generated scripts via OpenAI
- 🎙️ Voice narration using ElevenLabs API
- 🎞️ Video rendering with JSON2Video
- 🎶 Automatic music and intro selection
- 📊 Google Sheets as control panel for prompts & metadata
- 🔁 Error handling, retries, and logging integrated
- 📤 One-click publishing to YouTube (optional)

## 📂 Workflow Structure

1. **Input Generation**
   - Topic & prompt ingestion via Google Sheets
   - GPT-4 generates structured script

2. **Media Fetching**
   - Dynamic selection of intro clips and background music

3. **Narration & Rendering**
   - ElevenLabs for voice synthesis
   - JSON2Video assembles complete video

4. **Error Handling**
   - Retry logic and fallback mechanisms built into n8n

5. **Final Output**
   - Preview + automatic publishing support

## 📁 Files Included

- `n8n-workflow.json` – Complete export of n8n pipeline
- `docs/architecture.png` – Workflow diagram
- `samples/demo-output.mp4` – Sample generated video (optional)
- `integrations.md` – API usage and configuration details

## 🧠 Tech Stack

- [n8n](https://n8n.io/)
- [OpenAI GPT-4](https://platform.openai.com/)
- [ElevenLabs](https://www.elevenlabs.io/)
- [JSON2Video](https://json2video.com/)
- Google Sheets API
- YouTube Data API (optional for publishing)

## 📌 Use Cases

- Solo YouTube creators
- AI media agencies
- Educational content automation
- Scalable video production systems

---

Let me know once you're ready and I can help you write or refine:
- The full `README.md`
- Diagrams (I can generate for you)
- Any GitHub Actions (if you want to automate uploads or commits)

Just upload the exported `.json` file and start the repo—I'll guide you from there.

