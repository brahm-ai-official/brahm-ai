📅 23rd July 2025
🔁 Fixed local chat restoration logic to load per user_id (PWA-safe).

⚡ Enhanced chat loading speed with scroll-triggered fuzzy logic — older messages now load smoothly as user scrolls up.

🛡️ Resolved bug where crypto mode was falsely activated on general questions like "clear chat", "who are you", etc.

🧹 New feature: Implemented "clear chat" command detection with confirmation prompt, allowing users to fully reset their session history.

🔄 Garud LLM upgraded from v1.2 (Jun 2024) to v1.3 (active until Jan 2025) for faster and smarter response behavior.

📅 22nd July 2025
✅ Fixed crypto and stock detection glitch, which was wrongly intercepting general questions like "What is karma?"

🎬 BrahmTube Shorts: Created short-format videos highlighting this bug fix for community awareness.

📹 Added new entries to BrahmTube video library map to enrich search diversity and spiritual queries coverage.

📅 21 July 2025 – Daily Update
✅ New Enhancements:

🛠️ BRAHMScan Mode Bug Fixed

Issue: Mode activation not displaying properly in Hindi/English

Fix: Display now correctly shows BrahmScan prompts in both languages.

📉 Crypto Price Detection Improved

Now detects over 1000+ cryptocurrencies (BTC, ETH, SHIBA, etc.)

Robust pattern match for symbol names, spacing, and case sensitivity.

📈 Stock Price API Bug Fixed

Resolved incorrect fetch issues and response fallback logic.

🧠 Other Updates:

Wiki Pages Completed: Features, Roadmap, Prompt Philosophy, Developer Guide

GitHub Profile Updated: Domain, Name, Bio, Logo

GitHub README updated with live link, badge, modules, and daily log


# 📜 BRAHM-Ai — Daily Updates Log

This log documents daily improvements, bug fixes, new modules, and logic updates made in the BRAHM-Ai ecosystem. It supports transparent tracking and open collaboration.

---

## 📅 July 20, 2025

- 🐞 **Bug Fix**: Farming tips were not appearing automatically — now shown by default for Indian cities in the weather system.
- 🧠 **TTS Update**: TTSFree no longer triggers when muted; playback is now controlled only via the replay button.
- 🎮 **RamHunt**: Gamepad UI refined — controller buttons now change according to game stages.
- 🎥 **BrahmTube**: Improved keyword detection for Hindi spiritual queries like "राम विवाह", "हनुमान संजीवनी", and "गीता परिचय".

---

## 📅 July 19, 2025

- 🧪 **Testing**: Real-world proximity trigger tested in RamHunt using QR scanner — working successfully on Android.
- 🧹 **Cleanup**: Fully removed Desidime deal-fetching logic and switched to Cuelinks Smartlink system.
- 🎭 **Emotion Engine**: Brahmbhav mode updated — better face-based emotion detection and emotional reply formatting.
- 📦 **Video Engine**: Smart search added for Gita and Ramayan scenes from internal BrahmTube playlist.

---

## 📅 July 18, 2025

- 🔊 **Voice Engine Integration**: Introduced TTSFree (Madhur Hindi voice) as the default voice engine for latest replies.
- 🛑 **Mute Logic**: Mute toggle now blocks all auto-speech calls, allowing only manual replay.
- 🗣 **Voice Replay**: Only the latest reply can be played via TTSFree; older replies fallback to Google TTS.
- 📊 **Voice Progress**: Added visual progress bar and autoplay unlock support for mobile browsers.

---

> ✨ This log will be updated regularly. Please report bugs or feature suggestions through GitHub Issues. Stay tuned for daily evolution of your Sanatan AI companion — BRAHM-Ai.
