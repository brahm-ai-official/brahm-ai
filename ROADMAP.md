# 🗺️ BRAHM-AI Development Roadmap

This roadmap outlines the development direction of the BRAHM-AI ecosystem, including BRAHM True, BRAHM Voice, Garudaa LLMG 108 V2, multilingual intelligence, vision systems, scripture intelligence, Panchang and Jyotish services, business AI agents, and the upcoming BRAHM-AI Developer API.

BRAHM-AI is being developed as an India-first, Hindi-first, multilingual, multimodal, modular, and API-driven artificial intelligence ecosystem.

> **Ancient Knowledge. Modern Intelligence. Connected Action.**

---

## 📌 Status Legend

| Status | Meaning |
|---|---|
| ✅ Live | Available on the production platform |
| 🧪 Experimental | Available for controlled testing |
| 🚧 In Development | Currently being built or refined |
| 🔒 Private Preview | Available only to approved users or partners |
| 🗓️ Planned | Approved for future development |
| 🔍 Research | Under technical evaluation |

Features, priorities, timelines, models, endpoints, and implementation details may change after technical validation, security review, infrastructure testing, and user feedback.

---

## 🌐 Unified BRAHM-AI Platform

**Status:** ✅ Live / Continuing Improvement

Official platform access:

- **Main Platform:** https://brahm-ai.in
- **BRAHM Voice:** https://brahm-ai.in/voice
- **BRAHM True:** https://brahm-ai.in/true
- **BRAHM AI Agents:** https://www.brahm-ai-agents.com
- **Development Updates:** [UPDATES.md](./UPDATES.md)

The unified platform connects:

- Text conversation
- Live voice interaction
- Avatar experiences
- Computer vision and OCR
- Multilingual language processing
- Indian scripture intelligence
- Sanskrit assistance
- Panchang and Jyotish
- News and live information
- Market intelligence
- Agriculture and Mandi Bhav
- Automation
- Business AI phone agents
- Account, quota, and billing systems
- Future developer APIs

---

## 🧠 BRAHM True

**Status:** ✅ Live / Continuing Improvement

BRAHM True is the primary conversation and knowledge interface of the ecosystem.

Current and developing responsibilities include:

- General conversation
- Context-aware reasoning
- Indian knowledge
- Scripture retrieval
- Panchang routing
- Vision-result interpretation
- Live news and web information
- Market and agriculture context
- User language handling
- Session and memory context
- Specialized helper routing
- Safe model and provider fallback

BRAHM True remains the source of truth for the main BRAHM conversation flow.

---

## 🎙️ BRAHM Voice

**Status:** ✅ Live / Continuing Improvement

BRAHM Voice provides the live multilingual voice-avatar experience.

Current capabilities include:

- Speech-to-Text
- Text-to-Speech
- Multilingual voice interaction
- Language-matched speech output
- Avatar lipsync
- Listening, thinking, speaking, idle, and welcome states
- Camera-assisted interaction
- Object and scene understanding
- OCR and medicine-strip reading
- Returning-user greetings
- Voice-triggered supported actions
- Text fallback

BRAHM Voice does not use a separate answer engine. It uses the existing BRAHM True conversation flow.

```text
User Voice
  ↓
Speech-to-Text
  ↓
BRAHM True Conversation Flow
  ↓
Specialized Helper / RAG / Model
  ↓
Response Text
  ↓
Text-to-Speech
  ↓
Avatar Output
```

---

## 📷 Vision Intelligence

**Status:** ✅ Live / 🧪 Experimental / 🚧 Continuing Improvement

Current and experimental capabilities include:

- Object detection
- Multi-object recognition
- Scene recognition
- OCR
- Document reading
- Medicine-strip reading
- Packaging-text recognition
- Animal recognition
- Traffic-light recognition
- Environmental understanding
- Face-presence detection
- Returning-user recognition
- Mood and expression signals
- Approximate age-group estimation
- Voice-triggered visual questions

Vision results are confidence-based and may require user verification.

---

## 🪔 Panchang and Jyotish Intelligence

**Status:** ✅ Live / 🚧 Expanding

Current and developing capabilities include:

- Tithi
- Nakshatra
- Yoga
- Karana
- Sunrise and sunset
- Moonrise and moonset
- Rahu Kaal
- Choghadiya
- Bhadra
- Hora
- Muhurta
- Lahiri Ayanamsa
- Location-aware Panchang
- Tara Bala
- Chandra Bala
- Kundli-related guidance

Exact astronomical values should come from calculation services or structured sources before entering the language-model explanation layer.

---

## 📖 Scripture Intelligence

**Status:** ✅ Live / 🚧 Expanding

Current scripture-development areas include:

- Bhagavad Gita
- Valmiki Ramayan
- Vedas
- Upanishads
- Puranas
- Sanskrit literature
- Mantras
- Aartis
- Stotras
- Indian philosophy
- Dharma-related knowledge

Preferred retrieval flow:

```text
User Query
  ↓
Scripture Intent Detection
  ↓
Exact Local Lookup
  ↓
Structured Retrieval / RAG
  ↓
Source Validation
  ↓
BRAHM Explanation
```

The system should distinguish between original source text, translation, commentary, context, and AI-generated explanation.

---

# 🦅 Garudaa LLMG 108 V2

**Status:** 🚧 In Development

## Project Objective

Garudaa LLMG 108 V2 is being developed as a local, private, India-focused intelligence and reasoning layer for the BRAHM-AI ecosystem.

It is not intended to be only a renamed general-purpose model.

The objective is to create a compact intelligence engine capable of supporting:

- Hindi-first conversation
- Devanagari understanding
- Sanskrit-related queries
- Indian-language input
- English and multilingual interaction
- Indian conversational context
- Structured knowledge retrieval
- Scripture-grounded responses
- Local inference
- CPU and GPU deployment profiles
- BRAHM-AI platform integration

---

## Compact Local Model Development

Garudaa LLMG 108 V2 is being evaluated around a compact **3B-class local language model architecture**.

Planned development areas include:

- Instruction tuning
- Hindi response quality
- Sanskrit and Devanagari understanding
- Indian terminology
- Multilingual comprehension
- Response consistency
- Reduced hallucination
- Context retention
- Short and structured responses
- CPU inference optimization
- GPU acceleration
- Quantized deployment
- Ollama-compatible local serving
- API-based model access

The final base checkpoint, model family, quantization, adapter strategy, and training configuration will be documented after technical validation.

---

## Garudaa Hybrid Intelligence Modes

### 1. Exact Mode

Used when a verified local helper or structured dataset can answer directly.

Examples:

- Scripture verse
- Chapter or Sarga information
- Panchang value
- Structured user balance
- Account quota
- Known local data

### 2. Retrieval-Augmented Generation Mode

Used when relevant source context must be retrieved before generating an explanation.

```text
User Query
  ↓
Query Normalization
  ↓
Exact Lookup
  ↓
RAG Retrieval
  ↓
Best Source Selection
  ↓
Garudaa Reasoning
  ↓
Grounded Response
```

### 3. General Conversation Mode

Used when a query does not require an exact structured source.

This mode may handle:

- General conversation
- Explanation
- Summarization
- Language assistance
- Non-source-dependent reasoning
- Contextual follow-up questions

---

## Garudaa RAG Development

Planned and active RAG work includes:

- Local SQLite knowledge storage
- Structured scripture indexing
- Metadata-based retrieval
- Exact-title and alias matching
- Semantic retrieval
- Best-source selection
- Duplicate-source control
- Compact context generation
- Source-only fallback
- Retrieval-confidence handling
- Query normalization
- Multilingual retrieval
- Reindexing tools
- Dataset version tracking

RAG responses should identify whether the result came from:

- Exact retrieval
- Structured data
- RAG context
- General model reasoning
- Fallback mode

---

## Garudaa Runtime Architecture

```text
BRAHM-AI Request
  ↓
Identity and Quota Validation
  ↓
Language and Intent Detection
  ↓
Exact Helper Lookup
  ↓
RAG Retrieval
  ↓
Garudaa Local Model
  ↓
Safety and Response Formatting
  ↓
BRAHM True
  ↓
Text or Voice Delivery
```

Runtime goals include:

- Local inference
- Private processing
- Reduced external API dependency
- Lower operational cost
- CPU-compatible execution
- Optional GPU deployment
- Timeout protection
- Model pre-warming
- Compact prompt context
- Graceful fallback
- Usage metering
- Structured logging

---

## Garudaa Deployment Profiles

### Garudaa LLMG 108

Planned for:

- Higher-quality local reasoning
- RAG-assisted knowledge responses
- Advanced multilingual tasks
- API and platform use
- GPU or optimized server deployment

### Garudaa LLMG CPU

Planned for:

- Lightweight inference
- Low-cost local deployment
- Short responses
- Limited hardware environments
- Fallback processing
- Internal utility tasks

The two runtime classes may use different quantization, context limits, generation limits, daily quotas, token balances, and performance profiles.

---

## Garudaa Identity, Quota, and Usage Layer

Integration areas include:

- BRAHM user identity
- Daily free usage
- Purchased AI tokens
- Garudaa LLMG 108 balance
- Garudaa CPU balance
- BHM Power Pack
- Request metering
- Usage history
- Expiry-aware token lots
- Quota enforcement
- Plan-based limits
- API usage billing

Usage systems should remain separate from the answer-generation logic.

---

## Garudaa Integration with BRAHM True and Voice

The intended architecture is:

- BRAHM True remains the main conversational flow.
- Garudaa operates as a model and intelligence provider inside that flow.
- BRAHM Voice does not create a separate Garudaa response engine.
- Voice receives the final response from the existing BRAHM True flow.
- Identity, quota, and model-routing logic remain shared.
- Exact helpers run before general model generation.
- Garudaa should not replace verified structured data with invented answers.

---

## Garudaa V2 Success Criteria

Garudaa LLMG 108 V2 should demonstrate:

- Strong Hindi comprehension
- Natural Devanagari output
- Improved Sanskrit-query understanding
- Reliable instruction following
- Reduced hallucination
- Consistent short answers
- Correct helper and RAG usage
- Source-grounded scripture responses
- CPU-compatible inference
- Stable API serving
- Predictable latency
- Safe timeout behaviour
- Clear fallback responses
- BRAHM True integration
- BRAHM Voice compatibility
- Quota and billing compatibility

---

# 🔌 BRAHM-AI Developer API

**Status:** 🚧 In Development / 🗓️ Planned

The BRAHM-AI Developer API is being developed to provide selected intelligence capabilities to websites, applications, developers, institutions, researchers, businesses, AI agents, and approved integration partners.

---

## Planned API Categories

### Core Conversation API

```http
POST /api/v1/chat
```

Planned capabilities:

- General conversation
- Language selection
- Session context
- Specialized-helper routing
- Structured responses
- Source metadata
- Streaming where supported
- Garudaa model routing

---

### Panchang API

```http
GET /api/v1/panchang/daily
GET /api/v1/panchang/rahu-kaal
GET /api/v1/panchang/choghadiya
GET /api/v1/panchang/bhadra
GET /api/v1/panchang/hora
GET /api/v1/panchang/ayanamsa
```

Planned inputs:

- Date
- Local time
- Latitude
- Longitude
- Timezone
- City
- Language

Planned response areas:

- Tithi
- Nakshatra
- Yoga
- Karana
- Sunrise
- Sunset
- Rahu Kaal
- Choghadiya
- Bhadra
- Hora
- Lahiri Ayanamsa
- Calculation metadata

---

### Scripture API

```http
POST /api/v1/scriptures/search
GET /api/v1/scriptures/{scripture}/{section}/{chapter}
GET /api/v1/scriptures/{scripture}/verse/{verse_id}
```

Planned capabilities:

- Exact scripture lookup
- Natural-language scripture search
- Verse retrieval
- Sanskrit source text
- Translation
- Explanation
- Chapter and section metadata
- Source-edition metadata
- Related references
- Retrieval-mode reporting

---

### Language API

```http
POST /api/v1/language/process
```

Planned tasks:

- Language detection
- Translation
- Transliteration
- Grammar correction
- Script normalization
- Sentence explanation
- Multilingual response generation
- Indian-language processing
- Sanskrit assistance

---

### Vision and OCR API

```http
POST /api/v1/vision/analyze
```

Planned modes:

- General image understanding
- Object detection
- Scene analysis
- OCR
- Document reading
- Medicine-label reading
- Packaging analysis

---

### Agriculture and Mandi API

```http
GET /api/v1/mandi/prices
POST /api/v1/agriculture/advice
GET /api/v1/agriculture/weather-context
```

---

### Market Intelligence API

```http
POST /api/v1/market/analyze
```

Market responses will remain educational and not financial advice.

---

### Voice API

```http
POST /api/v1/voice/session
POST /api/v1/voice/transcribe
POST /api/v1/voice/synthesize
```

Planned capabilities:

- Voice-session initialization
- Speech-to-Text
- Language selection
- TTS voice routing
- Accent selection
- Audio output
- Streaming responses
- Session context
- Usage metering
- Avatar-state metadata

---

### Automation API

```http
POST /api/v1/automation/plan
POST /api/v1/automation/execute
GET /api/v1/automation/status/{task_id}
```

Sensitive actions will require explicit authorization and confirmation.

---

### Business Agent API

Planned capabilities include:

- Agent creation
- Business knowledge
- Inbound-call routing
- Outbound-call workflows
- Lead creation
- Conversation records
- Call summaries
- Follow-up scheduling
- CRM timeline
- Usage and billing
- Provider integrations

Business-agent APIs may be managed separately through the BRAHM AI Agents platform.

---

## Planned API Authentication

The planned authentication system includes:

- API keys
- Bearer tokens
- Development keys
- Production keys
- Internal service keys
- Restricted partner keys
- Key rotation
- Key revocation
- Permission scopes
- Per-key quotas
- Usage metering

Example:

```http
Authorization: Bearer brahm_live_xxxxxxxxx
Content-Type: application/json
```

API keys must not be exposed in public frontend code.

---

## Planned API Infrastructure

The developer platform is planned to include:

- Versioned endpoints
- API-key dashboard
- Authentication and authorization
- Scope-based permissions
- Rate limiting
- Daily quotas
- Usage metering
- Request IDs
- Idempotency support
- Structured errors
- Streaming responses
- Webhooks
- Audit logs
- Provider fallback
- Timeout handling
- Source metadata
- Data-freshness metadata
- Test and production environments
- Usage analytics
- Plan management
- BHM or plan-based billing
- Abuse protection
- Developer documentation
- Code examples
- SDKs

---

## 🛣️ Development Phases

### Phase 1 — Unified Platform Foundation

**Status:** ✅ Live / Continuing Improvement

- Unified `brahm-ai.in` platform
- BRAHM True
- BRAHM Voice
- Multilingual conversation
- Vision and OCR
- Panchang and Jyotish
- Scripture intelligence
- News and live information
- Market and agriculture modules
- PotliPay access
- BRAHM AI Agents
- Centralized API-driven frontend architecture

### Phase 2 — Garudaa LLMG 108 V2 Foundation

**Status:** 🚧 In Development

- Compact 3B-class local model evaluation
- Hindi-first instruction tuning
- Sanskrit and Devanagari evaluation
- Local Ollama-compatible runtime
- CPU deployment profile
- GPU deployment profile
- Quantization testing
- Context-size testing
- Response-style tuning
- Exact-first routing
- RAG integration
- Source-only fallback
- Timeout and failure handling
- BRAHM True integration
- Voice compatibility
- Identity and quota integration

### Phase 3 — Developer API Core

**Status:** 🚧 In Development / 🗓️ Planned

- API gateway
- Versioned routes
- Authentication
- API-key generation
- Quota enforcement
- Usage metering
- Request IDs
- Standard response envelope
- Structured error codes
- Developer documentation
- Internal API testing
- Partner access controls

### Phase 4 — Private API Preview

**Status:** 🗓️ Planned

Initial private-access categories may include:

- Core conversation
- Panchang
- Scripture search
- Language processing
- Vision and OCR
- Mandi Bhav
- Voice sessions
- Garudaa model access

### Phase 5 — Public Developer Beta

**Status:** 🗓️ Planned

- Developer registration
- API-key dashboard
- Free test quota
- Paid usage plans
- Request logs
- Usage analytics
- Documentation portal
- Code examples
- Webhooks
- Rate-limit visibility
- Support workflow

### Phase 6 — SDK and Integration Ecosystem

**Status:** 🔍 Research / 🗓️ Planned

Potential SDKs:

- Python
- JavaScript
- TypeScript
- PHP
- REST examples
- Website-assistant widgets
- Panchang widgets
- Scripture-search widgets
- Voice-agent integrations

### Phase 7 — Private and Sovereign AI Deployment

**Status:** 🔍 Research

Long-term areas include:

- Private enterprise deployment
- Institution-specific knowledge systems
- Local inference servers
- Offline or limited-connectivity usage
- Indian-language model infrastructure
- Secure RAG deployment
- Local scripture databases
- On-premise Garudaa inference
- Regional data systems
- Government and institutional integrations

---

## 🛡️ Safety and Reliability Roadmap

Planned work includes:

- Exact-source preference
- Source attribution
- Retrieval-mode disclosure
- Confidence-aware vision output
- Medicine-information warnings
- Financial-information disclaimers
- User confirmation for sensitive actions
- API abuse protection
- Prompt-injection resistance
- Cross-user memory isolation
- Secure credential handling
- Quota enforcement
- Audit logging
- Privacy-aware camera processing
- Safer fallback responses
- Structured failure reporting

---

## 📊 Quality and Evaluation Roadmap

Garudaa and BRAHM-AI modules will be evaluated for:

- Hindi accuracy
- English accuracy
- Indian-language quality
- Sanskrit-query understanding
- Devanagari output
- Instruction following
- Hallucination rate
- Source-grounding accuracy
- Scripture-reference accuracy
- Panchang calculation integrity
- Vision confidence
- OCR accuracy
- Medicine-name extraction
- Response latency
- CPU memory usage
- GPU performance
- API reliability
- Quota accuracy
- Fallback behaviour
- Voice-response continuity

---

## 🚫 Current Non-Goals

BRAHM-AI does not currently claim to provide:

- Guaranteed medical diagnosis
- Medical prescriptions
- Guaranteed financial returns
- Fully autonomous sensitive actions without confirmation
- Perfect visual recognition
- Error-free OCR
- A replacement for qualified professionals
- Public access to private model weights or production infrastructure
- Unrestricted commercial reuse of proprietary BRAHM-AI systems

---

## 🤝 Collaboration Areas

BRAHM-AI welcomes approved discussions with:

- AI researchers
- Indian-language experts
- Sanskrit scholars
- Scripture researchers
- Educational institutions
- Agriculture organizations
- Public-data providers
- Voice and speech providers
- Vision and OCR specialists
- GPU and infrastructure partners
- API integration partners
- Businesses seeking AI agents

Please review:

- [CONTRIBUTING.md](./CONTRIBUTING.md)
- [LICENSE](./LICENSE)
- [SECURITY.md](./SECURITY.md)
- [SUPPORT.md](./SUPPORT.md)

---

## 📬 Contact

For API access, technical collaboration, licensing, institutional deployment, or approved partnerships:

- **Email:** info@ramcoin.org
- **Website:** https://brahm-ai.in
- **GitHub:** https://github.com/brahm-ai-official/brahm-ai
- **BRAHM AI Agents:** https://www.brahm-ai-agents.com

---

## 📅 Roadmap Updates

Daily and milestone-level development updates are recorded in:

[UPDATES.md](./UPDATES.md)

---

**BRAHM-AI — Ancient Knowledge. Modern Intelligence. Connected Action.**

© 2025–2026 BRAHM-AI and Royal Web 3 Blockchain. All Rights Reserved.
