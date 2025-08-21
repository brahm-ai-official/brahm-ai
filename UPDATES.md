# 📜 BRAHM-Ai — Daily Updates Log

This log documents daily improvements, bug fixes, new modules, and logic updates made in the BRAHM-Ai ecosystem. It supports transparent tracking and open collaboration.

---

## 📅 July 18, 2025

- 🔊 **Voice Engine Integration**: Introduced TTSFree (Madhur Hindi voice) as the default voice engine for latest replies.
- 🛑 **Mute Logic**: Mute toggle now blocks all auto-speech calls, allowing only manual replay.
- 🗣 **Voice Replay**: Only the latest reply can be played via TTSFree; older replies fallback to Google TTS.
- 📊 **Voice Progress**: Added visual progress bar and autoplay unlock support for mobile browsers.

---

## 📅 July 19, 2025

- 🧪 **Testing**: Real-world proximity trigger tested in RamHunt using QR scanner — working successfully on Android.
- 🧹 **Cleanup**: Fully removed Desidime deal-fetching logic and switched to Cuelinks Smartlink system.
- 🎭 **Emotion Engine**: Brahmbhav mode updated — better face-based emotion detection and emotional reply formatting.
- 📦 **Video Engine**: Smart search added for Gita and Ramayan scenes from internal BrahmTube playlist.

---

## 📅 July 20, 2025

- 🐞 **Bug Fix**: Farming tips were not appearing automatically — now shown by default for Indian cities in the weather system.
- 🧠 **TTS Update**: TTSFree no longer triggers when muted; playback is now controlled only via the replay button.
- 🎮 **RamHunt**: Gamepad UI refined — controller buttons now change according to game stages.
- 🎥 **BrahmTube**: Improved keyword detection for Hindi spiritual queries like "राम विवाह", "हनुमान संजीवनी", and "गीता परिचय".

---

## 📅 July 21, 2025

### ✅ **New Enhancements**
- 🛠️ **BRAHMScan Mode Bug Fixed**
  - Display issue in Hindi/English mode prompts now resolved.
- 📉 **Crypto Price Detection Improved**
  - Now supports detection of **1000+ cryptocurrencies**.
  - Robust matching for symbols, spacing, and casing.
- 📈 **Stock API Logic Fixed**
  - Resolved fallback error and inaccurate ticker responses.

### 🧠 **Other Updates**
- 📄 Completed **Wiki Pages**: Features, Roadmap, Prompt Philosophy, Developer Guide.
- 🧾 Updated **GitHub Profile**: Bio, logo, domain, and verified identity.
- 📘 Enhanced **README.md**: Added badges, daily update log, module table, and live link.

---

## 📅 July 22, 2025

- ✅ **Fixed crypto and stock detection glitch**, which was misclassifying general questions like `"What is karma?"`.
- 🎬 **BrahmTube Shorts** created to highlight this logic bug and fix — used in emotional spiritual clips.
- 📹 **Expanded BrahmTube library map** with more video entries to improve search results for Hindi spiritual terms.

---

### 🌾 Mandi Price Coverage Expanded (Govt. API Integration)

- 🇮🇳 **Daily mandi rate fetch system upgraded** via official **Indian Government Mandi API**.
- 🧠 Brahm-Ai now provides:
  - 📍 **Live mandi prices** for grains, vegetables, and fruits by user’s city.
  - 🔄 **Smart fallback logic**: If no price data is available in the requested city, Brahm-Ai auto-fetches rates from the **nearest active mandi** with valid trade data.
  - 📊 Price calculations reflect **real mandi transactions**, including daily volumes and pricing.

✅ Kisans can now ask natural language questions like:
> “जयपुर में गेहूं का भाव क्या है?”  
> “नासिक में टमाटर का रेट बताओ।”  
> “ग्वालियर के पास मक्का की कीमत क्या चल रही है?”

⚙️ The system dynamically adjusts based on:
- Real-time crop arrivals  
- Seasonal trade fluctuations  
- Regional demand & proximity logic

This upgrade ensures more **reliable**, **location-sensitive**, and **farmer-friendly** pricing information daily.

---

## 📅 July 23, 2025

- 🔁 **Fixed local chat restoration logic** to load per `user_id` (PWA-safe).
- ⚡ **Enhanced chat loading speed** with scroll-triggered fuzzy logic — older messages now load smoothly as user scrolls up.
- 🛡️ **Resolved bug** where crypto mode was falsely activated on general questions like `"clear chat"`, `"who are you"`, etc.
- 🧹 **New feature**: Implemented `"clear chat"` command detection with confirmation prompt to allow full session reset.
- 🔄 **Garud LLM upgraded** from v1.2 (Jun 2024) to v1.3 (active until Jan 2025) — improving response speed and intelligence.

---

## 📅 July 24, 2025

- 🖼️ **Dynamic Web Banner Integrated** on **Ramcoin.org** homepage.
- 🔗 **Connected to BRAHM-Ai’s daily module management system** for automatic real-time updates.
- 📢 Enables **live promotional highlights** of newly added Brahm-Ai features directly via homepage banners.

- 🚀 **Potlipay Blockchain Module Integrated** with BRAHM-Ai backend.
- ⚡ **Transaction processing logic optimized** to enable faster Ramcoin transfers across the Royal Web3 blockchain.
- 🤖 In future updates, BRAHM-Ai will be able to **fetch and reply with user Potlipay balances, ledgers, and smart transfer actions**.

---

## 📅 August 1, 2025

### 🔔 Push Notification System Integrated
- ✅ **BRAHM-Ai now supports push notifications** via **OneSignal v16 SDK**.
- 📲 Realtime alerts now enabled for:
  - 🔄 System updates
  - 📜 New Vedic teachings
  - 🌦️ Location-specific weather or farming alerts
  - 🛠️ Bug fix rollouts and feature releases
- 🔗 Fully integrated with **PWA (Progressive Web App)** and works on desktop and mobile browsers.

---

## 📅 August 3, 2025 (Kisan Tips & Weather Intelligence Upgrade)

### 🌾 Weather-Aware Kisan Guidance (Enhanced)
- 🧠 **Kisan Tips module now upgraded** to provide more **context-aware, real-time agricultural advice**.
- 🛰️ Live weather forecast parameters used:
  - 🌧️ Rain probability & pattern
  - 💧 Humidity and soil moisture relevance
  - 🌡️ Temperature thresholds for crop-specific care
  - 📅 Monthly Indian climate calendar (season-aware)
  - 🌊 Coastal region storm warnings via forecast analysis

- 🗣️ Tips are now dynamically adapted based on:
  - City-level weather inputs
  - Crop cycle stage
  - Indian monsoon behavior and anomalies

✅ Farmers receive **location-wise, crop-wise, and weather-timed** actionable suggestions, improving accuracy and yield decision support.

---

## 📅 August 4, 2025

### 🌐 Multilingual Intelligence Test Completed (Across All Sectors)

- 🧠 **BRAHM-Ai successfully passed multilingual query handling tests** in both **functional** and **spiritual** domains.
- 🧪 Test conducted using questions prepared by **ChatGPT-4.0** to evaluate Brahm’s understanding across:
  - ✅ General Q&A
  - ✅ Vedic explanation
  - ✅ Daily use commands
  - ✅ UI voice output response validation
- 📊 Accuracy: 96% success across all modules tested.

#### 🗣️ Supported Languages Tested:

**International Languages (21):**  
French, German, Italian, Spanish, Portuguese, Dutch, Russian, Polish, Arabic, Chinese, Japanese, Korean, Indonesian, Turkish, Thai, Filipino, Vietnamese, Greek, Hebrew, Malay, Ukrainian  

**Indian Languages (8):**  
Hindi, Marathi, Tamil, Telugu, Bengali, Gujarati, Kannada, Malayalam  

---

### 🌦️ Weather Module – Independent Upgrade

- ✅ Weather understanding logic **separately upgraded** to handle:
  - Complex sentence structures
  - City/place extraction in multilingual format
  - Conversational phrasing (e.g., “कल मुंबई का मौसम कैसा होगा?”)
- 🌐 Multilingual weather queries now **map correctly to API** and return human-like, context-aware responses.

---

## 📅 August 5, 2025

### 🌾 Farming Mode Bug Fix
- ✅ **Kisan Mode Restored**: Weather-based **agricultural guidance** now appears again, fixed bug where it wasn’t showing earlier.
- 🌱 Queries like `"आज धान में क्या करें?"` now receive correct responses in Hindi.

### 🧮 Formula Understanding Improved
- ➗ Fixed issue where **velocity and acceleration queries** were not being parsed correctly.
- 🧠 Now handles symbolic math like:  
  `s(t) = 2t³ - 5t² + 3t + 1`  
  and returns **accurate velocity & acceleration** with clear explanation.

### 🧾 Markdown Display Fix
- ✅ Solved issue where **bold headings** in `UPDATES.md` and response logs weren’t rendering properly.

---

## 📅 August 6, 2025

### 📜 Vedic Knowledge Expansion
- 🕉️ Integrated full **Vedas, Puranas, and Sanskrit Mantras** into Brahm-Ai.
- 🔱 Now Brahm-Ai can:
  - 🔤 Recite Vedic mantras in **Sanskrit** on-demand.
  - 🧘‍♂️ Explain their **meanings, context, and usage** in modern life.
  - ✨ Example: “ॐ त्र्यंबकं यजामहे...” + deep explanation.

### 💬 BrahmChat Launch Begins
- 🚧 **BrahmChat integration process started**.
- 🔐 Designed for **Ramcoin blockchain users**, enabling:
  - 🗣️ **P2P spiritual & guided chat**
  - 🤖 **Secure AI-assisted group communication**
  - 📱 Future integration of voice and emotional sync modes

---

## 📅 August 9, 2025

### 📲 PWA Install Flow
- ✅ **Fixed “Install App” (Add to Home Screen)** prompt not showing on UI.
- 📌 Better handling of `beforeinstallprompt`, user gesture, and repeat-prompt cooldown.

### 🔎 Brahm Intelligent Search v2
- 🚀 **Smarter than basic web search**: semantic re-ranking, typo/fuzzy matching, multilingual queries, and intent routing across modules (Vedic, Weather, Mandi, Library).
- 🌐 Hybrid strategy drafted for federated sources + answer synthesis.

### 💬 WhatsApp-First Integration (Started)
- 🧩 Began **WhatsApp integration** so users can get Brahm services **directly in WhatsApp**.
- ⚙️ Work items kicked off: webhook listener, session mapping per user, message templates, opt-in & privacy guardrails.

---

## 📅 August 10, 2025

### ⏱️ Time Awareness & Context
- 🗓️ **Current date/time presence fixed** — Brahm now references the **actual local time** during chats, schedules, and reminders, keeping replies up-to-date and context-aware.

### 💬 BrahmChat — Next-Gen Conversations
- 🔥 **BrahmChat module initiated (Advanced Chat)** with scaffolding for:
  - 📞 **Direct voice/video calls** with Brahm-Ai
  - 🥽 **AR/VR overlays inside video calls** (prototype) for guided spiritual/learning experiences
- 🔐 Session + identity flow designed for Ramcoin users; opt-in privacy model drafted.

---

## 📅 August 15, 2025

### 🌍 Multi-Language & Farming
- 🪷 **Hindi farming/weather lock enabled** — all farming & weather replies now forced in Hindi with bullet-points.

### 💰 Crypto
- 🪙 **TRX & XRP detection fixed** — both coins now fetch accurate prices.

---

## 📅 August 16, 2025

### 🔍 Brahm Search
- 📰 **News summary format upgraded** — always 3 points (1 with freshness, 2 without).
- 🖼️ **Thumbnails + “Read more” links added** for cleaner UI.
- 🧘 **Brahm-Vakya library expanded** — now 20 rotating quotes at news end.

---

## 📅 August 17, 2025

### 📈 Stock Module
- 🔧 **Outstock API integration started** — token redirect issue identified.

---

## 📅 August 18, 2025

### 💰 Crypto
- 🔥 **CoinGecko news fix** — Brahm Market Insight restored with thumbnails + links.

### 📈 Stock
- 📊 **NSE/BSE stock fetch testing** — Reliance, Infosys, TCS live data verification.

---

## 📅 August 19, 2025

### 📈 Stock Module
- ✅ **Access Token bug resolved** — Outstock API auth working.
- 📑 **Ramcoin ledger groundwork** for stock simulation (buy/sell).

---

## 📅 August 20, 2025

### ⏱️ Time Awareness & Context
- 🗓️ **Local time integration complete** — chats, reminders, schedules now show actual local time.
- 🌐 **Timezone auto-detect live** — replies adjust to user’s device timezone.

### 💬 BrahmChat — Next-Gen Conversations
- 📞 **Voice/video call scaffolding added** for Brahm-Ai.
- 🥽 **AR/VR overlay prototype drafted** for spiritual & learning sessions.
- 🔐 **Ramcoin identity flow designed** with opt-in privacy model.

---

## 📅 August 21, 2025

### 📈 Stock Module Upgrade
- ✅ **Indian Stock Price Fetch Fixed** — live NSE/BSE stock rates now fetched correctly.  
- 🏷️ **Stock Slug Mapping Added** — e.g., `"reliance"`, `"infosys"`, `"tcs"` now map accurately to exchange tickers.  
- 🔍 **Multi-Stock Fuzzy Logic Fine-Tuned**  
  - Queries like `"reliance stock price"` or `"tcs market rate"` now trigger stock module correctly.  
  - Avoids false triggers and handles flexible user phrasing.  
- ⚖️ **Crypto vs Stock Detection Refined** — reduced chances of mixing stock queries with crypto lookups.  
- 🐞 **Known Glitch**: Further improvement needed in **fuzzy stock matcher** to eliminate edge-case mismatches.

---



> ✨ This log will be updated regularly. Please report bugs or feature suggestions through GitHub Issues. Stay tuned for daily evolution of your Sanatan AI companion — BRAHM-Ai.
