# 🤝 Contributing to BRAHM-AI

Thank you for your interest in contributing to **BRAHM-AI**.

BRAHM-AI is an India-first artificial intelligence ecosystem combining multilingual conversation, Indian knowledge, voice interaction, computer vision, Panchang and Jyotish utilities, scripture intelligence, automation, agriculture, education, business AI, and developer services.

The project is developed with a strong focus on:

* technical accuracy;
* modular architecture;
* responsible AI;
* Indian-language accessibility;
* source integrity;
* privacy and security;
* respectful handling of Indian knowledge traditions;
* reliable production deployment.

---

## ⚠️ Contribution Policy

BRAHM-AI is a **proprietary project** and is not currently open for unrestricted public code contributions.

Do not submit a Pull Request unless you have received prior approval from an authorized BRAHM-AI maintainer.

You may still:

* report a bug;
* suggest a feature;
* propose a collaboration;
* report a security concern;
* recommend a language or scripture correction;
* request API or institutional access;
* submit a technical proposal for review.

For collaboration approval:

📩 **Email:** [info@ramcoin.org](mailto:info@ramcoin.org)
🌐 **Platform:** https://brahm-ai.in
🌐 **Ecosystem:** https://www.ramcoin.org

Public repository visibility does not grant permission to copy, reuse, modify, deploy, redistribute, or commercially use BRAHM-AI source code, data, prompts, models, documentation, or architecture.

Please review the repository license before submitting any material.

---

## 🧭 Contribution Paths

BRAHM-AI accepts different types of approved contributions.

### 1. Bug Reports

A useful bug report should include:

* affected page or module;
* exact URL or API route;
* expected behaviour;
* actual behaviour;
* reproduction steps;
* browser, device, and operating system;
* relevant screenshots or logs;
* whether the issue is consistent or intermittent;
* whether login, camera, microphone, location, or another permission is involved.

Never include:

* passwords;
* session cookies;
* API keys;
* access tokens;
* private user information;
* complete environment files;
* payment credentials;
* production database exports.

---

### 2. Feature Proposals

A feature proposal should describe:

* the user problem;
* intended users;
* proposed behaviour;
* affected BRAHM-AI module;
* expected inputs and outputs;
* privacy or safety concerns;
* API or infrastructure requirements;
* possible limitations;
* how success should be measured.

Large features should not begin with implementation code. They should first be reviewed and approved through an issue, discussion, or written technical proposal.

---

### 3. Documentation Contributions

Approved documentation work may include:

* README improvements;
* API documentation;
* integration examples;
* setup instructions;
* architecture diagrams;
* changelog entries;
* language corrections;
* developer guides;
* responsible-use documentation;
* troubleshooting instructions.

Documentation must distinguish clearly between:

* features currently live;
* experimental capabilities;
* planned features;
* internal-only components;
* unsupported or deprecated behaviour.

Do not describe a planned feature as already available.

---

### 4. Language Contributions

BRAHM-AI supports Hindi-first and multilingual interaction.

Language contributions may include:

* translation corrections;
* grammar improvements;
* script normalization;
* STT trigger phrases;
* TTS pronunciation guidance;
* transliteration rules;
* regional vocabulary;
* user-interface labels;
* multilingual safety wording.

Language contributors should preserve:

* the original meaning;
* natural sentence structure;
* culturally appropriate terminology;
* consistent product naming;
* correct script usage.

Do not translate official product names unless an approved localized name exists.

---

### 5. Scripture and Sanskrit Contributions

Scripture-related contributions require additional care.

A proposal should identify:

* scripture name;
* edition or source;
* Kanda, chapter, Sarga, Sukta, Sutra, or verse reference;
* original Sanskrit or source text;
* proposed correction;
* translation or explanation;
* known textual variants;
* source attribution.

Contributors must not:

* invent a verse;
* merge unrelated editions silently;
* present interpretation as original scripture;
* modify source text without preserving the original;
* remove source or edition information;
* use unverified AI-generated Sanskrit as canonical text.

Preferred scripture workflow:

1. Preserve the original source text.
2. Record obvious corrections separately.
3. Validate numbering and references.
4. Create structured metadata.
5. Add translation and explanation.
6. Test exact retrieval.
7. Test natural-language retrieval.
8. Integrate with the appropriate helper or router.
9. Verify that unrelated scriptures are not affected.

---

## 🔐 Approval Requirements

An approved contributor may be required to complete one or more of the following:

* identity verification;
* contributor access approval;
* Non-Disclosure Agreement;
* Contributor License Agreement;
* intellectual-property declaration;
* data-source declaration;
* security review;
* repository-specific onboarding;
* limited environment access;
* module ownership assignment.

Access is granted only for the approved purpose and may be restricted by:

* repository;
* module;
* environment;
* branch;
* data scope;
* duration;
* deployment role.

Approval to contribute to one module does not automatically grant access to other BRAHM-AI systems.

---

## 🌿 Development Workflow

Approved contributors should follow this workflow.

### Step 1: Create or Reference an Issue

Before beginning a significant change:

* create an issue or technical proposal;
* describe the problem;
* define the expected result;
* identify affected files and modules;
* document known risks;
* wait for maintainer approval.

Minor approved corrections may be submitted directly when instructed by a maintainer.

---

### Step 2: Confirm the Correct Repository and Branch

The default integration branch is generally:

`main`

However, contributors may be assigned a specific branch such as:

* `develop`;
* `staging`;
* `feature/<name>`;
* `fix/<name>`;
* `docs/<name>`;
* `release/<version>`.

Do not push directly to protected branches unless explicitly authorized.

---

### Step 3: Create a Focused Branch

Recommended naming examples:

* `feature/panchang-api-v1`
* `feature/multilingual-tts-router`
* `fix/voice-double-trigger`
* `fix/ramayan-title-routing`
* `docs/api-authentication`
* `refactor/vision-service-layer`
* `security/session-cookie-hardening`

Use lowercase words separated by hyphens.

---

### Step 4: Make a Focused Change

Each contribution should solve one clearly defined problem.

Avoid combining unrelated changes such as:

* feature implementation;
* broad formatting changes;
* dependency upgrades;
* database migrations;
* UI redesign;
* documentation rewrites

inside the same Pull Request unless the maintainer approved them as one unit.

---

### Step 5: Test Before Submission

Test the affected module and any connected critical flow.

At minimum, confirm:

* syntax is valid;
* application starts successfully;
* existing routes still respond;
* affected API returns the expected status;
* no secrets were added;
* no unrelated file changed;
* fallback behaviour still works;
* logs contain no new critical errors;
* mobile behaviour remains usable where applicable.

Module-specific tests may also be required.

---

### Step 6: Submit a Pull Request

The Pull Request must include:

* clear title;
* linked issue or approval reference;
* summary of the change;
* files or modules affected;
* implementation details;
* test results;
* screenshots where UI changed;
* API request and response examples where applicable;
* database or migration details;
* security and privacy impact;
* rollback instructions;
* known limitations.

---

## 📝 Commit Message Convention

Use clear, concise, and descriptive commit messages.

Recommended format:

`<type>(<scope>): <description>`

Common types:

* `feat` — new capability;
* `fix` — bug fix;
* `docs` — documentation;
* `refactor` — code restructuring without intended behaviour change;
* `perf` — performance improvement;
* `test` — test coverage or test correction;
* `security` — security improvement;
* `build` — build or dependency change;
* `ci` — CI/CD configuration;
* `chore` — maintenance task;
* `data` — structured dataset update;
* `scripture` — scripture data or retrieval update;
* `api` — API-specific change.

Examples:

* `feat(voice): add multilingual STT routing`
* `fix(voice): prevent duplicate transcript submission`
* `feat(panchang): add location-aware Bhadra calculation`
* `scripture(ramayan): add Aranyakanda Sarga 6 data`
* `fix(scripture): prevent title-match routing conflict`
* `api(auth): add per-key quota validation`
* `perf(vision): reduce camera frame processing load`
* `docs(readme): document upcoming developer API`
* `security(session): rotate session after login`
* `data(mandi): normalize English crop aliases`

Emoji may be used, but the message must remain understandable without it.

Examples:

* `🎙️ feat(voice): add multilingual STT routing`
* `🐛 fix(chat): prevent repeated user message`
* `📖 scripture(gita): improve verse reference matching`

---

## 🧱 Code Quality Standards

### General Requirements

Code should be:

* readable;
* modular;
* testable;
* defensive;
* documented where behaviour is not obvious;
* consistent with the existing project structure;
* compatible with supported production environments.

Avoid:

* unnecessary abstractions;
* duplicated business logic;
* hard-coded credentials;
* hidden side effects;
* global mutable state without justification;
* silent exception handling;
* broad changes unrelated to the approved task.

---

### Python

Python contributions should generally include:

* clear function and variable names;
* type hints where practical;
* narrow exception handling;
* validation for external input;
* structured logging;
* reusable helper functions;
* separation between routing, business logic, data access, and provider integrations.

Avoid placing large amounts of business logic directly inside Flask or FastAPI route handlers.

Preferred separation:

```text
route
  ↓
request validation
  ↓
service or helper
  ↓
database / provider / model
  ↓
structured response
```

---

### JavaScript and TypeScript

Frontend contributions should:

* avoid blocking the main UI thread;
* clean up event listeners;
* clean up timers and media streams;
* prevent duplicate submissions;
* handle permission denial;
* include safe network-error handling;
* preserve mobile compatibility;
* avoid exposing secrets;
* keep UI logic separate from backend intelligence logic.

Animation and media code must not interfere with:

* microphone capture;
* Text-to-Speech playback;
* camera processing;
* chat submission;
* navigation;
* accessibility.

---

### PHP

Legacy or active PHP modules should:

* validate and sanitize request input;
* use prepared database statements;
* escape output appropriately;
* protect state-changing requests;
* avoid mixing sensitive secrets into public files;
* keep API and UI behaviour clearly separated where possible.

New complex intelligence logic should preferably be exposed through a service or API rather than added as large inline UI scripts.

---

## 🔌 API Contribution Standards

All approved API work should follow a consistent structure.

### Versioning

Public or partner APIs should use versioned paths, for example:

```text
/api/v1/chat
/api/v1/panchang/daily
/api/v1/scriptures/search
/api/v1/vision/analyze
```

Breaking changes require:

* a new API version;
* migration documentation;
* deprecation notice;
* compatibility period where practical.

---

### Request Validation

Every endpoint should validate:

* authentication;
* authorization;
* required fields;
* data types;
* length limits;
* supported enum values;
* uploaded file type and size;
* language codes;
* location or timezone fields;
* rate and quota limits.

Invalid input should return a structured error rather than a server exception.

---

### Response Structure

API responses should be predictable.

Suggested success structure:

```json
{
  "success": true,
  "request_id": "req_xxxxx",
  "data": {},
  "meta": {
    "language": "hi",
    "source_mode": "structured"
  }
}
```

Suggested error structure:

```json
{
  "success": false,
  "request_id": "req_xxxxx",
  "error": {
    "code": "INVALID_REQUEST",
    "message": "A valid location is required."
  }
}
```

---

### Status Codes

Use appropriate HTTP status codes:

* `200` — successful request;
* `201` — resource created;
* `202` — accepted for supported processing;
* `400` — invalid request;
* `401` — authentication required;
* `403` — access denied;
* `404` — resource not found;
* `409` — conflicting state;
* `413` — uploaded content too large;
* `422` — validation failure;
* `429` — quota or rate limit exceeded;
* `500` — unexpected server error;
* `502` — upstream provider failure;
* `503` — service temporarily unavailable;
* `504` — upstream timeout.

---

### API Security

Contributors must never:

* expose API keys in browser code;
* commit `.env` files;
* log authorization headers;
* return internal exception traces publicly;
* trust client-provided user IDs without validation;
* bypass quota checks;
* disable authentication for convenience;
* expose private administrative routes;
* accept unrestricted file uploads.

API changes should consider:

* authentication;
* authorization;
* rate limiting;
* replay protection;
* idempotency;
* CORS;
* CSRF where applicable;
* input limits;
* audit logging;
* abuse prevention;
* timeout handling;
* provider fallback.

---

## 🧠 AI and Model Contribution Standards

AI-related contributions must document:

* model or provider;
* model version;
* intended task;
* prompt or routing purpose;
* expected input;
* expected output;
* known limitations;
* latency impact;
* cost impact;
* fallback behaviour;
* safety implications.

Do not silently replace a production model or provider.

Model changes require comparison against the current system for:

* response accuracy;
* Hindi quality;
* multilingual quality;
* hallucination rate;
* instruction following;
* latency;
* token usage;
* fallback behaviour;
* safety compliance.

---

## 📚 RAG and Knowledge Retrieval Standards

Retrieval-based contributions should preserve a source-first flow.

Recommended pipeline:

```text
User Query
  ↓
Intent Detection
  ↓
Exact Lookup
  ↓
RAG Retrieval
  ↓
Source Validation
  ↓
Reasoning
  ↓
Attributed Response
```

RAG contributions should document:

* source dataset;
* chunking method;
* embedding model;
* index type;
* metadata fields;
* retrieval limits;
* ranking logic;
* confidence or fallback behaviour;
* duplicate handling;
* update and reindex process.

Do not place unverified generated text into a canonical knowledge database.

---

## 🌍 Multilingual Contribution Standards

Multilingual changes should test:

* native script;
* Latin transliteration;
* mixed-language input;
* language dropdown selection;
* automatic detection where applicable;
* STT recognition;
* displayed output;
* TTS pronunciation;
* gender and grammar consistency;
* fallback behaviour.

Hindi user-facing text should use Devanagari unless the product context specifically requires Roman transliteration.

---

## 🎙️ Voice Contribution Standards

Voice changes must preserve the shared intelligence architecture.

The expected flow is:

```text
User Voice
  ↓
Speech-to-Text
  ↓
Central BRAHM Conversation Flow
  ↓
Response Text
  ↓
Text-to-Speech
  ↓
Avatar / Audio Output
```

Do not create an independent answer engine for BRAHM Voice when the central BRAHM conversation flow is the designated source of truth.

Voice testing should include:

* first microphone permission;
* permission denied;
* silence;
* weak audio;
* user interruption;
* duplicate transcript prevention;
* long response playback;
* TTS failure;
* language switching;
* camera and voice running together;
* mobile browser behaviour.

---

## 📷 Vision Contribution Standards

Vision contributions must include:

* supported input type;
* frame or image validation;
* confidence threshold;
* OCR or detection method;
* user verification when uncertain;
* privacy behaviour;
* memory or storage behaviour;
* fallback result.

Do not describe probabilistic vision output as guaranteed fact.

For medicine or health-related vision:

* clearly display uncertainty;
* require user verification;
* avoid diagnosis;
* avoid personalized dosage instructions;
* include appropriate professional-care guidance.

---

## 🪔 Panchang and Jyotish Contribution Standards

Exact astronomical values must come from:

* dedicated computation;
* validated ephemeris or provider data;
* structured and testable calculation logic.

A language model must not invent:

* Tithi;
* Nakshatra;
* Yoga;
* Karana;
* Rahu Kaal;
* Choghadiya;
* Bhadra;
* sunrise;
* sunset;
* Lahiri Ayanamsa;
* planetary positions.

Every calculation contribution should test:

* date;
* time;
* latitude;
* longitude;
* timezone;
* daylight-saving behaviour where relevant;
* boundary transitions;
* location changes;
* invalid location input.

The reasoning layer may explain the result only after computation.

---

## 🔐 Security and Secrets

Never commit:

* `.env` files;
* API keys;
* database passwords;
* private keys;
* OAuth secrets;
* webhook secrets;
* SMTP credentials;
* payment credentials;
* access tokens;
* production session cookies;
* private certificates;
* user data exports.

Use environment variables or approved secret-management systems.

Before submitting a Pull Request:

```bash
git diff --cached
git status
```

Review all staged files manually.

If a secret is committed:

1. Notify the maintainer immediately.
2. Rotate or revoke the credential.
3. Remove it from repository history where required.
4. Do not rely only on deleting it in a later commit.

---

## 🛡️ Privacy Requirements

Contributions must not expose or unnecessarily collect:

* user conversations;
* voice recordings;
* camera frames;
* face images;
* face signatures;
* location history;
* contact information;
* medical information;
* financial information;
* account credentials;
* payment information;
* private documents.

Collect only data required for the approved feature.

Document:

* what is collected;
* why it is needed;
* where it is processed;
* how long it is retained;
* whether it is shared with a provider;
* how the user can control it.

---

## 🗄️ Database and Migration Guidelines

Database changes must include:

* migration or safe upgrade method;
* rollback instructions;
* default values;
* indexing impact;
* compatibility with existing records;
* backup considerations;
* validation of duplicate records;
* production-size performance considerations.

Do not:

* delete production fields casually;
* rename columns without migration;
* reset production databases;
* include real user data in tests;
* assume a blank database.

---

## ⚡ Performance Requirements

Contributions should avoid unnecessary:

* model loading;
* repeated database queries;
* large frontend bundles;
* camera frame processing;
* synchronous network calls;
* unbounded loops;
* memory accumulation;
* duplicate API requests;
* repeated TTS or STT initialization.

Performance-sensitive changes should include before-and-after observations where possible.

---

## 🧪 Testing Guidelines

Depending on the contribution, testing may include:

* syntax checks;
* unit tests;
* helper-level tests;
* route tests;
* API contract tests;
* database tests;
* permission tests;
* browser tests;
* mobile tests;
* fallback tests;
* regression tests;
* multilingual tests;
* load or quota tests under authorization.

A test should verify behaviour, not merely confirm that code executes.

---

## 🚀 Production Safety

Production changes must follow the approved deployment process.

A production-ready contribution should include:

* backup instructions;
* deployment steps;
* syntax or build verification;
* service restart instructions;
* health check;
* endpoint verification;
* relevant log checks;
* rollback method.

Avoid direct production experimentation without:

* backup;
* approval;
* validation;
* rollback readiness.

---

## 🔄 Backward Compatibility

Changes must preserve existing supported behaviour unless the issue explicitly approves a breaking change.

Before modifying a shared helper or router, identify:

* all callers;
* affected routes;
* alias behaviour;
* fallback flow;
* existing data schema;
* Voice and True dependencies;
* account and quota dependencies.

A fix for one module must not silently break another.

---

## 📋 Pull Request Template

Use the following structure in approved Pull Requests:

```text
## Summary
Explain what changed and why.

## Related Issue
Link the approved issue or proposal.

## Affected Modules
List the files, services, routes, or products affected.

## Implementation
Describe the technical approach.

## Testing
List the commands and scenarios tested.

## API Changes
Describe endpoints, schemas, authentication, or response changes.

## Database Changes
Describe migrations, indexes, and rollback requirements.

## Security and Privacy
Describe any impact on credentials, permissions, user data, camera, microphone, or external providers.

## Screenshots
Include before-and-after screenshots for UI changes.

## Rollback
Explain how to restore the previous version.

## Known Limitations
Document anything not fully covered.
```

---

## ✅ Pull Request Checklist

Before submitting, confirm:

* [ ] I received approval to contribute.
* [ ] The change is linked to an approved issue or proposal.
* [ ] The Pull Request addresses one focused concern.
* [ ] I reviewed all changed files.
* [ ] No credentials or private data are included.
* [ ] Syntax, build, and relevant tests pass.
* [ ] Existing critical flows still work.
* [ ] API or schema changes are documented.
* [ ] Database changes include migration and rollback instructions.
* [ ] Security and privacy impact has been considered.
* [ ] UI changes were tested on relevant mobile and desktop layouts.
* [ ] Multilingual behaviour was tested where applicable.
* [ ] Documentation and `UPDATES.md` were updated when required.
* [ ] I disclosed all third-party code, models, data, and licenses.
* [ ] I have the legal right to submit this contribution.

---

## 📦 Third-Party Code and Data

Do not submit third-party code, models, datasets, media, fonts, translations, or documentation unless:

* the license permits the intended use;
* attribution requirements are documented;
* commercial restrictions are disclosed;
* source links are provided;
* maintainer approval has been received.

AI-generated code must also be reviewed for:

* correctness;
* security;
* licensing risks;
* invented APIs;
* duplicated copyrighted code;
* unsuitable dependencies.

The contributor remains responsible for validating submitted material.

---

## 🧾 Intellectual Property

By submitting an approved contribution, you confirm that:

* you created the contribution or have authority to submit it;
* it does not knowingly infringe third-party rights;
* it does not contain unauthorized confidential information;
* all external sources and licenses have been disclosed;
* you agree to any applicable contributor agreement.

Submission does not guarantee acceptance.

The applicable Contributor License Agreement or written collaboration agreement will control ownership and usage rights for accepted contributions.

---

## 🔍 Review Process

Maintainers may:

* request changes;
* request additional tests;
* request source verification;
* require security review;
* require legal or licensing clarification;
* split a large Pull Request;
* postpone a contribution;
* close an unapproved Pull Request;
* reject a change that conflicts with product direction.

Approval of an issue does not guarantee approval of the final implementation.

A contribution is considered accepted only after it has been reviewed and merged by an authorized maintainer.

---

## 🚨 Security Reports

Do not publish exploitable security vulnerabilities in public issues.

Send security reports privately to:

📩 **[ admin@ramcoin.org](mailto:admin@ramcoin.org)**
📩 **[ info@brahm-ai-in](mailto:info@brahm-ai-in)**

Include:

* affected service or URL;
* vulnerability type;
* reproduction steps;
* potential impact;
* proof of concept without destructive action;
* recommended mitigation, when available.

Do not:

* access unrelated user data;
* modify production data;
* interrupt service;
* perform denial-of-service testing;
* publish the vulnerability before coordinated disclosure;
* demand payment as a condition for responsible reporting.

---

## 📣 Code of Conduct

All contributors and collaborators must communicate respectfully.

Unacceptable behaviour includes:

* harassment;
* threats;
* discrimination;
* abusive communication;
* deliberate misinformation;
* unauthorized disclosure;
* impersonation;
* disruption of technical discussions;
* misuse of spiritual, cultural, or personal identity.

Technical disagreements should remain evidence-based and focused on the contribution.

---

## 🕉️ Knowledge and Cultural Responsibility

BRAHM-AI works with Indian languages, scriptures, philosophy, and cultural knowledge.

Contributors should:

* preserve source context;
* respect textual variants;
* avoid fabricated quotations;
* distinguish scripture from commentary;
* avoid sectarian hostility;
* use respectful terminology;
* document uncertainty;
* seek scholarly review where appropriate.

Spiritual presentation must not override factual, technical, legal, medical, or safety responsibilities.

---

## 🙌 Acknowledgement

Approved contributions help strengthen an ecosystem intended to connect Indian knowledge, modern intelligence, multilingual access, and practical digital action.

> 🌺 **“योगः कर्मसु कौशलम्”**
> *Excellence in action is Yoga.*

Thank you for contributing with clarity, responsibility, and respect.

---

**BRAHM-AI — Ancient Knowledge. Modern Intelligence. Connected Action.**

© 2025–2026 BRAHM-AI | Ramcoin Foundation | Royal Web 3 Blockchain Ecosystem
**All Rights Reserved**
