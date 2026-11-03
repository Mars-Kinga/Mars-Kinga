# Hi, I'm Jinjia (Mars) Zheng 👋

I'm a Software Engineering student at East China Normal University and a former computer science exchange student at UC Berkeley. I build native iOS apps, AI-assisted software tools, and systems that connect software with hardware. I care about understandable user decisions, measured performance, and reliable workflows.

Based in Shanghai · Open to a six-month full-time software engineering internship · [Explore my repositories](https://github.com/Mars-Kinga?tab=repositories)

## Featured project: [Picora · 轻选](https://github.com/Mars-Kinga/picora)

A native iPhone and iPad photo-management app built with Swift and SwiftUI. Review photos one swipe at a time, resume later, and confirm changes before they reach the system photo library.

- **On-device recommendations:** Vision image features, OCR, and aesthetic and face-capture quality scores help group similar photos and suggest which to keep; SHA-256 checks complete resources for exact duplicates.
- **Recoverable review:** PhotoKit and SwiftData support staged decisions, a draggable timeline with saved browsing positions, continuous review of deferred photos, and verified Live Photo-to-still conversion.
- **Adaptive interface:** Portrait and wide layouts follow the available window size. The app supports English, Simplified Chinese, and Traditional Chinese with Taiwan wording.
- **Performance and power:** Incremental SQLite caching avoids repeat analysis. Background work adjusts to charging, Low Power Mode, and thermal conditions.

<p align="center">
  <a href="https://github.com/Mars-Kinga/picora"><img src="https://github.com/Mars-Kinga/picora/releases/download/readme-media-20261021/suggestions-light-20261013.png" width="200" alt="Picora photo suggestions"></a>
  <a href="https://github.com/Mars-Kinga/picora"><img src="https://github.com/Mars-Kinga/picora/releases/download/readme-media-20261021/iphone-duo-suggestions.png" width="510" alt="Picora wide suggestions and photo comparison"></a>
</p>

[View the project and privacy policy →](https://github.com/Mars-Kinga/picora) · [中文隐私政策](https://mars-kinga.github.io/picora/privacy/PRIVACY_POLICY.zh-CN.html) · [English privacy policy](https://mars-kinga.github.io/picora/privacy/PRIVACY_POLICY.en.html)

The public repository contains the project overview and privacy policy; the app source is kept private. The current development version is 1.1 for iOS / iPadOS 26+; its feature source and tests are synchronized to the private repository. No public App Store or TestFlight download is listed.

`Swift` `SwiftUI` `PhotoKit` `SwiftData` `Vision` `CryptoKit` `SQLite`

## More projects

### Moby · Edge–cloud AI companion

An ESP32-S3 companion robot with local “Hey Moby” wake detection, LVGL expressions, and a Python Agent Harness connecting Qwen ASR, validated tool execution, and TTS. Device actions use explicit receipts; long-term facts use versioned microSD storage with user-controlled editing and deletion.

The repository contains the P5 speech pipeline. Local P6 development adds automatic preference candidates, selective memory retrieval, and waiting-audio coordination. P6 remains under validation: firmware build/flash and controlled protocol checks do not establish natural voice quality, end-to-end latency, or reliable SD operation.

[Project overview and implementation status →](https://github.com/Mars-Kinga/moby-ai-companion) *(private repository; access required)*

`ESP32-S3` `C/C++` `FreeRTOS` `Python` `Agent Harness` `Speech APIs`

### [LAND-DATA](https://github.com/Mars-Kinga/LAND-DATA) · AI-assisted data tooling

A Python/SQLite pipeline for collecting and reviewing travel places and knowledge. Deterministic processing runs by default, with optional LLM extraction, field-level provenance, and separate QAU knowledge and Place release bridges.

Its development-stage location-verification harness includes read-only tool controls, call budgets, SQLite checkpoints, an independent goal gate, and human handoff. A fixed-order replay of 1,004 real records routed 20 cross-source coordinate discrepancies to review; this measures evidence routing, not location accuracy. Model-guided tool selection has been demonstrated on a synthetic case; real-case dynamic evaluation and independent gold labels remain in progress.

[Implementation status and evaluation boundaries →](https://github.com/Mars-Kinga/LAND-DATA/blob/main/docs/implementation-status.md)

`Python` `SQLite` `Agent Harness` `LLM APIs` `Evaluation` `Human Review`

### [Kitchen Assistant Robot Skill](https://github.com/Mars-Kinga/kitchen_assistant) · Guided cooking and robot workflows

A Python guided-cooking runtime with a LAN web console, 440 fixed recipes, local-first lookup, schema-validated Qwen generation, and camera ingredient questions. A deterministic state machine manages recipe selection, ingredient confirmation, cooking steps, timers, pause/resume, and completion.

Video and image-text tutorials become editable recipe drafts with source evidence and AI suggestions, then enter the cooking workflow after user confirmation. The public repository includes the console, portable setup scripts, offline Python tests, and UI regression checks. Robot adapters remain simulated; cloud services, voice and physical-device behavior require separate validation. [See the implementation and setup →](https://github.com/Mars-Kinga/kitchen_assistant#quick-start)

`Python` `LLM APIs` `Computer Vision` `State Machines` `Test Automation`

### [Online Museum](https://github.com/Mars-Kinga/OnlineMuseum) · Team web project

A Vue 3 digital museum of Central Asia along the Silk Road, with an interactive map, country pages, and a 3D exhibition hall. This is a team repository.

`Vue 3` `JavaScript` `model-viewer` `Responsive Design`

## Technical focus

- **iOS:** SwiftUI, PhotoKit, SwiftData, on-device image analysis, local persistence, and media interactions
- **AI and data:** Python, LLM APIs, evaluation, PyTorch, scikit-learn, and TensorFlow Lite Micro
- **Hardware workflows:** ESP32-S3, FreeRTOS, TCP/IP, data acquisition, and diagnostics
- **Software engineering:** C/C++, JavaScript/TypeScript, C#/.NET, SQL, REST APIs, and automated testing
