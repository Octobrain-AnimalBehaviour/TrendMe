🎬 TrendMe: Trend-Aware Brand Video Generator
Team Members: Ever Solís, Adrián Alemán, Brenda Scarleth Gutierrez, Alejandro Luna
Project by: Octobrain

🔍 About TrendMe
TrendMe is a tool that helps brands generate promotional videos based on real-time trends from social media. It scrapes trending YouTube Shorts, analyzes their content, and generates branded videos that match the trend's context and style.

📁 Main File
video_and_audio_analysis.ipynb: Contains the complete pipeline from data scraping to video generation.

⚙️ How to Run
API Keys Required:

Google YouTube Data API

HailuoAI API

Set Up:

Use Google Colab with a GPU runtime

Run all cells in order

Provide input parameters when prompted

🔄 Pipeline Overview
Scrape Trending Videos

Based on filters: style, duration, and keywords

Extract Contextual Features
From each video:

visual_style

topic_summary

text_narration

visual_assets_needed

audio_tone

audio_type

emotion_tone

emotion_triggered

trend_or_meme_reference

target_audience

audience_intent

Generate Prompt

Combines trend context + brand input

Generate Branded Video

Uses AI to create a promotional video aligned with trends and brand identity

🧠 Tech Stack
Python

YouTube Data API

HailuoAI (video generation)

LlavaNextVideoForConditionalGeneration (video-language model)

Custom text-to-video prompt system

