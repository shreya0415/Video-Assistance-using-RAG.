# 🎬 Video Agent

**Turn YouTube Videos into Actionable Intelligence in Seconds.**

Video Agent is an AI-powered pipeline designed to ingest video content, transcribe it with high accuracy, and extract meaningful insights using Large Language Models and Retrieval-Augmented Generation (RAG). 

---

## ✨ Features

*   **🎙️ Smart Multilingual Transcription:** Employs **Whisper** for standard English and **Sarvam** for Hinglish audio processing.
*   **🧠 Automated Intelligence Extraction:** Utilizes **LangChain** and **MistralAI** to automatically generate titles, comprehensive summaries, action items, key decisions, and open questions.
*   **🔍 RAG Engine Integration:** Built-in **ChromaDB** vector store to slice, embed, and query video transcripts for conversational retrieval.
*   **⚡ Automated Pre-Processing:** Seamlessly handles downloading and audio extraction via **yt-dlp** and **FFmpeg**.

---

## 🏗️ Project Architecture

```text
Video Agent/
├── .env                  
├── Requirements.txt       
├── test.py                
├── core/
│   ├── __init__.py
│   ├── extractor.py       
│   ├── rag_engine.py      
│   ├── summarizer.py      
│   ├── transcriber.py     
│   └── vector_store.py    
└── utils/
    └── audio_processor.py