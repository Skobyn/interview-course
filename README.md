# Google SA Interview Prep — AI/ML Course

Built for Scott Benson's Round 2 technical interview at Google Cloud.

## How to Open

**Option 1: File directly in browser**
```
open /home/node/.openclaw/workspace/interview-course/index.html
```
Or navigate to the file in your browser: `File → Open File` and select `index.html`.

**Option 2: Serve locally (for audio to work properly)**
```bash
cd /home/node/.openclaw/workspace/interview-course
python3 -m http.server 8080
```
Then open: http://localhost:8080

> Audio requires the files to be served (not just opened as file://) for browser security reasons. Use Option 2 for full audio playback.

## Course Structure

| Module | Topic | Time | Audio |
|--------|-------|------|-------|
| 1 | Embeddings — How They Actually Work | ~25 min | ✅ |
| 2 | Fine-Tuning vs RAG vs Prompting | ~30 min | ✅ |
| 3 | AI Evaluation — How You Know It's Working | ~25 min | ✅ |
| 4 | BigQuery ML — Anomaly Detection Focus | ~25 min | ✅ |
| 5 | Vertex AI Pipelines | ~20 min | ✅ |

**Total: ~2 hours**

## Features
- 🔒 Modules gate on quiz pass (3/5 required to unlock next module)
- 🧠 N-back recall: prior module questions surface before each new module
- 📊 Interview Readiness Score (0-100) tracked in localStorage
- 🎵 60-90 second audio intro per module (ElevenLabs)
- 📱 Mobile-friendly — works on the plane

## Audio Files
All 5 audio files generated successfully via ElevenLabs:
- `audio/module-1-intro.mp3` (~1.3 MB)
- `audio/module-2-intro.mp3` (~1.4 MB)
- `audio/module-3-intro.mp3` (~1.5 MB)
- `audio/module-4-intro.mp3` (~1.5 MB)
- `audio/module-5-intro.mp3` (~1.5 MB)

## Progress
Progress is saved in your browser's localStorage. It persists between sessions on the same browser.
