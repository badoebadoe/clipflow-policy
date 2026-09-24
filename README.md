# ClipFlow

Personal clip automation tool for content creators.

## What It Does
1. Fetches YouTube video transcripts
2. Uses AI (Gemini) to identify viral moments
3. Generates clips via Opus Clip API
4. Posts to YouTube Shorts, Instagram Reels, Facebook Reels, TikTok

## Architecture
- **Local-first** — runs on your machine
- **Python backend** (FastAPI) + **Tauri frontend** (Rust)
- **No cloud dependency** — all data stays on your device

## OAuth Apps
This repository uses private OAuth applications for:
- Google (YouTube)
- Meta (Instagram + Facebook)
- TikTok

These apps are in **Test Mode** for personal use only.

## Not For
- Commercial distribution
- Public SaaS offering
- Bulk automation beyond platform limits