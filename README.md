# Anurag-Subtitles (SubtitleAI)

AI-powered professional video subtitle generator and Premiere Pro style subtitle editor.

## Features
- **AI Speech-to-Text**: Powered by Groq Whisper, Google Gemini Flash (`gemini-3.8-flash`), and OpenAI Whisper.
- **Multilingual & Script Support**: Transcribes and translates Hindi (Devanagari), Hinglish (Roman script), and English.
- **Premiere Pro Style Timeline**: Clean timecode ruler (`00:00`, `00:01`, `00:02`...), draggable blocks, and live playhead scrubber.
- **Unified Subtitle Track**: Single clean track layout with real-time video preview.
- **Export Formats**: SRT, VTT, and video hardcoded subtitles.
- **Theme**: Midnight Purple (`#8B5CF6`) + Cyan (`#22D3EE`) dark aesthetic.

## Tech Stack
- React 19 + TypeScript + Vite
- Lucide React icons
- Web Audio API (in-browser 16kHz mono audio downsampling)

## Getting Started

```bash
npm install
npm run dev
```
