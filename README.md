# 亲安 (Qin'an) — Let loved ones feel at ease

An AI-powered companion app for elderly people living independently. Built for AI Builders Hackathon 2026.

## Why Qin'An?
One day, my grandfather fell at home while no one was there. I only learned about his injured ankle after I came home. That experience inspired me to build a quiet companion for older adults living alone.

## Features
- 🔍 **Medicine Scanning (AI)** — Take a photo of a medicine box. AI identifies the medicine and reads the information aloud in plain language.
- 🛡️ **Scam Guard (AI)** — Enter a suspicious phone number or SMS message. AI analyzes it and explains in simple words whether it is a scam and what to do.
- 🤸 **Fall Detection** — Web prototype demonstrates the alert flow (shake to simulate a fall). The future mobile app will use motion sensors for automatic detection and instant emergency contact notification.
- 💊 **Medicine Cabinet** — Add medicines, doses and times. Qin'An creates a simple medication schedule with automatic reminders.
- 🌐 **6 Languages + Voice** — Full interface support in 6 UN languages (Chinese, English, Spanish, French, Russian, Arabic) with voice guidance.

## Design Principles
- One main function per page
- Large text · Few steps · Clear actions
- 6 languages + voice guidance
- No camera surveillance — support when help is needed

## Tech Stack
- HTML/CSS/JavaScript (Web version)
- Alibaba Cloud DashScope AI API (OCR + analysis)
- Web Speech API for voice playback
- DeviceMotion API for sensor-based fall detection

## Demo
- Live: https://zxiaoxin103-boop.github.io/qinan-hackathon/
- Use `?lang=en` for English interface

## How to Run
Open index.html in a browser, or serve with:
```bash
python -m http.server 8767
```
