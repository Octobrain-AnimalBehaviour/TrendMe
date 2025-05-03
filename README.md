# 🎬 TrendMe: Trend-Aware Brand Video Generator

**Team Members**: Ever Solís, Adrián Alemán, Brenda Scarleth Gutierrez, Alejandro Luna  
**Project by**: [Octobrain](#)

---

## 🔍 About TrendMe

**TrendMe** is an AI-powered tool that helps brands create promotional videos based on *real-time trends* from social media. It scrapes trending **YouTube Shorts**, analyzes their content, and generates branded videos that match the trend’s context and style.

---

## 📁 Main File

- `video_and_audio_analysis.ipynb`: Contains the complete pipeline from **data scraping** to **video generation**.

---

## ⚙️ How to Run

### 🔐 API Keys Required
- Google **YouTube Data API**
- **HailuoAI** API

### 🚀 Setup Instructions
1. Open the notebook in **Google Colab** (GPU runtime recommended).
2. Run all cells **in order**.
3. Provide **input parameters** when prompted.

---

## 🔄 Pipeline Overview

### 1. **Scrape Trending Videos**
- Filter by: `style`, `duration`, and `keywords`

### 2. **Extract Contextual Features**
From each video:
- `visual_style`
- `topic_summary`
- `text_narration`
- `visual_assets_needed`
- `audio_tone`
- `audio_type`
- `emotion_tone`
- `emotion_triggered`
- `trend_or_meme_reference`
- `target_audience`
- `audience_intent`

### 3. **Generate Prompt**
- Combines **trend context** with **brand input**

### 4. **Generate Branded Video**
- Uses AI to create a **promotional video** aligned with the **trend** and **brand identity**

---

## 🧠 Tech Stack

- **Python**
- **YouTube Data API**
- **HailuoAI** (video generation)
- `LlavaNextVideoForConditionalGeneration` (video-language model)
- Custom **text-to-video prompt system**

---

> 🎯 TrendMe empowers marketers to stay on trend, increase engagement, and rapidly respond to cultural moments.
